#### Test 83070177977a8d1_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 13:44:28.039  5908  5908 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-29 13:44:28.184  5908  5908 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:28.185  5908  5908 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:28.251  5908  5908 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 13:44:28.272  5908  5908 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 13:44:28.274  5908  5908 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 13:44:28.289  5908  5908 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 13:44:28.290  5908  5908 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-29 13:44:28.303  1033  1940 I ActivityManager: Killing 4940:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 13:44:28.335  1033  1920 W libprocessgroup: failed to open /acct/uid_10085/pid_4940/cgroup.procs: No such file or directory
08-29 13:44:28.344  2835  2853 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 13:44:28.346  2835  2853 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f2f49ca on behalf of 5908
08-29 13:44:28.351  4543  5965 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 13:44:28.392  1033  1740 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5966 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:28.418  5908  5908 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 13:44:28.460  5908  5908 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 13:44:28.559  5966  5966 D DocsApplication: Installing DEX configuration.
08-29 13:44:28.576  5966  5966 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 13:44:28.581  5966  5966 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{ca3f8e0 com.google.android.apps.docs}
08-29 13:44:28.597  5966  5966 D TAG     : onCreate()
08-29 13:44:28.620  5966  5966 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-29 13:44:28.777  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:44:28.847  4543  5965 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 496 ms] updated apps [took 495 ms] 
08-29 13:44:28.961  6000  6000 D AndroidRuntime: 
08-29 13:44:28.961  6000  6000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:44:28.964  6000  6000 D AndroidRuntime: CheckJNI is OFF
08-29 13:44:28.989  2786  2786 I MusicWidget: mDelayedStopHandler : unbind
08-29 13:44:28.993  2186  2186 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 13:44:28.994  2186  2186 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 13:44:28.995  2186  2186 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 13:44:28.998  2186  2186 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 13:44:28.999  2186  2186 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 13:44:28.999  2186  2186 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 13:44:29.002  2186  2186 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 13:44:29.003  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 13:44:29.005  1033  2032 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3d25554bcom.lge.music.MediaPlaybackService$5@2be45b28
08-29 13:44:29.006  2186  2186 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 13:44:29.008  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.009  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.009  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.009  2186  2186 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@327ce736
08-29 13:44:29.010  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.010  2186  2186 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 13:44:29.010  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.011  2186  2186 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 13:44:29.011  2186  2186 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 13:44:29.011  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.011  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.012  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.012  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.013  2186  2186 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:44:29.014  2186  2186 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 13:44:29.016  2186  2186 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 13:44:29.017  2186  2186 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 13:44:29.017  2186  2186 V MediaPlayer[Native]: reset
08-29 13:44:29.034  2186  2186 V MediaPlayer[Native]: setListener
08-29 13:44:29.034  2186  2186 V MediaPlayer[Native]: disconnect
08-29 13:44:29.034  2186  2186 V MediaPlayer[Native]: destructor
08-29 13:44:29.034   315  2185 V AudioFlinger: releasing 18 from 2186 for -1
08-29 13:44:29.034   315  2185 V AudioFlinger:  decremented refcount to 0
08-29 13:44:29.034   315  2185 V AudioFlinger: purging stale effects
08-29 13:44:29.035  2186  2186 V MediaPlayer[Native]: disconnect
08-29 13:44:29.038  2186  2186 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 13:44:29.039  2186  2186 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 13:44:29.039  2186  2186 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 13:44:29.040  2186  2186 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 13:44:29.040  2186  2186 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 13:44:29.040  2186  2186 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 13:44:29.040  2186  2186 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 754004033
08-29 13:44:29.040  2186  2186 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 754004033
08-29 13:44:29.044  2186  2186 I SmartShareClient: [SmartShareManagerClient] terminate service: 2186/MediaPlaybackService/452969228
08-29 13:44:29.046  2186  2186 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 13:44:29.046  2186  2186 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@32ab89e6
08-29 13:44:29.047  2186  2186 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 13:44:29.048  2186  2186 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 13:44:29.048  2186  2186 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 13:44:29.048  2186  2186 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 13:44:29.049  2186  2186 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 30000
08-29 13:44:29.050  1033  1049 I ActivityManager: Killing 5332:com.lge.clock/u0a10 (adj 15): empty #17
08-29 13:44:29.141  6000  6000 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:44:29.149  1033  1939 W libprocessgroup: failed to open /acct/uid_10010/pid_5332/cgroup.procs: No such file or directory
08-29 13:44:29.153  1033  1777 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 13:44:29.184  1941  2892 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 13:44:29.188  1033  1777 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 13:44:29.190  1033  1777 D ActivityManager: setTaskToReturnTo : TaskRecord{68823e2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 13:44:29.190  1033  1777 D ActivityManager: setTaskToReturnTo : TaskRecord{68823e2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 13:44:29.191  1033  1777 D WindowStateEx: AppWindowTokenEx init.. 
08-29 13:44:29.192   339   348 E GBMv2   : DFP En is all cleared set to be enabled
08-29 13:44:29.226  1033  1777 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6023 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:44:29.228  6000  6000 D AndroidRuntime: Shutting down VM
08-29 13:44:29.313  1941  2892 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 13:44:29.313  1941  2892 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5948f2e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 13:44:29.315  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 13:44:29.317  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f752acf co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 13:44:29.370  6023  6023 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 13:44:29.440  6023  6023 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 13:44:29.447  6023  6023 I LibraryLoader: Loading: webviewchromium
08-29 13:44:29.451  6023  6023 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6958-6963)
08-29 13:44:29.452  6023  6023 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:44:29.476  6023  6023 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7b04e6a}
08-29 13:44:29.477  6023  6023 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:44:29.477  6023  6023 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:44:29.486  6023  6023 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 13:44:29.487  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:29.493  6023  6045 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-29 13:44:29.498  6023  6023 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 13:44:29.498  6023  6023 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 13:44:29.499  6023  6023 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 13:44:29.507   315  1384 V AudioPolicyService: registerClient() client 0xb1023e80, uid 10118
,08-29 13:44:29.514  6023  6023 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:44:29.514  6023  6023 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:44:29.514  6023  6023 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:44:29.514  6023  6023 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:44:29.514  6023  6023 I Adreno-EGL: Remote Branch: 
08-29 13:44:29.514  6023  6023 I Adreno-EGL: Local Patches: 
08-29 13:44:29.514  6023  6023 I Adreno-EGL: Reconstruct Branch: 
08-29 13:44:29.530  1033  1095 D BluetoothManagerService: Message: 20
08-29 13:44:29.530  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf3d15c:true
,08-29 13:44:29.605  6023  6055 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 13:44:29.608  6023  6023 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 13:44:29.626  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:44:29.631  6023  6023 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 13:44:29.634  6023  6023 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 13:44:29.638  6023  6023 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,08-29 13:44:29.638  6023  6023 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 13:44:29.652  6023  6023 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-29 13:44:29.658  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:29.658  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:44:29.682  6023  6067 D OpenGLRenderer: Render dirty regions requested: true
08-29 13:44:29.682  6023  6067 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 13:44:29.689  6023  6067 D OpenGLRenderer: Enabling debug mode 0
08-29 13:44:29.699  6023  6023 D Atlas   : Validating map...
,08-29 13:44:29.703  1033  2032 D SplitWindow: check instance of lgWin Window{3cd139b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 13:44:29.734  6023  6065 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:29.734  6023  6065 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:44:29.823  6023  6023 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cf13041 time:107334
,08-29 13:44:29.825  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms (total +631ms)
08-29 13:44:29.825  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25b25373 u0 com.test.thalitest/.MainActivity t6} time:107336
08-29 13:44:29.848  1816  4683 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-29 13:44:29.886  1816  4683 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-29 13:44:29.921  6023  6023 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:44:29.982  1816  4683 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-29 13:44:29.992  6023  6065 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 13:44:29.992  6023  6065 I chromium: 
08-29 13:44:30.138  6023  6079 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435048448
,08-29 13:44:30.154  6023  6023 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 13:44:30.154  6023  6023 I chromium: 
,08-29 13:44:30.155  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:44:30.155  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:44:30.155  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:44:30.155  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:44:30.155  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 13:44:30.156  6023  6079 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d63135 added. We now have 1 listener(s)
08-29 13:44:30.166  1033  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:44:30.170  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 13:44:30.173  5966  5966 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:30.173  5966  5966 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:30.173  6023  6079 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:44:30.176  6023  6079 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:44:30.177  6023  6079 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 13:44:30.184  6023  6079 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2678de58 added. We now have 1 listener(s)
,08-29 13:44:30.185  6023  6079 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:30.188  1033  1542 D WifiService: New client listening to asynchronous messages
08-29 13:44:30.200  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:44:30.200  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 13:44:30.200  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:44:30.200  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:44:30.200  6023  6079 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 13:44:30.203  6023  6079 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:30.203  1033  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:30.204  6023  6079 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 13:44:30.210  6023  6079 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:30.210  6023  6079 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:30.210  6023  6079 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:44:30.210  6023  6079 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:30.211  6023  6079 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:44:30.211  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:30.242  6023  6023 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:44:30.389  1033  2032 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6087 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:30.390  1033  2032 I ActivityManager: Killing 5065:com.lge.bnr/1000 (adj 15): empty #17
08-29 13:44:30.410   339   350 E GBMv2   : DFP En is all cleared set to be enabled
08-29 13:44:30.410   339   350 E GBMv2   : Set value is all cleared set the max
08-29 13:44:30.410   339   350 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 13:44:30.450  1033  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_5065/cgroup.procs: No such file or directory
,08-29 13:44:30.461  5966  5966 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-29 13:44:30.505  6087  6087 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 13:44:30.517  6087  6087 I LockScreenSettings: New app installed broadcast received ..
08-29 13:44:30.520  6087  6087 I LockScreenSettings: Number of installed packages  1
,08-29 13:44:30.565  1033  1740 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6108 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:30.587   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 374us total 22.518ms
,08-29 13:44:30.604   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 16.471ms
,08-29 13:44:30.620   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 16.320ms
,08-29 13:44:30.638  6108  6108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:44:30.945  6023  6083 W jxcore-log: Initializing JXcore engine
08-29 13:44:30.945  6023  6083 W jxcore-log: JXcore engine is ready
,08-29 13:44:30.974  6083  6083 W Thread-672: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10297]" dev="sockfs" ino=10297 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 13:44:30.974  6083  6083 W Thread-672: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 13:44:30.974  6083  6083 W Thread-672: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10483]" dev="sockfs" ino=10483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 13:44:30.974  6083  6083 W Thread-672: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 13:44:30.974  6083  6083 W Thread-672: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[28952]" dev="sockfs" ino=28952 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 13:44:30.992  6023  6083 W jxcore-log: Starting JXcore engine
08-29 13:44:31.075  6023  6083 W jxcore-log: Platform android
08-29 13:44:31.075  6023  6083 W jxcore-log: 
08-29 13:44:31.075  6023  6083 W jxcore-log: Process ARCH arm
08-29 13:44:31.075  6023  6083 W jxcore-log: 
,08-29 13:44:31.098  1033  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:44:31.132  1033  1920 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:44:31.197  6144  6144 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 13:44:31.197  6144  6144 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 13:44:31.224  1033  1048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 13:44:31.225  1033  1048 I ActivityManager: Killing 5399:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 13:44:31.271  1033  1648 I art     : Explicit concurrent mark sweep GC freed 30667(1433KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.606ms total 101.938ms
,08-29 13:44:31.299  6023  6083 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:44:31.299  6023  6083 I jxcore-log: 
08-29 13:44:31.299  6023  6083 W jxcore-log: JXcore engine is started
,08-29 13:44:31.305  6023  6079 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 13:44:31.308  6023  6023 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-29 13:44:31.319  1033  1574 W libprocessgroup: failed to open /acct/uid_10064/pid_5399/cgroup.procs: No such file or directory
,08-29 13:44:31.382  6164  6164 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 13:44:31.406  6164  6164 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 13:44:31.407  1033  1049 I ActivityManager: Killing 5214:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 13:44:31.423  5190  5190 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 13:44:31.423  5190  5190 W System.err: android.os.DeadObjectException
08-29 13:44:31.423  5190  5190 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:44:31.423  5190  5190 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:44:31.423  5190  5190 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 13:44:31.423  5190  5190 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 13:44:31.423  5190  5190 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:44:31.423  5190  5190 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:44:31.423  5190  5190 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:44:31.423  5190  5190 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:44:31.424  5190  5190 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:44:31.424  5190  5190 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:44:31.424  5190  5190 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:31.424  5190  5190 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:31.424  5190  5190 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:44:31.424  5190  5190 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:44:31.424  5190  5190 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 13:44:31.424  5190  5190 W System.err: android.os.DeadObjectException
08-29 13:44:31.424  5190  5190 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:44:31.424  5190  5190 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:44:31.424  5190  5190 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 13:44:31.424  5190  5190 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-29 13:44:31.425  5190  5190 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:44:31.425  5190  5190 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:44:31.425  5190  5190 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:44:31.425  5190  5190 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:44:31.425  5190  5190 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:44:31.425  5190  5190 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:44:31.425  5190  5190 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:31.425  5190  5190 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:31.425  5190  5190 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:44:31.425  5190  5190 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:44:31.425  5190  5190 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 13:44:31.425  5190  5190 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 13:44:31.615  1033  1049 E libprocessgroup: failed to kill 1 processes for processgroup 5214
,08-29 13:44:31.799  1033  2010 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 13:44:31.813  5190  5190 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 13:44:31.814  5190  5190 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:44:31.846  1033  1740 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6194 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:44:31.846  5190  5190 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 13:44:31.909  6194  6194 D UEI.SmartControl: Quickset Services start...
08-29 13:44:31.911  6194  6194 I UEI.SmartControl: Manufacture = LGE
08-29 13:44:31.911  6194  6194 D UEI.SmartControl: Id = LGNevo
08-29 13:44:31.912  6194  6194 D UEI.SmartControl: File observer start...
08-29 13:44:31.912  6194  6194 E UEI.SmartControl: IR Port is disabled: false
08-29 13:44:31.912  6194  6194 D UEI.SmartControl: Starting file observer...
08-29 13:44:31.913  6194  6194 D UEI.SmartControl: Extracting JNI libs...
08-29 13:44:31.913  6194  6194 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-29 13:44:31.970  6194  6194 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 13:44:31.970  6194  6194 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 13:44:31.970  6194  6194 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 13:44:31.992  6194  6194 I UEI.SmartControl: --- Selecting new region: 6
,08-29 13:44:31.993  6194  6194 I UEI.SmartControl: Model = LG-D855
08-29 13:44:31.994  6194  6194 D UEI.SmartControl: QS Service created
08-29 13:44:32.004  6194  6194 I UEI.SmartControl: Service initServices...
08-29 13:44:32.006  6194  6194 D UEI.SmartControl: QS start get config
,08-29 13:44:32.038  6194  6194 D UEI.SmartControl: Loading JNI Libs...
,08-29 13:44:32.254  6194  6194 I UEI.SmartControl: Supports setup maps: true
,08-29 13:44:32.257  6194  6194 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 13:44:32.257  6194  6194 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 13:44:32.257  6194  6194 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 13:44:32.257  6194  6194 I UEI.SmartControl: ### init IR Blaster...
08-29 13:44:32.262  6194  6194 D serial_port: Configuring serial port
08-29 13:44:32.266  6194  6194 E UEI.SmartControl: UEIBLaster setting for 616
08-29 13:44:32.266  6194  6194 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 13:44:32.266  6194  6194 I UEI.SmartControl: configuring settings for MAXQ616
08-29 13:44:32.266  6194  6194 I UEI.SmartControl: Get version...
,08-29 13:44:32.283  6194  6217 D UEI.SmartControl: serial port data available: 21
,08-29 13:44:32.314  6194  6194 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 13:44:32.314  6194  6194 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 13:44:32.314  6194  6194 I UEI.SmartControl: QS saving settings...
,08-29 13:44:32.318  6194  6194 D UEI.SmartControl: IR Blaster version: 25672567
08-29 13:44:32.335  6194  6217 D UEI.SmartControl: serial port data available: 4
,08-29 13:44:32.380  6194  6223 I UEI.SmartControl: Device manager: loading config....
08-29 13:44:32.381  6194  6223 D UEI.SmartControl: ----------- loading internal config...
,08-29 13:44:32.386  6194  6194 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 13:44:32.388  6194  6194 E UEI.SmartControl: Services init done
08-29 13:44:32.388  6194  6194 D UEI.SmartControl: QS Service init finished
08-29 13:44:32.390  6194  6194 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 13:44:32.390  6194  6194 D UEI.SmartControl: QS Service version code: 201091
08-29 13:44:32.391  6194  6194 D UEI.SmartControl: Service requested: Control
08-29 13:44:32.394  6194  6223 E UEI.SmartControl: Loading SETTINGS...
08-29 13:44:32.396  6194  6194 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 13:44:32.399  5190  5190 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 13:44:32.400  1033  2032 I ActivityManager: Killing 5190:com.lge.qremote/u0a112 (adj 15): empty #17
,08-29 13:44:32.403  6194  6209 I UEI.SmartControl: ------ IControl API: 11
08-29 13:44:32.404  6194  6209 I UEI.SmartControl: Registering callback...
08-29 13:44:32.426  6194  6223 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 13:44:32.443  6194  6222 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 13:44:32.443  6194  6222 D UEI.SmartControl: -----service ready thread exits
,08-29 13:44:32.499  1033  1776 W libprocessgroup: failed to open /acct/uid_10112/pid_5190/cgroup.procs: No such file or directory
,08-29 13:44:32.502  6194  6194 D UEI.SmartControl: Internal service binding...
08-29 13:44:34.292  5966  5966 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 13:44:34.296  1033  1049 I ActivityManager: Killing 5440:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 13:44:34.439  1033  2010 W libprocessgroup: failed to open /acct/uid_10072/pid_5440/cgroup.procs: No such file or directory
,08-29 13:44:35.234  5966  6082 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 13:44:36.089  1033  2010 I ActivityManager: Killing 5114:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 13:44:36.189  1033  2032 W libprocessgroup: failed to open /acct/uid_10013/pid_5114/cgroup.procs: No such file or directory
,08-29 13:44:37.378  6194  6224 D UEI.SmartControl: Internal timer expired: 1
,08-29 13:44:37.379  6194  6224 D UEI.SmartControl: unbind internal service
,08-29 13:44:37.391  6194  6194 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 13:44:37.392  6194  6194 D UEI.SmartControl: Service.onDestroy
08-29 13:44:37.392  6194  6194 D UEI.SmartControl: Lock is in USE false
08-29 13:44:37.392  6194  6194 D UEI.SmartControl: unbind internal service
08-29 13:44:37.392  6194  6194 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@327ce736
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 13:44:37.393  6194  6194 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 13:44:37.393  6194  6194 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:44:37.393  6194  6194 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:44:37.393  6194  6194 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:37.393  6194  6194 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:37.393  6194  6194 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:44:37.393  6194  6194 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:44:37.393  6194  6194 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@327ce736
08-29 13:44:37.396  6194  6218 D serial_port: close(fd = 25)
,08-29 13:44:37.403  6194  6218 I UEI.SmartControl: Serial port is closed.
,08-29 13:44:37.403  6194  6194 I UEI.SmartControl: Serial port is closed.
,08-29 13:44:37.403  6194  6194 I UEI.SmartControl: Serial port is closed.
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: Blaster closed
,08-29 13:44:37.404  6194  6194 D UEI.SmartControl: Shut down QS...
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: Stopping QS lib
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: QS lib stop result = true
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: Stopped QS lib
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: Stopped file observer...
08-29 13:44:37.404  6194  6194 D UEI.SmartControl: QS shutdown complete
08-29 13:44:39.051  2186  2186 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19998
,08-29 13:44:41.389  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 13:44:41.389  6023  6083 I jxcore-log: 
,08-29 13:44:41.392  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 13:44:41.392  6023  6083 I jxcore-log: 
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:41.396  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:41.399  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:41.401  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:44:41.401  6023  6083 I jxcore-log: 
08-29 13:44:41.403  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:44:41.403  6023  6083 I jxcore-log: 
,08-29 13:44:41.424  1033  1091 I ActivityManager: Waited long enough for: ServiceRecord{15f9bcbe u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 13:44:41.905  6023  6083 D executeNativeTests: Running unit tests
,08-29 13:44:41.987  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:44:41.988  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f added. We now have 2 listener(s)
,08-29 13:44:41.988  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:41.990  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:44:41.990  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:44:41.990  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:44:41.990  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:41.990  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c added. We now have 2 listener(s)
08-29 13:44:41.990  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:41.991  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:44:41.993  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:41.994  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:41.995  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:41.995  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:41.996  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.001  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:44:42.003  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:42.003  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:42.006  6023  6083 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 13:44:42.007  6023  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:42.007  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:42.008  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:42.008  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:42.009  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.010  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.010  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.011  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.011  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.011  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.011  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:44:42.011  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f removed from the list
08-29 13:44:42.011  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.012  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c removed from the list
08-29 13:44:42.012  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.012  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.012  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.012  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.013  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.013  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.013  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.013  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.015  6023  6083 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 13:44:42.015  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.015  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.015  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.015  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.015  6023  6083 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.015  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.015  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.015  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.015  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.015  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.015  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.015  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.015  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.015  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.016  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.016  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:42.016  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.016  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:44:42.020  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:231,0:2310:2310]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:44:42.021  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:42.021  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.021  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.021  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.022  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:42.022  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.022  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.022  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.022  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.022  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.022  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:42.022  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.022  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.022  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.022  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.023  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.023  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:42.023  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.023  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.024  6023  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:42.025  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.026  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.027  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:42.027  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:42.028  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.028  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:42.028  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:42.029  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:42.029  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.029  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:42.031  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:44:42.031  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:42.035  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:44:42.038  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:44:42.039  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 13:44:42.040  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:42.040  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.041  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:44:42.041  6023  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:44:42.043  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.043  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.043  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:42.043  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.043  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.043  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.043  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.043  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.043  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.043  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.043  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.044  6023  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:42.045  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.046  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.047  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.047  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:42.047  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:42.047  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:42.047  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:42.047  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.047  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:42.049  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.050  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:42.050  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.051  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:44:42.051  6023  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:44:42.052  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activitie,s and killing connections
08-29 13:44:42.052  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.052  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.052  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.052  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.052  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.053  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.053  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.053  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.053  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.053  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.053  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.053  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.053  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.053  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.054  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.054  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.054  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.054  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.055  6023  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:42.056  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.057  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.058  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.058  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:42.059  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.059  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:42.059  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:42.059  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:42.059  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.059  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:42.062  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:42.062  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.063  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:44:42.063  6023  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:44:42.063  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.063  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.063  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.064  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.064  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.064  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.064  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.064  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.064  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:42.064  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.064  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.064  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.064  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.064  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.065  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.065  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.065  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.065  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.065  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.065  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.065  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.065  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.066  6023  6083 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:44:42.066  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.066  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.066  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.066  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.066  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.066  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.066  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.066  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.066  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.066  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.066  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.066  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.066  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.067  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.067  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.067  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.068  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.068  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.068  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.068  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.068  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:42.069  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.069  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.069  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.069  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.069  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.069  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.069  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.069  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.069  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.069  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.069  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.069  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.069  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.069  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.070  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.070  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.070  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.070  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.070  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.070  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.071  6023  6083 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 13:44:42.071  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.071  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.071  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.071  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.071  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.071  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.071  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.071  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.071  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.071  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.071  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.071  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.071  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.071  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.072  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.072  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.072  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.072  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.072  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.072  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.073  6023  6083 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 13:44:42.073  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.073  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.073  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.073  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.073  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.073  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.073  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.073  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.073  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.073  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.073  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.073  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.073  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.073  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.074  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.074  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.074  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.074  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.074  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.074  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.075  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:44:42.075  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:42.075  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:42.075  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:42.075  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:44:42.075  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:42.075  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.075  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.075  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.076  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.076  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.076  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.076  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.076  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:42.076  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.076  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.076  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.076  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.076  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.076  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.076  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.076  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.077  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.077  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.077  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.077  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.077  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:42.078  6023  6083 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:42.078  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:42.079  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:42.079  6023  6083 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:42.079  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:44:42.080  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:42.080  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:44:42.080  6023  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:42.080  6023  6083 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:44:42.080  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:42.080  6023  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:42.080  6023  6083 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:44:42.080  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:42.080  6023  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:42.081  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:42.082  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 13:44:42.083  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:44:42.083  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 13:44:42.083  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:44:42.083  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 13:44:42.084  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:44:42.084  6023  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:42.084  6023  6083 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 13:44:42.084  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.084  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.084  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.089  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.089  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.089  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.089  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:44:42.090  6023  6228 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 736)
08-29 13:44:42.090  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.090  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.090  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.090  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.090  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.090  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.090  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.090  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.091  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.091  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.091  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.091  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.091  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.091  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.092  6023  6083 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:44:42.092  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.092  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.092  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.096  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.096  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.096  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.096  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.096  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.096  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.096  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.096  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.096  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.096  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.096  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.097  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.097  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.097  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.097  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.097  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.097  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.098  6023  6083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:44:42.099  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.099  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.099  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.100  6023  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 736
08-29 13:44:42.100  6023  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 736)
08-29 13:44:42.100  6023  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 736)
08-29 13:44:42.101  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.101  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.101  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.101  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.101  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.101  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.101  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.101  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.101  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.101  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.101  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.104  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.104  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.104  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.104  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.104  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.104  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.105  6023  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:44:42.105  6023  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:44:42.105  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:42.105  6023  6083 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:44:42.105  6023  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:44:42.105  6023  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:44:42.105  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:42.105  6023  6083 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:44:42.105  6023  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:44:42.106  6023  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:42.106  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:42.106  6023  6083 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:44:42.106  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.106  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.106  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.107  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.107  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.108  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.108  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.108  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.108  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.108  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.108  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.108  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.108  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.108  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.109  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.109  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.109  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.109  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.109  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.109  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.110  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.110  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.110  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.110  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.110  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.110  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.110  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.110  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.110  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.110  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.110  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.111  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.111  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.111  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.111  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.111  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.111  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.111  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.111  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.111  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.111  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.111  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.111  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.111  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.111  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.111  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.111  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.111  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.111  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.117  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.117  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.119  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.119  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.119  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.119  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.120  6023  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:44:42.120  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.121  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:44:42.121  6023  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:44:42.121  6023  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 13:44:42.122  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:44:42.122  6023  6023 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:44:42.122  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:42.129  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.129  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:44:42.129  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:44:42.129  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:44:42.129  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.129  6023  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:44:42.129  6023  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:44:42.129  6023  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:44:42.130  6023  6023 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:44:42.130  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.130  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.130  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:44:42.130  6023  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 13:44:42.130  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:42.131  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:42.131  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:44:42.131  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:42.131  6023  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:44:42.131  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.131  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.132  6023  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:42.134  6023  6023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:42.134  6023  6023 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 13:44:42.134  6023  6023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:42.134  6023  6023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:42.134  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.134  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.134  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.134  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.134  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.134  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.134  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.134  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.134  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.134  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.134  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.134  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.134  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.134  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.134  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.135  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.135  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.135  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.135  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.135  6023  6083 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:44:42.136  6023  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:42.136  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:42.137  6023  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:42.137  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.137  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.137  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.137  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.137  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.137  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.137  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.137  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.137  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.137  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.137  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.137  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.137  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.137  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.138  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.138  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.138  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.138  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.139  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:42.139  1033  1777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:42.140  1033  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:42.140  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.140  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.140  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.140  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.140  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.140  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.140  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.140  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.141  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.141  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.141  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.141  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.141  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.141  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.141  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.141  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.141  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.141  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.142  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:42.142  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:42.142  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:42.142  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:42.142  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.142  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.143  6023  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed3392f not in the list
08-29 13:44:42.143  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.143  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.143  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:42.143  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.143  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.143  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:42.143  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:42.143  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:42.143  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:42.143  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:42.143  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b5db3c not in the list
08-29 13:44:42.144  6023  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:44:42.144  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:42.144  6023  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:44:42.144  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:42.144  6023  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:44:42.144  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:42.146  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:42.146  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:44:42.146  6023  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:44:42.146  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:42.146  6023  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 13:44:42.146  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:42.146  6023  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:44:42.146  6023  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:44:42.147  6023  6083 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:44:42.150  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:42.150  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2107537d added. We now have 2 listener(s)
08-29 13:44:42.150  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:42.152  6023  6083 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 13:44:42.153  1033  1940 D WifiServiceImplEx: setWifiEnabled: true pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:44:42.154  1033  1940 D WifiService: setWifiEnabled: true pid=6023, uid=10118
08-29 13:44:42.154  1033  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:44:42.155  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:42.155  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b3cd272 added. We now have 3 listener(s)
08-29 13:44:42.155  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:42.157  6023  6228 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 13:44:42.157  6023  6228 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 736)
08-29 13:44:42.159  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:42.159  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173086c3 added. We now have 4 listener(s)
08-29 13:44:42.159  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:42.160  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:42.160  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@268afb40 added. We now have 5 listener(s)
08-29 13:44:42.160  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:42.162  1033  2032 D WifiServiceImplEx: setWifiEnabled: false pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:44:42.162  1033  2032 D WifiService: setWifiEnabled: false pid=6023, uid=10118
08-29 13:44:42.162  1033  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:44:42.171  1033  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:42.171  1033  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25f7b0b4 mBinding = false
08-29 13:44:42.172  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 13:44:42.172  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:42.172  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 13:44:42.172  1033  1537 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:42.173  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:42.173  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:42.173  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:42.173  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:44:42.173  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:42.174  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-29 13:44:42.174  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:42.174  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@306f9118
08-29 13:44:42.174  1033  1536 D LGWifiP2pService: P2pDisablingState
08-29 13:44:42.175  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:44:42.175  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 13:44:42.175  1941  2282 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 13:44:42.175  1941  2282 D WfdsService: Set the WFDS Monitor: false
08-29 13:44:42.175  1033  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:42.175  1033  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:42.175  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:42.175  1033  1536 D LGWifiP2pService: p2p socket connection lost
08-29 13:44:42.175  1033  1536 D LGWifiP2pService: P2pDisabledState
08-29 13:44:42.176  1941  2282 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:44:42.176  1941  2282 D WfdsService: STATE : WfdsDisabledState - enter
08-29 13:44:42.177  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 13:44:42.177  1941  2856 D CtrlSupplicant: Received on exit socket, terminate
08-29 13:44:42.177  1941  2856 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 13:44:42.177  1941  2856 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 13:44:42.177  1941  2856 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 13:44:42.177  1033  1095 D BluetoothManagerService: Message: 2
08-29 13:44:42.178  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:44:42.178  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:42.178  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 13:44:42.178  1941  2282 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 13:44:42.178  1941  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 13:44:42.178  1033  1095 D BluetoothManagerService: Sending off request.
08-29 13:44:42.178   310   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:42.178  3831  3944 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 13:44:42.179  3831  3906 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 13:44:42.179  3831  3906 D BluetoothAdapterProperties: Setting sta,te to 13
08-29 13:44:42.179  3831  3906 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:44:42.179  3831  3906 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:44:42.179  3831  3906 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 13:44:42.180  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:42.180  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:42.180  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 13:44:42.181  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 13:44:42.182  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:44:42.182  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:42.184  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.184  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.184  3831  3831 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.184  3831  3831 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:44:42.184  3831  3831 V BtOppService: Receiver DISABLED_ACTION 
08-29 13:44:42.184  3831  3831 V BluetoothMapService: Handler(): got msg=4
08-29 13:44:42.184  3831  3831 D BluetoothMapService: MAP Service closeService in
08-29 13:44:42.184  3831  3831 D BluetoothMapMasInstance: MAP Service shutdown
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 13:44:42.185  3831  4153 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 13:44:42.185  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:44:42.185  3831  3831 V BluetoothMapService: MAP Service closeService out
08-29 13:44:42.186  3831  3831 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:42.186  3831  3831 V BtOppRfcommListener: close mBtServerSocket
08-29 13:44:42.186  3831  3831 V BtOppRfcommListener: waiting for thread to terminate
08-29 13:44:42.186  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.186  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.186  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:42.186  3831  4191 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:42.187  3831  4191 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:44:42.187  3831  3831 V BtOppRfcommListener: done waiting for thread to terminate
08-29 13:44:42.188  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42,.189  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.189  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.189  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.189  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.190  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.212  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6238 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:44:42.213  3831  3909 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:42.214  3831  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 13:44:42.214  3831  3831 V BtOppService: onDestroy
08-29 13:44:42.214  3831  3906 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:44:42.215  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 13:44:42.215  3831  4194 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:42.216  3831  4017 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 13:44:42.216  3831  4192 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:42.216  3831  4154 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 13:44:42.217  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 13:44:42.217  3831  4017 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:44:42.218  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 13:44:42.218  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:42.218  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:42.218  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:42.221  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.222  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.222  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 13:44:42.223  3831  3831 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-29 13:44:42.224  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 13:44:42.224  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
08-29 13:44:42.224  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:42.224  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:42.224  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:42.226  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:42.226  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:42.226  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:42.228  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-29 13:44:42.230  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 13:44:42.230  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:42.230  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 13:44:42.231  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.231  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.231  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.231  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.232  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:42.232  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:42.233  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:42.233  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:42.234  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:42.238  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:44:42.238  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:42.239  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:42.250  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecifie,d), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:44:42.250  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:42.250  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:44:42.251  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:42.269  1033  1574 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:44:42.291  6238  6238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:42.291  6238  6238 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 13:44:42.291  6238  6238 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:44:42.291  6238  6238 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 13:44:42.292  6238  6238 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:44:42.293  6238  6238 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:44:42.309  2736  2736 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 13:44:42.309  2736  2736 I wpa_supplicant: monitor socket send errors count : 1
08-29 13:44:42.309  2736  2736 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,08-29 13:44:42.311  1033  2841 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 13:44:42.311  1033  2841 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 13:44:42.337  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 13:44:42.341  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:42.341  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:42.342  1033  1939 I ActivityManager: Killing 4841:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 13:44:42.378  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 13:44:42.384  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:42.385  1033  2841 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 13:44:42.385  1033  2841 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:42.385  1033  2841 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:42.385  2736  2736 W wpa_supplicant: USIM:  scard_deinit function
08-29 13:44:42.386  1033  2841 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 13:44:42.386  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 13:44:42.387  1033  2841 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:44:42.387  1033  2841 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:44:42.387  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119884
08-29 13:44:42.387  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119884
08-29 13:44:42.387  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=119885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:44:42.388  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=119885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:44:42.392  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:42.392  1033  1940 W libprocessgroup: failed to open /acct/uid_10014/pid_4841/cgroup.procs: No such file or directory
,08-29 13:44:42.398  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:42.398   310  6281 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:44:42.399  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:44:42.399  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:42.400  3831  3831 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:44:42.400  3831  3831 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.400  3831  3831 V BluetoothPbapReceiver: ***********state = 13
08-29 13:44:42.401  3831  3831 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 13:44:42.401  3831  3831 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.401  3831  3831 V BluetoothPbapService: state: 13
08-29 13:44:42.401  3831  3831 V BluetoothPbapService: Pbap Service closeService in
08-29 13:44:42.403  3831  3831 V BluetoothPbapService: successfully stopped pbap service
08-29 13:44:42.403  3831  3831 V BluetoothPbapService: Pbap Service closeService out
08-29 13:44:42.403  3831  3831 V BluetoothPbapService: Pbap Service onDestroy
08-29 13:44:42.403  3831  3831 V BluetoothPbapService: Pbap Service closeService in
08-29 13:44:42.403  3831  3831 V BluetoothPbapService: Pbap Service closeService out
08-29 13:44:42.403  3831  3831 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 13:44:42.404  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:42.405  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:42.453  6238  6238 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:42.453  6238  6238 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:44:42.465  1033  1777 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6284 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:42.470  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:42.479  1033  1095 D BluetoothManagerService: Message: 20
08-29 13:44:42.479  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13c7279e:true
,08-29 13:44:42.485  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 13:44:42.485  1033  2841 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 13:44:42.485  1033  2841 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 13:44:42.485  1033  2841 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-29 13:44:42.486  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-29 13:44:42.495  1033  1095 D BluetoothManagerService: Message: 30
,08-29 13:44:42.501  1033  1095 D BluetoothManagerService: Message: 30
08-29 13:44:42.504  6238  6238 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 13:44:42.505  6238  6238 D BluetoothMap: Create BluetoothMap proxy object
08-29 13:44:42.506  1033  1095 D BluetoothManagerService: Message: 30
,08-29 13:44:42.522  1033  1095 D BluetoothManagerService: Message: 30
,08-29 13:44:42.529  6238  6238 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 13:44:42.532  6238  6238 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 13:44:42.563  6238  6238 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 13:44:42.568  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 13:44:42.582  6238  6238 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:42.588  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 13:44:42.588  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:42.588  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:42.588  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:42.589  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 13:44:42.590  1941  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 13:44:42.590  1941  2282 D WfdsService: Set the WFDS Monitor: false
08-29 13:44:42.590  1941  2282 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:44:42.590  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:44:42.591  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:42.594  2464  2464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:42.596  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 13:44:42.597  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 13:44:42.597  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 13:44:42.597  6284  6284 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 13:44:42.597  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.597  6284  6284 W LG Account v2.2: No ProfileInfo entries
08-29 13:44:42.598  6284  6284 I LG Account v2.2: isEnabled: false
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]Country: EU
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]Operator: OPEN
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]Ranking support: false
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]Comfort support: false
08-29 13:44:42.598  6284  6284 I Feature : [Lifetracker]Accessory: true
08-29 13:44:42.599  6284  6284 I Feature : [Lifetracker]Health device: true
08-29 13:44:42.599  6284  6284 I Feature : [Lifetracker]Extra Pedometer: false
08-29 13:44:42.599  6284  6284 I Feature : [Lifetracker]Blood glucose device: false
08-29 13:44:42.599  6284  6284 I Feature : [Lifetracker]Device Number: 3
08-29 13:44:42.599  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:42.601  6238  6238 D BluetoothInputDevice: Proxy object connected
08-29 13:44:42.602  6238  6238 D HidProfile: Bluetooth service connected
08-29 13:44:42.602  6238  6238 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:44:42.603  6238  6238 D PanProfile: Bluetooth service connected
08-29 13:44:42.603  1033  1938 I ActivityManager: Killing 5645:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 13:44:42.604  6238  6238 D BluetoothMap: Proxy object connected
08-29 13:44:42.604  6238  6238 D MapProfile: Bluetooth service connected
08-29 13:44:42.605  6238  6238 D BluetoothMap: getConnectedDevices()
08-29 13:44:42.605  6238  6238 D BluetoothMap: Bluetooth is Not enabled
08-29 13:44:42.606  6238  6238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 13:44:42.633  6023  6023 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:44:42.641  1033  1048 W libprocessgroup: failed to open /acct/uid_10004/pid_5645/cgroup.procs: No such file or directory
08-29 13:44:42.648  6238  6238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 13:44:42.652  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:44:42.654  6238  6238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 13:44:42.664  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 13:44:42.666  1033  2010 I ActivityManager: Killing 5772:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 13:44:42.773  3831  3831 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 13:44:42.773  3831  3831 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-29 13:44:42.775  3831  3831 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 13:44:42.776  1033  1776 W libprocessgroup: failed to open /acct/uid_10008/pid_5772/cgroup.procs: No such file or directory
08-29 13:44:42.868  1033  2010 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6310 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 13:44:42.873  3831  3831 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:42.873  3831  3831 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:44:42.875  3831  3831 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:44:42.875  3831  3831 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.875  3831  3831 V BluetoothFtpService: Ftp Service closeService
,08-29 13:44:42.875  3831  3831 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 13:44:42.878  3831  3831 V BluetoothFtpService: successfully stopped ftp service
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 13:44:42.878  3831  3831 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:44:42.880  3831  3831 V BluetoothFtpService: Ftp Service onDestroy
08-29 13:44:42.880  3831  3831 V BluetoothFtpService: Ftp Service closeService
08-29 13:44:42.941  1033  1975 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6327 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:44:42.942  3831  3831 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:42.942  3831  3831 V BluetoothSapService: state: 13
08-29 13:44:42.942  3831  3831 V BluetoothSapService: Stopping SAP server process
08-29 13:44:42.944  3831  3831 V BluetoothSapService: Sap Service closeSapService in
08-29 13:44:42.944  3831  3831 V BluetoothSapService: Close listen Socket : 
08-29 13:44:42.944  3831  3831 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:44:42.944  3831  3831 V BluetoothSapService: Close sapd  Socket : 
,08-29 13:44:42.955  3831  3831 V BluetoothSapService: Sap Service closeSapService out
08-29 13:44:42.955  3831  3831 V BluetoothSapService: Sap Service onDestroy
08-29 13:44:42.955  3831  3831 V BluetoothSapService: Sap Service closeSapService in
08-29 13:44:42.955  3831  3831 V BluetoothSapService: Close listen Socket : 
08-29 13:44:42.956  3831  3831 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:44:42.956  3831  3831 V BluetoothSapService: Close sapd  Socket : 
08-29 13:44:42.957  3831  3831 V BluetoothSapService: Sap Service closeSapService out
,08-29 13:44:42.977  6310  6310 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:44:43.006  6310  6310 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 13:44:43.045  6310  6310 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 13:44:43.045  6310  6310 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-29 13:44:43.046  6310  6310 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 13:44:43.046  6310  6310 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 13:44:43.046  6310  6310 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-29 13:44:43.047  6327  6327 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:44:43.049  6310  6310 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 13:44:43.055  6310  6310 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 13:44:43.062  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:44:43.066  1033  1049 I ActivityManager: Killing 5805:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 13:44:43.067  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:43.099  1033  1975 W libprocessgroup: failed to open /acct/uid_10011/pid_5805/cgroup.procs: No such file or directory
,08-29 13:44:43.103  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:44:43.105  6310  6310 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 13:44:43.109  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:43.110  6310  6310 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 13:44:43.114  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:44:43.114  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 13:44:43.115  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:43.123  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:43.131  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:43.139  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:43.139  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:44:43.142  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:44:43.209  1033  2028 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6347 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 13:44:43.220  3831  4017 W bt-btif : ag scb idx 1 not allocated
08-29 13:44:43.220  3831  3909 D bt_hci_bdroid: cleanup
08-29 13:44:43.220  3831  4017 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:43.220  3831  4126 I bt_userial_mct: exiting userial_read_thread
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:43.220  3831  4126 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:43.220  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:43.221  3831  4017 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:43.221  3831  4017 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:43.221  3831  4017 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:43.221  3831  4017 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:44:43.221  3831  4020 I bt_lpm  : LPM is already off!!!
08-29 13:44:43.221  3831  3909 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 13:44:43.221  3831  4020 I bt_vendor: hw_epilog_process
08-29 13:44:43.222  3831  3909 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 13:44:43.222  3831  3909 D bt_userial_mct: userial_close
08-29 13:44:43.222  3831  3909 E bt_userial_mct: pthread_join() FAILED result:3
08-29 13:44:43.222  3831  3909 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 13:44:43.310  3831  3909 D bt_hci_bdroid: set_power 0
08-29 13:44:43.310  3831  3909 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:44:43.310  3831  3909 I bt_vendor: bluetooth satus is on
08-29 13:44:43.311  3831  3909 I bt_vendor: bt-vendor : resetting BT status
,08-29 13:44:43.311  3831  3909 I bt_vendor: Starting hciattach daemon
08-29 13:44:43.311  3831  3909 I bt_vendor: try to set false
08-29 13:44:43.312  3831  3909 I bt_vendor: Starting hciattach daemon
08-29 13:44:43.312  3831  3909 I bt_vendor: try to set false
08-29 13:44:43.313  3831  3909 I bt_vendor: cleanup
08-29 13:44:43.314  3831  4017 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 13:44:43.315  3831  3909 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:44:43.315  3831  3909 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 13:44:43.316  3831  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 13:44:43.321  3831  3831 D HeadsetService: Received stop request...Stopping profile...
08-29 13:44:43.323  3831  3831 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:44:43.323  3831  3831 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:43.323  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
,08-29 13:44:43.325  3831  3939 D HeadsetStateMachine: Exit Disconnected: -1
08-29 13:44:43.326  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:43.327  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 13:44:43.329  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:43.329  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:43.329  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:43.332  3831  3831 D A2dpService: Received stop request...Stopping profile...
08-29 13:44:43.333  3831  3997 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:44:43.334  3831  3831 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 13:44:43.338  3831  3906 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 13:44:43.339  3831  3831 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 13:44:43.339  3831  3831 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:43.339  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.340  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:43.340  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 13:44:43.343  3831  3831 D HidService: Received stop request...Stopping profile...
08-29 13:44:43.343  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.344  6238  6238 D BluetoothInputDevice: Proxy object disconnected
08-29 13:44:43.344  6238  6238 D HidProfile: Bluetooth service disconnected
08-29 13:44:43.345  3831  3831 D HealthService: Received stop request...Stopping profile...
,08-29 13:44:43.345  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.348  3831  3831 D HeadsetStateMachine: Unbinding service...
08-29 13:44:43.350  3831  3831 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:44:43.350  3831  3831 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:44:43.350  3831  3831 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:44:43.350  3831  3831 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:44:43.350  3831  3831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:43.350  3831  3831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:43.350  3831  3831 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:44:43.351  3831  3831 D PanService: Received stop request...Stopping profile...
08-29 13:44:43.352  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:43.354  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.357  3831  3831 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:44:43.358  3831  3831 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:44:43.358  3831  3831 D BtGatt.GattService: stop()
08-29 13:44:43.358  3831  3831 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 13:44:43.359  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:43.360  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.361  3831  3831 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:44:43.361  3831  3831 D BluetoothMapService: stop()
08-29 13:44:43.362  3831  3831 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 13:44:43.362  3831  3831 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 13:44:43.362  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df1df5b
08-29 13:44:43.364  3831  3831 I BluetoothA2dpServiceJni: cleanupNative
08-29 13:44:43.364  3831  4000 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 13:44:43.366  3831  3831 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:44:43.366  3831  3831 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 13:44:43.366  3831  3831 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:44:43.366  3831  3831 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:44:43.367  3831  3831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:44:43.367  3831  3831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:43.367  3831  3831 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:43.367  3831  3831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:43.367  3831  3831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:44:43.369  3831  3831 V BluetoothMapService: Handler(): got msg=4
08-29 13:44:43.369  3831  3831 D BluetoothMapService: MAP Service closeService in
08-29 13:44:43.369  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:44:43.369  3831  3831 V BluetoothMapService: MAP Service closeService out
08-29 13:44:43.369  3831  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:44:43.370  3831  3906 D BluetoothAdapterProperties: Setting state to 10
08-29 13:44:43.370  3831  3906 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:44:43.370  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:43.370  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 13:44:43.370  3831  3906 I BluetoothAdapterState: Entering OffState
08-29 13:44:43.370  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 13:44:43.370  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:43.370  3831  3831 D BluetoothMapService: cleanup()
08-29 13:44:43.370  3831  3831 D BluetoothMapService: MAP Service closeService in
08-29 13:44:43.371  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:44:43.371  3831  3831 V BluetoothMapService: MAP Service closeService out
08-29 13:44:43.371  6238  6255 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:44:43.372  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:43.372  6238  6254 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:44:43.373  1852  4373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:43.374  6238  6255 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:44:43.375  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:43.375  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:43.377  6238  6255 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 13:44:43.381  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:43.382  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 13:44:43.382  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 13:44:43.384  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 13:44:43.384  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 13:44:43.384  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25f7b0b4 mBinding = false
08-29 13:44:43.390  1033  1095 D BluetoothManagerService: Sending unbind request.
,08-29 13:44:43.393  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 13:44:43.397  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:44:43.401  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:43.401  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:44:43.401  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:44:43.402  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:44:43.403  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 13:44:43.403  1601  1601 D BluetoothAdapter: 290912578: getState() :  mService = null. Returning STATE_OFF
08-29 13:44:43.403  1601  1601 D BluetoothAdapter: 290912578: getState() :  mService = null. Returning STATE_OFF
08-29 13:44:43.405  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:43.406  1941  2099 D LGBluetoothAPIService: Message: 2
08-29 13:44:43.406  1941  2099 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@33087c5c mBinding = false
08-29 13:44:43.406  1941  2099 D LGBluetoothAPIService: Sending unbind request.
08-29 13:44:43.408  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:43.410  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:43.418  3831  3909 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 13:44:43.422  3831  3831 I GKI_LINUX: GKI_exit_task 1 done
,08-29 13:44:43.422  3831  3831 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 13:44:43.423  3831  3831 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 13:44:43.423  1033  1377 V AlarmManager: RTC_WAKEUP set : Alarm{35f41303 type 0 when 1472471083295 com.android.vending} when 1472471083295
08-29 13:44:43.423  3831  3831 I art     : --- WEIRD: removing null entry 246
08-29 13:44:43.423  3831  3831 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 13:44:43.423  3831  3831 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 13:44:43.425  3831  3831 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 13:44:43.428  3831  3831 I art     : System.exit called, status: 0
08-29 13:44:43.428  3831  3831 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 13:44:43.430  6347  6373 W FormManager: Network not available. Please check & try again.
08-29 13:44:43.439  6347  6378 V FormManager: Network unavailable.
08-29 13:44:43.442  6347  6378 V FormManager: Network unavailable.
,08-29 13:44:43.452   315  2185 V AudioFlinger: 3831 died, releasing its sessions
08-29 13:44:43.452   315  2185 V AudioFlinger:  pid 1852 @ 0
08-29 13:44:43.452   315  2185 V AudioFlinger:  pid 3387 @ 1
08-29 13:44:43.452   315  2185 V AudioFlinger:  pid 3387 @ 2
08-29 13:44:43.453  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:44:43.453  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:44:43.453  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:44:43.453  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:44:43.454  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:44:43.454  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:44:43.455  6238  6238 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:44:43.455  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 13:44:43.455  6238  6238 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 13:44:43.457  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:44:43.493  1033  1740 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:44:43.508  1033  1777 I ActivityManager: Process com.android.bluetooth (pid 3831) has died
,08-29 13:44:43.508  1033  1777 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-29 13:44:43.586  1033  1648 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6389 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 13:44:43.598  6238  6238 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 13:44:43.603  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 13:44:43.604  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:43.610  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:43.613  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:43.614  6238  6238 D DockEventReceiver: finishStartingService: stopping service
08-29 13:44:43.623  6256  6256 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 13:44:43.623  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:43.623  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:43.626  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:43.626  4267  6409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:44:43.632  4267  6409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:43.634  6347  6412 W FormManager: Network not available. Please check & try again.
,08-29 13:44:43.636  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:43.639  4267  6407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:44:43.645  6347  6413 V FormManager: Network unavailable.
08-29 13:44:43.656  6347  6413 V FormManager: Network unavailable.
,08-29 13:44:43.661  6310  6310 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:44:43.663  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 13:44:43.663  6310  6310 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 13:44:43.664  6389  6389 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 13:44:43.665  6389  6389 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:44:43.665  6389  6389 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 13:44:43.666  6389  6389 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 13:44:43.686  6389  6389 D BluetoothAdapterApp: Loading JNI Library
,08-29 13:44:43.703  6310  6310 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:44:43.704  6310  6310 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:43.712  6310  6310 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 13:44:43.714  6310  6310 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 13:44:43.714  6310  6310 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 13:44:43.714  6310  6310 V SoundPool: doLoad: loading sample sampleID=1
08-29 13:44:43.715  6310  6310 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:44:43.718  6310  6310 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 13:44:43.719  6310  6416 V SoundPool: Start decode
08-29 13:44:43.720  6310  6416 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 13:44:43.720  6194  6194 D UEI.SmartControl: QS Service created
08-29 13:44:43.720  6389  6389 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@ca3f8e0 Instance Count = 1
08-29 13:44:43.724   315  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 13:44:43.724   315  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 13:44:43.724   315  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 13:44:43.724   315  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 13:44:43.724   315  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 13:44:43.724   315  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 13:44:43.725   315  1383 V MediaPlayerService: player type = 3
08-29 13:44:43.725   315  1383 V AwesomePlayer: AwesomePlayer create()
08-29 13:44:43.725  6310  6310 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:44:43.725   315  1383 V AwesomePlayer: reset_l() 
08-29 13:44:43.725   315  1383 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.725   315  1383 V AwesomePlayer: setAudioSink() 
08-29 13:44:43.725   315  1383 V AwesomePlayer: reset_l() 
08-29 13:44:43.725   315  1383 V AudioCache: notify(0xb5474b80, 8, 0, 0)
08-29 13:44:43.725   315  1383 V AudioCache: ignored
08-29 13:44:43.725   315  1383 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.725  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 13:44:43.725   315  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 13:44:43.726   315  1383 V AwesomePlayer: setDataSource_l dataSource
08-29 13:44:43.726   315  1383 V LGParserOSAL: SniffLGParser start
08-29 13:44:43.726   315  1383 V LGParserOSAL: MainType:5, SubType=0
08-29 13:44:43.726   315  1383 V LGParserOSAL: #### check Mime : application/ogg
08-29 13:44:43.726   315  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 13:44:43.726   315  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 13:44:43.726  6389  6389 D BluetoothAdapterApp: onCreate
08-29 13:44:43.738  6310  6310 V LGMDMManager: Create singleton instance
,08-29 13:44:43.749  6389  6389 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 13:44:43.750  6389  6389 D ProfileConfigQcom: Adding HeadsetService
08-29 13:44:43.750  6389  6389 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 13:44:43.750  6389  6389 D ProfileConfigQcom: Adding A2dpService
08-29 13:44:43.751  6389  6389 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 13:44:43.751  6194  6194 I UEI.SmartControl: Service initServices...
08-29 13:44:43.751  6389  6389 D ProfileConfigQcom: Adding HidService
08-29 13:44:43.751  6194  6194 D UEI.SmartControl: QS start get config
08-29 13:44:43.752  6389  6389 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 13:44:43.752  6389  6389 D ProfileConfigQcom: Adding HealthService
08-29 13:44:43.752  6389  6389 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 13:44:43.753  6389  6389 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 13:44:43.753  6389  6389 D ProfileConfigQcom: Adding PanService
08-29 13:44:43.754  6389  6389 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 13:44:43.754  6389  6389 D ProfileConfigQcom: Adding GattService
08-29 13:44:43.754  6389  6389 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 13:44:43.754  6389  6389 D ProfileConfigQcom: Adding BluetoothMapService
08-29 13:44:43.754  6389  6389 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 13:44:43.755  6389  6389 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:44:43.756  6389  6389 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:43.757  6389  6389 V BluetoothPbapReceiver: ***********state = 10
08-29 13:44:43.758  6389  6389 V LGMDMManagerInternal: Create singleton instance
,08-29 13:44:43.771   315  1383 V LGParserOSAL: supported mime: application/ogg
08-29 13:44:43.771   315  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 13:44:43.771   315  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 13:44:43.771   315  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 13:44:43.771   315  1383 V AwesomePlayer: AudioTrack Setting
08-29 13:44:43.771   315  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 13:44:43.771   315  1383 V AwesomePlayer: setAudioSource() 
08-29 13:44:43.771   315  1383 V MediaPlayerService: prepare
08-29 13:44:43.771   315  1383 V AwesomePlayer: prepareAsync_l() 
08-29 13:44:43.771   315  1383 V MediaPlayerService: wait for prepare
08-29 13:44:43.771   315  6418 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 13:44:43.771   315  6418 V AwesomePlayer: initAudioDecoder() 
08-29 13:44:43.771   315  6418 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:44:43.771   315  6418 V AudioSystem: isOffloadSupported()
08-29 13:44:43.771   315  6418 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:44:43.771   315  6418 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:44:43.771   315  6418 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:44:43.771   315  6418 V AwesomePlayer: getUseOffload() = 0 
08-29 13:44:43.771   315  6418 V OMXCodec: OMXCodec::Create
08-29 13:44:43.771   315  6418 V OMXCodec: findMatchingCodecs()
08-29 13:44:43.771   315  6418 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 13:44:43.771   315  6418 V OMXCodec: matchingCodecs.size()=1
08-29 13:44:43.771   315  6418 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 13:44:43.773   315  6418 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 13:44:43.773   315  6418 V LGCodecAdapter: LG Codec Adapter start
08-29 13:44:43.773   315  6418 V OMXCodec: OMXCodec Createtor
08-29 13:44:43.773   315  6418 V OMXCodec: setComponentRole
08-29 13:44:43.773   315  6418 V OMXCodec: configureCodec protected=0
,08-29 13:44:43.773   315  6418 V LGCodecAdapter: called getLGCodecSpecificData
08-29 13:44:43.773   315  6418 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 13:44:43.773   315  6418 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 13:44:43.773   315  6418 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 13:44:43.773   315  6418 V LGCodecOSAL: Not support LGCodec
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 13:44:43.773   315  6418 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 13:44:43.773   315  6418 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 13:44:43.773   315  6418 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 13:44:43.773   315  6418 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:44:43.773   315  6418 V AudioSystem: isOffloadSupported()
08-29 13:44:43.773   315  6418 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:44:43.773   315  6418 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 13:44:43.773   315  6418 V OMXCodec: init()
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 13:44:43.773   315  6418 V OMXCodec: allocateBuffers
08-29 13:44:43.773   315  6418 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-29 13:44:43.773   315  6418 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-29 13:44:43.773   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 13:44:43.774   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-29 13:44:43.774   315  6418 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd0b0 on output port
08-29 13:44:43.774   315  6418 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 13:44:43.774   315  6418 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 13:44:43.774   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 13:44:43.774   315  6418 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 13:44:43.774   315  6418 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 13:44:43.774   315  6418 V AudioCache: notify(0xb5474b80, 5, 0, 0)
08-29 13:44:43.774   315  6418 V AudioCache: ignored
08-29 13:44,:43.774   315  6418 V AudioCache: notify(0xb5474b80, 1, 0, 0)
08-29 13:44:43.774   315  6418 V AudioCache: prepared
08-29 13:44:43.774   315  1383 V AudioCache: wait - success
08-29 13:44:43.774   315  1383 V MediaPlayerService: start
08-29 13:44:43.774   315  1383 V AwesomePlayer: play_l() 
08-29 13:44:43.774   315  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 13:44:43.774   315  1383 V AwesomePlayer: createAudioPlayer_l
08-29 13:44:43.774   315  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 13:44:43.774   315  1383 V AwesomePlayer: startAudioPlayer_l() 
08-29 13:44:43.774   315  1383 D AudioPlayer: start of Playback, useOffload 0
08-29 13:44:43.774   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 13:44:43.774   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790448
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 13:44:43.776   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 13:44:43.777   315  6420 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
,08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 13:44:43.777   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 13:44:43.778   315  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 13:44:43.778   315  1383 V AudioCache: notify(0xb5474b80, 6, 0, 0)
08-29 13:44:43.778   315  1383 V AudioCache: ignored
08-29 13:44:43.778   315  1383 V MediaPlayerService: wait for playback complete
08-29 13:44:43.779   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.779   315  6421 V AudioCache: memcpy(0xac300000, 0xb1472000, 4096)
08-29 13:44:43.780   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.780   315  6421 V AudioCache: memcpy(0xac301000, 0xb1472000, 4096)
08-29 13:44:43.780   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.780   315  6421 V AudioCache: memcpy(0xac302000, 0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: memcpy(0xac303000, 0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: memcpy(0xac304000, 0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: memcpy(0xac305000, 0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.781   315  6421 V AudioCache: memcpy(0xac306000, 0xb1472000, 4096)
,08-29 13:44:43.782   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.782   315  6421 V AudioCache: memcpy(0xac307000, 0xb1472000, 4096)
08-29 13:44:43.782   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.782   315  6421 V AudioCache: memcpy(0xac308000, 0xb1472000, 4096)
08-29 13:44:43.782   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.782   315  6421 V AudioCache: memcpy(0xac309000, 0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: memcpy(0xac30a000, 0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: memcpy(0xac30b000, 0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.783   315  6421 V AudioCache: memcpy(0xac30c000, 0xb1472000, 4096)
08-29 13:44:43.784   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.784   315  6421 V AudioCache: memcpy(0xac30d000, 0xb1472000, 4096)
,08-29 13:44:43.784   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.784   315  6421 V AudioCache: memcpy(0xac30e000, 0xb1472000, 4096)
08-29 13:44:43.784   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.784   315  6421 V AudioCache: memcpy(0xac30f000, 0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: memcpy(0xac310000, 0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: memcpy(0xac311000, 0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.785   315  6421 V AudioCache: memcpy(0xac312000, 0xb1472000, 4096)
08-29 13:44:43.786   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.786   315  6421 V AudioCache: memcpy(0xac313000, 0xb1472000, 4096)
08-29 13:44:43.786   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.786   315  6421 V AudioCache: memcpy(0xac314000, 0xb1472000, 4096)
,08-29 13:44:43.790   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: memcpy(0xac315000, 0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: memcpy(0xac316000, 0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: memcpy(0xac317000, 0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.790   315  6421 V AudioCache: memcpy(0xac318000, 0xb1472000, 4096)
08-29 13:44:43.791   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.791   315  6421 V AudioCache: memcpy(0xac319000, 0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: memcpy(0xac31a000, 0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: memcpy(0xac31b000, 0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.792   315  6421 V AudioCache: memcpy(0xac31c000, 0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: memcpy(0xac31d000, 0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: memcpy(0xac31e000, 0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: memcpy(0xac31f000, 0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.794   315  6421 V AudioCache: memcpy(0xac320000, 0xb1472000, 4096)
08-29 13:44:43.795   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.795   315  6421 V AudioCache: memcpy(0xac321000, 0xb1472000, 4096)
08-29 13:44:43.795   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.795   315  6421 V AudioCache: memcpy(0xac322000, 0xb1472000, 4096)
08-29 13:44:43.796   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.796   315  6421 V AudioCache: memcpy(0xac323000, 0xb1472000, 4096)
08-29 13:44:43.796   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.796   315  6421 V AudioCache: memcpy(0xac324000, 0xb1472000, 4096)
08-29 13:44:43.797   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.797   315  6421 V AudioCache: memcpy(0xac325000, 0xb1472000, 4096)
08-29 13:44:43.798   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.798   315  6421 V AudioCache: memcpy(0xac326000, 0xb1472000, 4096)
08-29 13:44:43.798   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.798   315  6421 V AudioCache: memcpy(0xac327000, 0xb1472000, 4096)
08-29 13:44:43.799   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.799   315  6421 V AudioCache: memcpy(0xac328000, 0xb1472000, 4096)
08-29 13:44:43.800   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.800   315  6421 V AudioCache: memcpy(0xac329000, 0xb1472000, 4096)
08-29 13:44:43.800   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.800   315  6421 V AudioCache: memcpy(0xac32a000, 0xb1472000, 4096)
08-29 13:44:43.801   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.801   315  6421 V AudioCache: memcpy(0xac32b000, 0xb1472000, 4096)
08-29 13:44:43.802   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.802   315  6421 V AudioCache: memcpy(0xac32c000, 0xb1472000, 4096)
08-29 13:44:43.802   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.802   315  6421 V AudioCache: memcpy(0xac32d000, 0xb1472000, 4096)
08-29 13:44:43.803   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.803   315  6421 V AudioCache: memcpy(0xac32e000, 0xb1472000, 4096)
08-29 13:44:43.804   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.804   315  6421 V AudioCache: memcpy(0xac32f000, 0xb1472000, 4096)
08-29 13:44:43.804   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.805   315  6421 V AudioCache: memcpy(0xac330000, 0xb1472000, 4096)
08-29 13:44:43.805   315  6421 V AudioCache: write(0xb1472000, 4096)
08-29 13:44:43.805   315  6421 V AudioCache: memcpy(0xac331000, 0xb1472000, 4096)
08-29 13:44:43.806   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 13:44:43.806   315  6421 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 13:44:43.806   315  6421 V AwesomePlayer: postAudioEOS() 
08-29 13:44:43.806   315  6421 V AudioCache: write(0xb1472000, 280)
08-29 13:44:43.806   315  6421 V AudioCache: memcpy(0xac332000, 0xb1472000, 280)
08-29 13:44:43.807  5908  5908 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-29 13:44:43.807   315  6418 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 13:44:43.807   315  6418 V AwesomePlayer: onStreamDone
08-29 13:44:43.807   315  6418 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 13:44:43.807   315  6418 V AudioCache: notify(0xb5474b80, 2, 0, 0)
08-29 13:44:43.807   315  6418 V AudioCache: playback complete
08-29 13:44:43.807   315  6418 V AwesomePlayer: pause_l() 
08-29 13:44:43.807   315  6418 V AudioCache: notify(0xb5474b80, 7, 0, 0)
08-29 13:44:43.808   315  6418 V AudioCache: ignored
08-29 13:44:43.808   315  6418 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.808   315  6418 D AudioPlayer: Pause Playback at 1068125
08-29 13:44:43.808   315  1383 V AudioCache: wait - success
08-29 13:44:43.808   315  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 13:44:43.808   315  1383 V AwesomePlayer: reset_l() 
08-29 13:44:43.808   315  1383 V AudioCache: notify(0xb5474b80, 8, 0, 0)
08-29 13:44:43.808   315  1383 V AudioCache: ignored
08-29 13:44:43.808   315  1383 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.808   315  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 13:44:43.808   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 13:44:43.808   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 13:44:43.808   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 13:44:43.808   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 13:44:43.808   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:44:43.808   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:44:43.808   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-29 13:44:43.809   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 13:44:43.810   315  6420 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 13:44:43.810   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 13:44:43.810   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 13:44:43.810   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 13:44:43.811   315  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 13:44:43.812   315  1383 D AudioPlayer: AudioPlayer releasing audio source
08-29 13:44:43.812   315  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-29 13:44:43.812   315  1383 V AwesomePlayer: reset_l() 
08-29 13:44:43.812   315  1383 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.812   315  1383 V AwesomePlayer: ~AwesomePlayer call
08-29 13:44:43.812   315  1383 V AwesomePlayer: reset_l() 
08-29 13:44:43.812   315  1383 V AwesomePlayer: cancelPlayerEvents
08-29 13:44:43.812  6310  6416 V SoundPool: close(31)
08-29 13:44:43.812  6310  6416 V SoundPool: pointer = 0x9fea6000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 13:44:43.818  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 13:44:43.822  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 13:44:43.824  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1879
08-29 13:44:43.828  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:43.829  6238  6238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 13:44:43.829  1033  1975 I ActivityManager: Killing 5823:com.android.contacts/u0a19 (adj 15): empty #17
08-29 13:44:43.842  4424  6423 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 13:44:43.980  1033  2032 W libprocessgroup: failed to open /acct/uid_10019/pid_5823/cgroup.procs: No such file or directory
,08-29 13:44:44.008  6238  6238 D BluetoothPermissionRequest: onReceive
,08-29 13:44:44.012  6238  6238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:44:44.013  6238  6238 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 13:44:44.016  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:44:44.021  6389  6389 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 13:44:44.028  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:44.032  6389  6389 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:44:44.033  6389  6389 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:44:44.033  6389  6389 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 13:44:44.035  6389  6389 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:44.036  6389  6389 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 13:44:44.044  6327  6327 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 13:44:44.140  6194  6194 I UEI.SmartControl: Supports setup maps: true
08-29 13:44:44.143  6194  6194 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 13:44:44.143  6194  6194 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 13:44:44.143  6194  6194 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 13:44:44.143  6194  6194 I UEI.SmartControl: ### init IR Blaster...
,08-29 13:44:44.147  6194  6194 D serial_port: Configuring serial port
,08-29 13:44:44.148  6194  6194 E UEI.SmartControl: UEIBLaster setting for 616
08-29 13:44:44.148  6194  6194 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 13:44:44.148  6194  6194 I UEI.SmartControl: configuring settings for MAXQ616
08-29 13:44:44.148  6194  6194 I UEI.SmartControl: Get version...
08-29 13:44:44.164  6194  6432 D UEI.SmartControl: serial port data available: 21
,08-29 13:44:44.190  6194  6194 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 13:44:44.190  6194  6194 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 13:44:44.190  6194  6194 I UEI.SmartControl: QS saving settings...
08-29 13:44:44.192  6194  6194 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 13:44:44.208  6194  6432 D UEI.SmartControl: serial port data available: 4
,08-29 13:44:44.240  6194  6435 I UEI.SmartControl: Device manager: loading config....
,08-29 13:44:44.245  6194  6194 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 13:44:44.247  6194  6435 D UEI.SmartControl: ----------- loading internal config...
08-29 13:44:44.248  6194  6194 E UEI.SmartControl: Services init done
08-29 13:44:44.248  6194  6194 D UEI.SmartControl: QS Service init finished
08-29 13:44:44.249  6194  6194 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 13:44:44.250  6194  6194 D UEI.SmartControl: QS Service version code: 201091
08-29 13:44:44.250  6194  6194 D UEI.SmartControl: Service requested: Control
08-29 13:44:44.259  6194  6435 E UEI.SmartControl: Loading SETTINGS...
,08-29 13:44:44.262  6194  6194 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 13:44:44.266  6194  6194 D UEI.SmartControl: Internal service binding...
08-29 13:44:44.266  6310  6310 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 13:44:44.268  6194  6210 I UEI.SmartControl: ------ IControl API: 11
08-29 13:44:44.268  6194  6210 D UEI.SmartControl: File observer start...
08-29 13:44:44.269  6194  6210 E UEI.SmartControl: IR Port is disabled: false
08-29 13:44:44.269  6194  6210 D UEI.SmartControl: Starting file observer...
08-29 13:44:44.269  6194  6210 I UEI.SmartControl: Registering callback...
08-29 13:44:44.270  6194  6209 I UEI.SmartControl: ------ IControl API: 19
08-29 13:44:44.271  6194  6435 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 13:44:44.273  6194  6209 I UEI.SmartControl: Registering Services Ready callback...
,08-29 13:44:44.297  6194  6434 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 13:44:44.298  6194  6434 D UEI.SmartControl: -----service ready thread exits
08-29 13:44:44.299  6310  6326 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 13:44:44.302  6310  6414 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 13:44:44.303  6310  6414 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 13:44:44.307  6310  6310 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 13:44:44.307  6310  6310 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 13:44:44.309  6194  6210 I UEI.SmartControl: ------ IControl API: 8
08-29 13:44:44.314  6310  6310 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 13:44:44.314  6310  6310 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 13:44:44.315  6310  6310 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 13:44:44.316  6310  6310 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 13:44:44.319  6310  6310 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-29 13:44:44.321  6310  6310 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 13:44:44.325  6310  6310 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 13:44:44.331  6310  6310 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:44:44.332  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 13:44:44.334  6310  6310 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:44:44.335  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 13:44:44.337  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 13:44:44.339  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 13:44:44.340  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 13:44:44.343  6310  6310 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472471084342]
08-29 13:44:44.348  6310  6310 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-29 13:44:44.354  1033  1975 I ActivityManager: Killing 5882:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 13:44:44.374  6310  6440 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 13:44:44.421  1033  1975 I ActivityManager: Killing 5849:com.lge.email/u0a23 (adj 15): empty #18
,08-29 13:44:44.480  1033  1777 W libprocessgroup: failed to open /acct/uid_10027/pid_5882/cgroup.procs: No such file or directory
,08-29 13:44:44.486  1033  1049 W libprocessgroup: failed to open /acct/uid_10023/pid_5849/cgroup.procs: No such file or directory
08-29 13:44:44.493  6310  6310 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-29 13:44:44.496  6310  6310 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:44:44.496  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 13:44:44.496  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 13:44:44.497  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 13:44:44.497  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 13:44:44.498  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 13:44:44.508  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 13:44:45.191  1033  2010 D WifiServiceImplEx: setWifiEnabled: true pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 13:44:45.193  1033  2010 D WifiService: setWifiEnabled: true pid=6023, uid=10118
08-29 13:44:45.193  1033  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:44:45.221  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:44:45.221  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:45.221  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 13:44:45.225  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 13:44:45.225  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 13:44:45.227  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 13:44:45.227  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:44:45.227  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 13:44:45.227  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:44:45.227  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 13:44:45.227  1033  1537 E WifiHW  : unknown target_country: EU , set to default
08-29 13:44:45.227  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 13:44:45.227  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 13:44:45.227  1033  1537 I WifiUtil: gEnableBmps=1
08-29 13:44:45.829   310   890 D SoftapController: Softap fwReload - Ok
,08-29 13:44:45.834  1033  1537 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (597ms)
08-29 13:44:45.848  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:45.848  1033  1095 D Tethering: InitialState.processMessage what=4
,08-29 13:44:45.854   310   890 D CommandListener: Setting iface cfg
08-29 13:44:45.854   310   890 D CommandListener: Trying to bring down wlan0
08-29 13:44:45.856   310   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:45.857   310  6455 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:44:45.865  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 13:44:45.868  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:45.870  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 13:44:45.894  6456  6456 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:44:45.905  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:45.905  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:44:45.905  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:44:45.905  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:44:45.894  6456  6456 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:45.916  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 13:44:45.928  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:44:45.928  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:44:45.929  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:44:45.929  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:44:45.929  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:44:45.929  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 13:44:45.945  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:45.946  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 13:44:45.946  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:44:45.946  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:44:45.947  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:44:45.949  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:44:45.949  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:44:45.949  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:44:45.949  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:44:45.949  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:44:45.949  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:44:45.952  6456  6456 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 13:44:45.984  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:45.984  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:45.984  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:45.984  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 13:44:45.984  1033  1537 D WifiMonitor: connecting to supplicant
08-29 13:44:45.985  6456  6456 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:44:45.985  6456  6456 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 13:44:45.991  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:45.994  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:45.995  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:45.997  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 13:44:46.000  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 13:44:46.010  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:46.014  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:46.023  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.024  6347  6472 W FormManager: Network not available. Please check & try again.
08-29 13:44:46.031  6347  6473 V FormManager: Network unavailable.
08-29 13:44:46.043  6347  6473 V FormManager: Network unavailable.
,08-29 13:44:46.047  6456  6456 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:44:46.091  6456  6456 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 13:44:46.097  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 13:44:46.099  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 13:44:46.099  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:44:46.099  1033  6475 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 13:44:46.101  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 13:44:46.102  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:44:46.103  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:44:46.104  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.105  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.106  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.107  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.109  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 13:44:46.109  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 13:44:46.109  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 13:44:46.110  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 13:44:46.110  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 13:44:46.111  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:46.111  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:46.111  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:46.111  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.112  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.112  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 13:44:46.112  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.112  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.112  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:46.113  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
,08-29 13:44:46.113  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
08-29 13:44:46.113  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 13:44:46.113  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-29 13:44:46.119  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.119  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:44:46.119  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 13:44:46.119  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:44:46.119  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 13:44:46.120  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 13:44:46.120  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:44:46.120  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:44:46.122  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 13:44:46.125  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-29 13:44:46.127  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:46.127  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:46.127  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:46.127  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:46.133  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:46.133  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:46.133  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:46.133  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:46.139  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 13:44:46.139  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 13:44:46.140  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:44:46.140  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 13:44:46.142  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-29 13:44:46.142  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 13:44:46.143  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 13:44:46.143  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 13:44:46.144  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 13:44:46.145  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 13:44:46.145  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 13:44:46.146  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 13:44:46.146  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 13:44:46.146  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 13:44:46.147  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:44:46.148  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 13:44:46.148  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 13:44:46.148  1941  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 13:44:46.148  1941  2282 D WfdsService: Set the WFDS Monitor: true
08-29 13:44:46.148  1941  2282 D WfdsMonitor: WfdsMonitorThread create
08-29 13:44:46.148  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:46.148  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 13:44:46.148  1033  1537 D WifiNative-HAL: Setting external_sim to 1
08-29 13:44:46.148  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 13:44:46.149  1941  2282 D WfdsMonitor: WFDS Monitor is created and started
08-29 13:44:46.149  1941  2282 D WfdsService: WiFi: Supplicant connection re-established
08-29 13:44:46.149  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 13:44:46.149  1033  1537 I WifiNative-HAL: startHal
08-29 13:44:46.149  1033  1537 D wifi    : setting scan oui 0x95278fe0
08-29 13:44:46.150  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:44:46.150  1033  1537 I WifiNative-HAL: startHal
08-29 13:44:46.150  1033  1537 D wifi    : setting scan oui 0x95278fe0
08-29 13:44:46.150  1941  6477 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 13:44:46.150  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 13:44:46.150  1941  6477 E CtrlSupplicant: Succeed to open control connection
08-29 13:44:46.151  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 13:44:46.151  1941  6477 E CtrlSupplicant: Succeed to open monitor connection
08-29 13:44:46.151  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 13:44:46.151  1941  6477 D WfdsMonitor: Supplicant connection established
08-29 13:44:46.151  1941  2282 D WfdsService: Connected to the supplicant for wfds
08-29 13:44:46.151  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 13:44:46.152  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 13:44:46.152  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:46.152  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:44:46.152  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:44:46.153  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:44:46.153  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 13:44:46.153  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 13:44:46.153  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 13:44:46.153  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:44:46.153  6456  6456 I wpa_supplic,ant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:44:46.154  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:44:46.154  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:44:46.154  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:44:46.154  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:44:46.154  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 13:44:46.155  6456  6456 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 13:44:46.155  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 13:44:46.155  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:44:46.155  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:44:46.156  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:44:46.156  1033  1537 E WifiNative: : [123,653,559 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 13:44:46.156  1033  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 13:44:46.157  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
08-29 13:44:46.157  1033  1537 D WifiNative-wlan0: doString: [STATUS]
08-29 13:44:46.157  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:44:46.158  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-29 13:44:46.158  1033  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:44:46.159  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:44:46.159  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:44:46.159  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.160  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:44:46.160  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:44:46.160  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-29 13:44:46.161  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 13:44:46.161  1033  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.161  1033  1555 I WifiNative-HAL: startHal
08-29 13:44:46.161  1033  1555 D wifi    : getting scan capabilities on interface[1] = 0x95278fe0
08-29 13:44:46.161  1033  1555 D wifi    : failed to get capabilities : -3
08-29 13:44:46.161  1033  1555 E WifiScanningService: could not get scan capabilities
08-29 13:44:46.161  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 13:44:46.161  1033  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.162  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 13:44:46.162  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.162  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=123659  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:44:46.163   310   890 D CommandListener: Setting iface cfg
08-29 13:44:46.163   310   890 D CommandListener: Trying to bring up p2p0
08-29 13:44:46.163  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=123661  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:44:46.163  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:44:46.163  1033  1536 D LGWifiP2pService: P2pEnablingState
08-29 13:44:46.163  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.163  1033  1536 D LGWifiP2pService: P2p socket connection successful
08-29 13:44:46.163  1033  1536 D LGWifiP2pService: P2pEnabledState
08-29 13:44:46.164  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 13:44:46.164  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 13:44:46.164  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 13:44:46.164  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 13:44:46.165  6456  6456 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 13:44:46.165  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 13:44:46.166  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 13:44:46.166  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 13:44:46.166  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 13:44:46.166  6456  6456 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 13:44:46.167  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 13:44:46.167  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 13:44:46.168  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 13:44:46.168  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.168  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 13:44:46.168  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 13:44:46.169  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:44:46.169  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.169  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.170  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.170  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.170  6456  6456 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:44:46.170  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:44:46.170  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.171  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.171  1033  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 13:44:46.171  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:44:46.171  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.172  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.172  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:44:46.172  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:44:46.172  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.172  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.172  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:44:46.172  1033  6475 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.172  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 13:44:46.172  1033  6475 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.172  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 13:44:46.172  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init,=CORE type=UNKNOWN
08-29 13:44:46.172  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:44:46.173  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 13:44:46.173  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 13:44:46.173  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 13:44:46.173  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
08-29 13:44:46.174  1033  1537 D WifiNative-wlan0: SCAN: returned false
08-29 13:44:46.174  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=123672  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:44:46.176  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 13:44:46.177  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=123674  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:44:46.177  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 13:44:46.178  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 13:44:46.178  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 13:44:46.178  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-29 13:44:46.178  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 13:44:46.178  1033  1536 D LGWifiP2pService: before postfix = G3
08-29 13:44:46.178  1033  1536 D WifiServerServiceExt: postfix byte check : 2
08-29 13:44:46.178  1033  1536 D LGWifiP2pService: after postfix = G3
08-29 13:44:46.178  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 13:44:46.179  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 13:44:46.179  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 13:44:46.179  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 13:44:46.179  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 13:44:46.180  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 13:44:46.180  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 13:44:46.180  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 13:44:46.180  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 13:44:46.180  1941  2282 D WfdsService: Receive the WFDS_ENABLE Method
08-29 13:44:46.180  1941  2282 D WfdsService: Set the WFDS Monitor: true
08-29 13:44:46.180  1941  2282 D WfdsService: Connected to the supplicant for wfds
08-29 13:44:46.180  1941  2282 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 13:44:46.181  6456  6456 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 13:44:46.181  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 13:44:46.181  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:44:46.181  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 13:44:46.181  1941  2282 D WfdsService: selectPreferredScanChannel [36]
08-29 13:44:46.181  1941  2282 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 13:44:46.183  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.183  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.183  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-29 13:44:46.185  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 13:44:46.185  1941  1941 D WfdsService: isConnected: false
08-29 13:44:46.185  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.186  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 13:44:46.189  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.189  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.190  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.191  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.191  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 13:44:46.191  1033  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:44:46.192  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:44:46.192  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:44:46.192  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:44:46.193  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 13:44:46.193  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 13:44:46.193  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:44:46.193  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 13:44:46.193  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 13:44:46.194  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 13:44:46.194  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 13:44:46.194  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 13:44:46.194  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-29 13:44:46.197  6347  6479 W FormManager: Network not available. Please check & try again.
08-29 13:44:46.198  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 13:44:46.198  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 13:44:46.198  1941  1941 D WfdsService: Update P2p Interface State: 3
08-29 13:44:46.201  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:44:46.201  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:46.203  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:46.204  6347  6480 V FormManager: Network unavailable.
08-29 13:44:46.206  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:44:46.207  6347  6480 V FormManager: Network unavailable.
08-29 13:44:46.211  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:46.212  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 13:44:46.212  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 13:44:46.213  1033  1536 D LGWifiP2pService: InactiveState
08-29 13:44:46.213  1033  1536 D LGWifiP2pService: InactiveState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.213  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.213  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 13:44:46.213  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:44:46.214  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.214  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:44:46.214  1033  6475 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.214  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.214  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:44:46.214  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:44:46.214  6456  6456 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-29 13:44:46.214  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.215  4267  6483 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:44:46.215  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.215  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 13:44:46.215  1033  1536 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.215  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  6475 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.216  1033  6475 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  6475 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  6475 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.216  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.217  1033  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.217  1941  2282 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 13:44:46.218  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.218  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:44:46.219  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.219  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:46.220  1033  1033 E WifiServerServiceExt: No p2p device connected
,08-29 13:44:46.222  4267  6484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:44:46.222  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:46.223  4267  6484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:46.227  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.232  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.232  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.233  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 13:44:46.236  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:46.242  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:46.246  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.251  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.252  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.253  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:44:46.256  6164  6164 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 13:44:46.257  6164  6164 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 13:44:46.262  6164  6164 V [BNRBootReceiver]: Boot Receiver Return
,08-29 13:44:46.704  6456  6456 E wpa_supplicant: USIM:  scard_init function
,08-29 13:44:46.705  6456  6456 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 13:44:46.716  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 13:44:46.716  1033  6475 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 13:44:46.716  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 13:44:46.716  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-29 13:44:46.717  1033  6475 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 13:44:46.717  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:44:46.717  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 13:44:46.721  1033  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-29 13:44:46.722  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-29 13:44:46.722  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-29 13:44:46.722  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=12 bcn=0
08-29 13:44:46.723  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 13:44:46.740  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=124238  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 13:44:46.749  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.749  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.751  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.755  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.755  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.755  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 13:44:46.759  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=124256  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 13:44:46.760  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.760  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 13:44:46.761  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 13:44:46.777  6238  6238 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 13:44:46.784  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:44:46.796  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:46.806  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.815  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.815  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.816  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:44:46.837  6456  6456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:44:46.844  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 13:44:46.844  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 13:44:46.844  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 13:44:46.844  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 13:44:46.844  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:44:46.845  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:44:46.852  6456  6456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:44:46.852  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 13:44:46.862  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-29 13:44:46.862  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:44:46.863  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 13:44:46.863  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:44:46.863  1033  6475 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:44:46.863  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=124360  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 13:44:46.863  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 13:44:46.863  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:44:46.863  1033  6475 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:44:46.863  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=124361  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 13:44:46.864  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:44:46.864  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:44:46.864  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124362
08-29 13:44:46.865  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124362
08-29 13:44:46.865  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124363
08-29 13:44:46.867  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124365
08-29 13:44:46.868  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124365
08-29 13:44:46.869  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=124366  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:44:46.869  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 13:44:46.878  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:46.878  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:44:46.878  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:44:46.878  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:44:46.880  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:44:46.881  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.882  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 13:44:46.884  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.885  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.885  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.885  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:44:46.886  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=124383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:44:46.887  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=124384  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:44:46.888  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=124385  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:44:46.890  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.890  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.890  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 13:44:46.893  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:44:46.893  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124390
08-29 13:44:46.893  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 13:44:46.893  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:44:46.893  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:44:46.893  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:44:46.893  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 13:44:46.893  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:44:46.894  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124391
08-29 13:44:46.894  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.894  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 13:44:46.895  1033  1537 D WifiNative-wlan0: doString: [STATUS]
08-29 13:44:46.896  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:44:46.896  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 13:44:46.899  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:46.899  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:44:46.902  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 13:44:46.907  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.907  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.910  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.910  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:46.911  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 13:44:46.911  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 13:44:46.919  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.919  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.919  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:44:46.921  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.923  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.923  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:46.923  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-29 13:44:46.933  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.933  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.934  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.934  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.934  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.934  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:44:46.937  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:46.937  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:46.937  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:46.939  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-29 13:44:46.939  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
08-29 13:44:46.941  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:44:46.941  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:44:46.941  1033  1543 D ConnectivityService: NetworkAgent connected
08-29 13:44:46.942  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.944  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:44:46.945  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:46.945  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:44:46.945  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 13:44:46.952  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.955  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:44:46.955  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:44:46.955  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:44:46.955  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:44:46.955  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:44:46.959  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.959  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.959  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:44:46.962  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:44:46.963   310   890 D CommandListener: Setting iface cfg
08-29 13:44:46.963  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:44:46.971  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:46.973  1033  6513 D DhcpStateMachine: StoppedState
08-29 13:44:46.973  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 1
08-29 13:44:46.973  1033  6513 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.973  1033  6513 D DhcpStateMachine: WaitBeforeStartState
08-29 13:44:46.974  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:44:46.974  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:44:46.974  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 13:44:46.975  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.975  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.975  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.976  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.976  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.976  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:46.977  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:44:46.978  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:44:46.978  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124476  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:44:46.979  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.979  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 13:44:46.980  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-702695548] from screen [on:0 period:-702695548]
08-29 13:44:46.981  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-702695547]
08-29 13:44:46.981  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 13:44:46.985  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:46.985  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:46.986  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-29 13:44:46.986  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:46.987  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 13:44:46.987  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:46.988  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:46.988  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:46.988  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:46.989  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 13:44:46.989  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 13:44:46.990  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 13:44:46.990  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 13:44:46.990  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 13:44:46.990  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 13:44:46.990  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 13:44:46.991  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
08-29 13:44:46.991  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 13:44:46.991  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 13:44:46.991  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 13:44:46.991  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@726ed2f target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.991  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@726ed2f target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.992  1033  6513 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:46.992  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 13:44:46.992  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:46.992  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:44:46.992  1033  6513 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 13:44:46.992  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:44:46.992  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-29 13:44:46.992  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:46.992  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:44:46.993  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.993  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:44:46.994  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:46.994  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:44:46.996  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:47.002  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:47.007  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:47.013  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:47.013  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:47.013  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:44:47.176  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:47.176  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:47.177  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:47.195  1033  6513 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 13:44:47.197  1033  6513 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-29 13:44:47.197  1033  6513 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 13:44:47.226  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-29 13:44:47.224  6514  6514 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:47.224  6514  6514 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:47.226  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:44:47.227  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:44:47.227  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:44:47.227  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:44:47.228  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:44:47.256  6514  6514 I dhcpcd  : version 5.5.6 starting
,08-29 13:44:47.260  6514  6514 E dhcpcd  : get_duid: m
08-29 13:44:47.260  6514  6514 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,08-29 13:44:47.260  6514  6514 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 13:44:47.418  6514  6514 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:44:47.418  6514  6514 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:44:47.419  6514  6514 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-29 13:44:47.422  6514  6514 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-29 13:44:47.422  6514  6514 D dhcpcd  : wlan0: sending REQUEST (xid 0xb36686ef), next in 4.72 seconds
08-29 13:44:47.445  6514  6514 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 13:44:47.448  6514  6514 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 13:44:47.448  6514  6514 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 13:44:47.449  6514  6514 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 13:44:47.449  6514  6514 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 13:44:47.449  6514  6514 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:44:47.450  6514  6514 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:44:47.450  6514  6514 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:44:47.450  6514  6514 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 13:44:47.453  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:47.454  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:47.456  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:47.457  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 13:44:47.458  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:47.459  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 13:44:47.460  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-29 13:44:47.810  1033  6513 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 13:44:47.817  1033  6513 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-29 13:44:47.820  1033  6513 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:44:47.821  1033  6513 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-29 13:44:47.830  1033  6513 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-29 13:44:47.833  1033  6513 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:44:47.833  1033  6513 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-29 13:44:47.834  1033  6513 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 13:44:47.834  1033  6513 D DhcpStateMachine: RunningState
08-29 13:44:47.835  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:44:47.836  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:44:47.836  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:44:47.836  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:44:47.837  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:47.837  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:47.837  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:44:47.838  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 13:44:47.838  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 13:44:47.839  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 13:44:47.839  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:44:47.854  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:44:47.855  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:44:47.856  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:44:47.856  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-29 13:44:47.861  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 13:44:47.861  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
,08-29 13:44:47.885  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:47.885  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:47.890  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.890  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.890  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 13:44:47.897  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 13:44:47.899  1033  1543 D ConnectivityService: Adding iface wlan0 to network 100
08-29 13:44:47.904  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:44:47.935  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.935  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.935  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 13:44:47.951  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:47.954  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:47.954  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:47.969  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 13:44:47.976  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 13:44:47.980  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:44:47.980  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-29 13:44:47.982  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-29 13:44:47.985  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-29 13:44:47.987  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 13:44:47.987  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-29 13:44:47.987  1033  1543 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-29 13:44:47.991  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.991  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.991  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:44:47.993  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:47.998  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 13:44:48.008  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.008  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.008  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:44:48.012  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:44:48.012  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 13:44:48.012  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-29 13:44:48.019  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.019  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 13:44:48.020  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.020  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:48.022  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 13:44:48.022  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:44:48.023  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.030  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 13:44:48.030  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:48.030  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:44:48.030  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 13:44:48.030  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.031  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 13:44:48.031  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-29 13:44:48.031  1033  1543 D ConnectivityService:    accepting network in place of null
08-29 13:44:48.031  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.032  1033  1543 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-29 13:44:48.035  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.031  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.035  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:48.035  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-29 13:44:48.043  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:48.043  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:44:48.044  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.049  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:44:48.049  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 13:44:48.050  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 13:44:48.056  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:48.057  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 13:44:48.057   310  6565 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 13:44:48.061  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 13:44:48.062  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 13:44:48.062  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:44:48.063  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-29 13:44:48.063  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:44:48.063  1033  1033 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-29 13:44:48.064  1033  1543 D ConnectivityService: validation of new default Network = false
08-29 13:44:48.064  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 13:44:48.064  1033  1543 D DSQN    : enableDataServiceNotify 
08-29 13:44:48.065  1033  1543 D DSQN    : start dsqn bin
08-29 13:44:48.066   310  6571 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 13:44:48.067   310  6571 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 13:44:48.070   310  6572 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 13:44:48.070   310  6572 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-29 13:44:48.075  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:44:48.079  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 13:44:48.080  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.080  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:44:48.080  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:44:48.081  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:44:48.074  6573  6573 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:48.074  6573  6573 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:44:48.101  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:44:48.101  6573  6573 E DSQN    : DSQN ssw
08-29 13:44:48.102  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.103  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.107  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:48.114  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.126  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:44:48.127  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:44:48.134  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:44:48.137  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:48.144  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:48.150  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:44:48.156  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:48.157  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:48.157  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:44:48.162  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:48.166  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:44:48.171  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:48.175  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:48.182  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.191  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:44:48.191  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:48.192  6310  6310 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:44:48.193  6310  6310 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-29 13:44:48.194  6310  6310 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 13:44:48.201  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:44:48.207  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:44:48.208  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:48.215  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:44:48.224  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:44:48.229  1033  1975 D WifiServiceImplEx: setWifiEnabled: false pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:44:48.230  1033  1975 D WifiService: setWifiEnabled: false pid=6023, uid=10118
08-29 13:44:48.230  1033  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:44:48.241  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:48.241  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:44:48.242  6310  6310 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:44:48.244  6310  6310 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:44:48.244  6310  6310 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:44:48.252  1033  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:48.252  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:44:48.252  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:48.253  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:48.253  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 13:44:48.253  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:48.253  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:48.254  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:44:48.254  1033  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:44:48.254  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:44:48.254  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:44:48.255  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:44:48.255  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 13:44:48.265  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:44:48.266  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.266  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.266  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:44:48.266  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:44:48.267  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:44:48.267  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:44:48.268  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:44:48.269  1033  6513 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.270   310   890 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:48.308  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 13:44:48.308  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 13:44:48.313  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:48.313  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:48.314  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 13:44:48.316  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 13:44:48.316  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.317  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.318  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.319  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:48.322  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:44:48.327  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 13:44:48.328  1033  1536 D LGWifiP2pService: InactiveState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.328  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.328  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@306f9118
08-29 13:44:48.329  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.329  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.330  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.330  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.331  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.331  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:44:48.332  1033  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:44:48.334  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.334  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.334  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:48.334  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:44:48.334  1033  1033 D RttService: SCAN_AVAILABLE : 1
,08-29 13:44:48.336  1033  1556 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.337  1033  1555 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.338  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:48.338  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:48.339  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.340  1033  1536 D LGWifiP2pService: P2pDisablingState
08-29 13:44:48.340  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.340  1033  1536 D LGWifiP2pService: p2p socket connection lost
08-29 13:44:48.340  1033  1536 D LGWifiP2pService: P2pDisabledState
08-29 13:44:48.342  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 13:44:48.342  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:44:48.342  6456  6456 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:44:48.342  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.342  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:48.343  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:44:48.343  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:44:48.343  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:44:48.344  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:44:48.344  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 13:44:48.344  1941  2282 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 13:44:48.344  1941  2282 D WfdsService: Set the WFDS Monitor: false
08-29 13:44:48.345  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:44:48.345  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:48.345  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:48.346  1941  2282 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:44:48.346  1941  2282 D WfdsService: STATE : WfdsDisabledState - enter
08-29 13:44:48.346  1941  6477 D CtrlSupplicant: Received on exit socket, terminate
08-29 13:44:48.346  1941  6477 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 13:44:48.346  1941  6477 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 13:44:48.346  1941  6477 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 13:44:48.346  1941  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 13:44:48.346  1941  2282 W WfdsService: DefaultState - msg [9445378] is not handled
,08-29 13:44:48.349  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:48.353  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.361  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:44:48.361  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:48.363  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:44:48.365   310   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:48.365  1033  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 13:44:48.365  1033  1543 D DSQN    : disableDataServiceNotify
08-29 13:44:48.365  1033  1543 D DSQN    : stop dsqn bin
08-29 13:44:48.366  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:48.367  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 13:44:48.368  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
08-29 13:44:48.368  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:48.368  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:48.368  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:48.368  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-29 13:44:48.368  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:44:48.368  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:44:48.369  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.369  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.369  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:44:48.369  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.370  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 13:44:48.372  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:44:48.373  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.373  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:48.373  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.373  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:48.374  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.374  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:48.374  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.374  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:48.374  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 13:44:48.374  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:44:48.374  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:48.374  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:48.374  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:44:48.374  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 13:44:48.376  1033  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 13:44:48.376  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.376  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:44:48.376  1033  1543 D ConnectivityS,ervice: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:44:48.377  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 13:44:48.378  1033  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 13:44:48.378  1033  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 13:44:48.378  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 13:44:48.378  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:44:48.380  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:48.381  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:48.381  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:44:48.381  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:48.381  1033  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.381  1033  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.381  1033  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.381  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:48.381  1033  1543 D NetworkManagementService: Removing idletimer
08-29 13:44:48.382  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:48.382  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:44:48.382  1033  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.383  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 13:44:48.383  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:44:48.384  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:44:48.384  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:44:48.384  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.384  1033  1033 D LocSvc_java: Send,ing msg: 4 arg1:0 arg2:1
08-29 13:44:48.385  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:44:48.385  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:44:48.385  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:44:48.385  1033  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 13:44:48.393  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:48.393  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:48.395  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:44:48.398  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:44:48.403  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:44:48.405  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:48.405  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:48.407  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:44:48.413  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.414  6456  6456 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 13:44:48.414  6456  6456 I wpa_supplicant: monitor socket send errors count : 1
08-29 13:44:48.414  6456  6456 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-29 13:44:48.414  1033  6475 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 13:44:48.414  1033  6475 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 13:44:48.420  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:44:48.420  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:44:48.421  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 13:44:48.431  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:44:48.431  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:44:48.432  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.432  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.433  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:48.438  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:44:48.439  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:48.439  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 13:44:48.439  6456  6456 W wpa_supplicant: USIM:  scard_deinit function
08-29 13:44:48.439  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:48.440  1033  6475 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:48.442  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 13:44:48.442  1033  6475 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 13:44:48.442  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:44:48.442  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:44:48.443  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125940
08-29 13:44:48.443  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125941
,08-29 13:44:48.444  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=125941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:44:48.444  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=125941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:44:48.446  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:48.446  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:48.447  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:44:48.447  6347  6587 W FormManager: Network not available. Please check & try again.
08-29 13:44:48.447   310  6589 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:44:48.450  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:44:48.458  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:48.459  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 13:44:48.459  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:44:48.459  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:44:48.459  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:44:48.460  6347  6588 V FormManager: Network unavailable.
08-29 13:44:48.460  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:44:48.461  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:44:48.461  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:44:48.461  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:44:48.461  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:44:48.461  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:44:48.466  6347  6588 V FormManager: Network unavailable.
08-29 13:44:48.468  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:44:48.469  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.469  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:44:48.481  1033  6513 D DhcpStateMachine: StoppedState
08-29 13:44:48.481  1033  6513 D DhcpStateMachine: StoppedState{ when=-138ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:48.483  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-29 13:44:48.483  1033  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 13:44:48.489  6456  6456 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 13:44:48.490  1033  6475 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 13:44:48.490  1033  6475 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 13:44:48.490  1033  6475 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 13:44:48.491  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
08-29 13:44:48.594  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 13:44:48.595  1941  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 13:44:48.595  1941  2282 D WfdsService: Set the WFDS Monitor: false
08-29 13:44:48.595  1941  2282 D WfdsMonitor: WFDS Monitor is stopped
,08-29 13:44:48.601  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 13:44:48.602  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:44:48.602  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:44:48.602  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:44:48.602  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:44:48.603  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:48.606  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:44:48.607  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:44:48.610  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:44:48.612  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 13:44:48.614  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 13:44:48.614  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 13:44:48.614  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.614  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:48.618  2464  2464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:48.619  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.619  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:48.622  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:48.634  4267  6590 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:44:48.637  6256  6256 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 13:44:48.637  6256  6256 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:44:48.637  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:44:48.640  4267  6592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:44:48.642  4267  6592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:48.643  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:48.645  6347  6593 W FormManager: Network not available. Please check & try again.
,08-29 13:44:48.650  6347  6594 V FormManager: Network unavailable.
,08-29 13:44:48.652  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:44:48.652  6347  6594 V FormManager: Network unavailable.
,08-29 13:44:49.241  6194  6436 D UEI.SmartControl: Internal timer expired: 2
08-29 13:44:49.241  6194  6436 D UEI.SmartControl: unbind internal service
,08-29 13:44:49.587  6194  6433 D serial_port: close(fd = 24)
,08-29 13:44:49.593  6194  6433 I UEI.SmartControl: Serial port is closed.
,08-29 13:44:49.991  1033  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-702692537] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 13:44:49.993  1033  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-702692535] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 13:44:51.059  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:51.074  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 13:44:51.089  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.093  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.096  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.101  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 13:44:51.105  3733  3755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 13:44:51.118  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 13:44:51.179  2158  2158 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:51.259  1033  2028 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6606 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 13:44:51.262  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:51.262  1033  1939 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-29 13:44:51.265  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:51.282  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:44:51.282  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:51.283  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 13:44:51.284  1033  1095 D BluetoothManagerService: Message: 1
08-29 13:44:51.284  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 13:44:51.288   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 28.750ms
,08-29 13:44:51.309   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 604us total 20.724ms
08-29 13:44:51.324  1033  1090 E GpsLocationProvider: No APN found to select.
,08-29 13:44:51.330   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 20.900ms
08-29 13:44:51.331  1033  1095 D BluetoothManagerService: Message: 20
08-29 13:44:51.331  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cf55f40:true
08-29 13:44:51.332  6389  6389 D BluetoothAdapterState: make
08-29 13:44:51.336  6389  6389 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 13:44:51.337  6389  6636 I BluetoothAdapterState: Entering OffState
08-29 13:44:51.337  6389  6389 I bluedroid-qcom: init
,08-29 13:44:51.339  6389  6389 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:44:51.340  6389  6389 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:44:51.340  6389  6389 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:44:51.340  6389  6389 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:44:51.340  6389  6389 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 13:44:51.340  6389  6389 I bluedroid-qcom: get_profile_interface socket
08-29 13:44:51.340  6389  6389 I bluedroid-qcom: get_profile_interface map_client
08-29 13:44:51.342  6389  6639 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 13:44:51.334  6640  6640 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:51.334  6640  6640 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:51.345  6389  6639 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 13:44:51.347  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:44:51.347  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:44:51.347  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 13:44:51.348  6389  6639 D BluetoothAdapterProperties: Name is: G3
08-29 13:44:51.348  1033  1095 D BluetoothManagerService: Message: 40
08-29 13:44:51.348  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 13:44:51.349  6389  6406 I bluedroid-qcom: config_hci_snoop_log
08-29 13:44:51.349  6640  6640 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 13:44:51.349  6640  6640 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 13:44:51.349  6640  6640 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 13:44:51.351  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 13:44:51.351  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 13:44:51.356  6640  6640 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 13:44:51.356  6389  6636 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 13:44:51.357  6389  6636 D BluetoothAdapterProperties: Setting state to 11
08-29 13:44:51.357  6389  6636 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:44:51.357  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:51.357  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 13:44:51.358  6389  6636 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 13:44:51.359  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 13:44:51.361  6640  6640 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 13:44:51.361  6640  6640 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-29 13:44:51.364  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:51.365  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:44:51.366  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.366  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 13:44:51.368  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.370  6389  6389 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:44:51.370  6389  6389 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:51.370  6389  6389 V BluetoothPbapReceiver: ***********state = 11
08-29 13:44:51.372  6389  6636 D BluetoothBondStateMachine: make
08-29 13:44:51.374  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:51.374  6389  6642 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:44:51.374  6389  6636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.375  6389  6636 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 13:44:51.375  6389  6636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.375  6389  6636 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 13:44:51.375  6389  6636 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-29 13:44:51.379  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:44:51.381  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.382  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.391  6606  6606 I AppUp4:AppBoxCP: onCreate
,08-29 13:44:51.393  6606  6606 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 13:44:51.400  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 13:44:51.400  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.402  6606  6606 I AppUp4:DB:  setFingerPrint start
,08-29 13:44:51.402  6606  6606 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 13:44:51.405  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-29 13:44:51.406  6389  6389 D HeadsetService: Received start request. Starting profile...
08-29 13:44:51.407  6389  6389 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:44:51.407  6389  6389 D LGBluetoothHfpAdapter: Version 1.6
08-29 13:44:51.410  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.411  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.411  6389  6389 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:44:51.412  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.412  6389  6389 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:44:51.413  6389  6389 D HeadsetStateMachine: make
08-29 13:44:51.416  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.416  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 13:44:51.419  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 13:44:51.420  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.423  6606  6606 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 13:44:51.423  6606  6606 I AppUp4:DB:  SDK version = 21
08-29 13:44:51.423  6606  6606 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 13:44:51.424  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 13:44:51.427  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:44:51.428  6606  6606 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 13:44:51.428  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:44:51.429  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:44:51.429  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:51.431  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:44:51.432  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 13:44:51.434  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:44:51.435  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:51.435  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:51.437  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:44:51.442  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:44:51.442  6606  6606 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:44:51.446  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 13:44:51.450  6389  6636 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:44:51.458  6389  6389 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:44:51.458  6389  6389 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:51.463  6389  6389 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:44:51.463  6389  6389 I bluedroid-qcom: get_profile_interface handsfree
08-29 13:44:51.465  6389  6389 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 13:44:51.465   315  2185 V AudioPolicyService: registerClient() client 0xb1023f00, uid 1002
08-29 13:44:51.466  6389  6636 V LGMDMManager: Create singleton instance
08-29 13:44:51.466   315  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:44:51.466   315  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:44:51.466   315  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:44:51.466  6389  6389 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:44:51.466   315  2184 V AudioFlinger: registerClient() client 0xb5581808, pid 6389
08-29 13:44:51.467   315  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.467   315  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.467  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.467  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.467  3387  3404 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.467  3387  3404 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.467  1852  4373 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.467  1852  4373 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.468  1033  2028 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.468  1033  2028 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.468  6389  6643 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.468  6389  6643 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 13:44:51.468  2186  2203 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:44:51.468  6389  6389 V ToneGenerator: Create Track: 0xb4928a80
08-29 13:44:51.468  2186  2203 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:44:51.468  6389  6389 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 13:44:51.468  6389  6389 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 13:44:51.468   315  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469   315  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.469   315  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:44:51.469   315  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:44:51.469   315  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:44:51.469   315  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:44:51.469  3387  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469  3387  3402 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.469  6389  6406 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469  1033  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469  6389  6406 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 13:44:51.469  1033  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.469   315  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:44:51.469   315   31,5 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:44:51.469   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 13:44:51.469   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:44:51.469  1601  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:44:51.469  1601  2101 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.469  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.469  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.470  2186  6186 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:44:51.470  2186  6186 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:44:51.470  6389  6389 V AudioSystem: getLatency() output 2, latency 50
08-29 13:44:51.470  6389  6389 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 13:44:51.470  6389  6389 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 13:44:51.471   315  2184 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:44:51.471   315  2184 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:44:51.471   315  2184 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:44:51.471   315  2184 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:44:51.471   315  2184 V AudioFlinger: createTrack() lSessionId: 22
08-29 13:44:51.472  6389  6389 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 13:44:51.473   315  2184 V AudioFlinger: acquiring 22 from 6389, for 6389
08-29 13:44:51.473   315  2184 V AudioFlinger:  added new entry for 22
08-29 13:44:51.474  6389  6389 V ToneGenerator: ToneGenerator INIT OK, time: 128985
08-29 13:44:51.474  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.475  6389  6636 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:44:51.475  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.477  6389  6389 D A2dpService: Received start request. Starting profile...
08-29 13:44:51.478  6389  6389 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:44:51.478  6389  6649 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 13:44:51.480  6389  6389 V Avrcp   : make
08-29 13:44:51.481  6389  6389 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 13:44:51.481  6389  6389 I bluedroid-qcom: get_profile_interface avrcp
08-29 13:44:51.482  6389  6649 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:44:51.482  6389  6649 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:44:51.482  6389  6649 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 13:44:51.483   315  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6389
08-29 13:44:51.483   315  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 13:44:51.483   315  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 13:44:51.483   315  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 13:44:51.483   315  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 13:44:51.483   315  1384 V voice   : voice_set_parameters: exit with code(0)
08-29 13:44:51.483   315  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 13:44:51.483   315  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 13:44:51.483   315  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 13:44:51.483   315  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 13:44:51.483   315  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 13:44:51.483   315  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 13:44:51.483  6389  6649 V ToneGenerator: ToneGenerator destructor
08-29 13:44:51.483  6389  6649 V ToneGenerator: stopTone
08-29 13:44:51.483  6389  6649 V ToneGenerator: Delete Track: 0xb4928a80
08-29 13:44:51.484  6389  6649 V AudioTrack: ~AudioTrack, releasing session id from 6389 on behalf of 6389
08-29 13:44:51.484   315  2185 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 13:44:51.484   315   315 V AudioFlinger: releasing 22 from 6389 for 6389
08-29 13:44:51.484   315   315 V AudioFlinger:  decremented refcount to 0
08-29 13:44:51.484   315  2185 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 13:44:51.484   315   315 V AudioFlinger: purging stale effects
08-29 13:44:51.484   315  1259 V AudioPolicyService: AudioCommandThread() waking up
08-29 13:44:51.484   315  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 13:44:51.484   315  1259 V AudioPolicyManager: releaseOutput() 2
08-29 13:44:51.484   315  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 13:44:51.484   315  2185 V AudioFlinger: PlaybackThread::Track destructor
08-29 13:44:51.484   315  2185 V AudioFlinger: removeClient_l() pid 6389, calling pid 315
08-29 13:44:51.489  6389  6389 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 13:44:51.492  6389  6389 E AudioManager: No RCC entry present to update
08-29 13:44:51.492  6389  6389 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 13:44:51.495  6389  6389 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 13:44:51.496  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 13:44:51.496  6389  6389 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 13:44:51.496  6606  6606 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:51.496  6606  6606 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:51.500  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 13:44:51.504  6606  6606 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7b04e6a
08-29 13:44:51.504  6606  6606 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:44:51.504  6606  6606 D AppUp4:CustFacade: isPhone : true
08-29 13:44:51.550  6606  6606 D AppUp4:CustModeStarterReceiver: begin check event
,08-29 13:44:51.550  6606  6606 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 13:44:51.550  6606  6606 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 13:44:51.570  6606  6650 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-29 13:44:51.570  6606  6650 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 13:44:51.570  6606  6650 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-29 13:44:51.580  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:51.580  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:51.584  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:44:51.589  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:51.602  4267  6656 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:44:51.605  4267  6657 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:51.605  4267  6657 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:51.623  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:44:51.624  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:44:51.645  1033  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6658 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 13:44:51.683  1033  2028 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 13:44:51.690  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:44:51.694  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 13:44:51.695  6389  6389 I BluetoothA2dpServiceJni: classInitNative
08-29 13:44:51.695  6389  6389 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:44:51.695  6389  6389 D A2dpStateMachine: make
,08-29 13:44:51.699  6389  6389 I bluedroid-qcom: get_profile_interface a2dp
08-29 13:44:51.699  6389  6676 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 13:44:51.702  6389  6389 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:44:51.702  6389  6389 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 13:44:51.703  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.703  6389  6675 D A2dpStateMachine: Enter Disconnected: -2
08-29 13:44:51.703  6389  6389 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:44:51.705  6389  6389 D HidService: Received start request. Starting profile...
08-29 13:44:51.705  6389  6389 I bluedroid-qcom: get_profile_interface hidhost
08-29 13:44:51.705  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.705  6389  6389 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:44:51.707  6389  6389 D HealthService: Received start request. Starting profile...
08-29 13:44:51.710  6389  6389 I bluedroid-qcom: get_profile_interface health
08-29 13:44:51.710  6389  6389 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:44:51.710  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.711  6389  6389 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:44:51.712  6389  6389 D PanService: Received start request. Starting profile...
08-29 13:44:51.713  6389  6389 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:44:51.713  6389  6389 I bluedroid-qcom: get_profile_interface pan
08-29 13:44:51.719  6389  6389 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 13:44:51.719  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.720  6389  6389 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 13:44:51.723  6389  6389 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:44:51.723  6389  6389 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:44:51.724  6389  6389 D BtGatt.GattService: start()
08-29 13:44:51.724  6389  6389 I bluedroid-qcom: get_profile_interface gatt
08-29 13:44:51.724  6389  6389 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:44:51.729  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.730  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.730  6389  6389 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 13:44:51.731  6389  6389 V BluetoothMapService: BluetoothMapBinder()
08-29 13:44:51.732  6389  6389 D BluetoothMapService: Received start request. Starting profile...
08-29 13:44:51.732  6389  6389 D BluetoothMapService: start()
08-29 13:44:51.732  6658  6658 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:51.733  6658  6658 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:44:51.734  6658  6658 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:44:51.735  6658  6658 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 13:44:51.735  6389  6389 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-29 13:44:51.735  6389  6389 D BluetoothMapEmailAppObserver: createReceiver()
08-29 13:44:51.736  6389  6389 D BluetoothMapEmailAppObserver: initObservers()
08-29 13:44:51.737  6389  6389 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 13:44:51.749  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:51.749  6389  6389 D HeadsetStateMachine: Proxy object connected
08-29 13:44:51.750  6389  6389 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 13:44:51.750  6389  6389 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 13:44:51.754  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:44:51.754  6389  6649 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 13:44:51.755  6389  6649 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:44:51.755  6389  6649 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 13:44:51.757  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:44:51.761  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 13:44:51.765  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 13:44:51.767  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:51.768  6389  6389 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 13:44:51.772  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:44:51.775  6389  6389 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.776  6389  6389 V BluetoothMapService: Handler(): got msg=1
,08-29 13:44:51.777  6389  6636 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 13:44:51.777  6389  6389 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:44:51.777  6389  6636 I bluedroid-qcom: enable
08-29 13:44:51.777  6389  6389 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:44:51.777  6389  6389 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:44:51.777  6389  6389 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:51.777  6389  6683 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 13:44:51.778  6389  6636 I bt_hci_bdroid: init
08-29 13:44:51.778  6389  6683 I bt-btu  : btu_task pending for preload complete event
08-29 13:44:51.778  6389  6389 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 13:44:51.781  6389  6636 I bt_vendor: bt-vendor : init
08-29 13:44:51.781  6389  6636 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:44:51.781  6389  6636 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:44:51.781  6389  6636 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 13:44:51.781  6389  6636 D bt_userial_mct: userial_init
08-29 13:44:51.782  6389  6636 D bt_hci_bdroid: set_power 1
08-29 13:44:51.782  6389  6636 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 13:44:51.782  6389  6636 I bt_vendor: Starting hciattach daemon
08-29 13:44:51.782  6389  6636 I bt_vendor: try to set true
08-29 13:44:51.774  6686  6686 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:51.774  6686  6686 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:51.809  6687  6687 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 13:44:51.832  6658  6658 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 13:44:51.845  6658  6658 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 13:44:51.895  6694  6694 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 13:44:51.902  6658  6658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:44:51.909  6695  6695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:44:51.939  6658  6658 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:44:51.939  6658  6658 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:51.948  6697  6697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-29 13:44:51.965  6699  6699 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 13:44:51.977  6700  6700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:44:51.990  6703  6703 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 13:44:52.025  6705  6705 I libmdmdetect: ESOC framework not supported
08-29 13:44:52.026  6705  6705 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 13:44:52.033  6658  6658 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 13:44:52.034  6705  6705 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 13:44:52.034  6705  6705 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 13:44:52.034  6705  6705 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 13:44:52.034  6705  6705 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 13:44:52.034  6705  6705 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 13:44:52.034  6705  6705 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 13:44:52.034  6705  6705 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 13:44:52.059  3387  3387 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:44:52.059  3387  3387 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:52.061  3387  3387 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 13:44:52.061  3387  3387 D PhoneState: setPdpRejectCasuse : false
08-29 13:44:52.063  6658  6658 I HubEmail: JNI_OnLoad()
08-29 13:44:52.063  6658  6658 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:44:52.063  6658  6658 I HubEmail: registerNatives()
08-29 13:44:52.063  6658  6658 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:44:52.063  6658  6658 I HubEmail: registerNativeMethods()
08-29 13:44:52.063  6658  6658 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:44:52.064  6658  6658 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 13:44:52.068  6705  6706 E QC-QMI  : qmi_client [6705] 14: failed to locate client data
08-29 13:44:52.069   489   489 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 13:44:52.069   489   489 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-29 13:44:52.096  1033  1940 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6715 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 13:44:52.107  6721  6721 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
08-29 13:44:52.108  6347  6712 W FormManager: Network not available. Please check & try again.
08-29 13:44:52.109  6658  6714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:52.113  6347  6713 V FormManager: Network unavailable.
,08-29 13:44:52.115  6347  6713 V FormManager: Network unavailable.
08-29 13:44:52.123  1033  1777 I ActivityManager: Killing 2186:com.lge.music/u0a34 (adj 15): empty #17
08-29 13:44:52.128  6722  6722 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:44:52.148   315  1384 V AudioFlinger: 2186 died, releasing its sessions
,08-29 13:44:52.148   315  1384 V AudioFlinger:  pid 1852 @ 0
08-29 13:44:52.148   315  1384 V AudioFlinger:  pid 3387 @ 1
08-29 13:44:52.148   315  1384 V AudioFlinger:  pid 3387 @ 2
08-29 13:44:52.184  6389  6636 I bt_vendor: bluetooth satus is on
08-29 13:44:52.184  6389  6636 D bt_hci_bdroid: preload
,08-29 13:44:52.184  6389  6685 D bt_userial_mct: userial_open(port:0)
08-29 13:44:52.184  6389  6685 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 13:44:52.187  6389  6685 I bt_vendor: Done intiailizing UART
08-29 13:44:52.188  6389  6685 I bt_vendor: Done intiailizing UART
08-29 13:44:52.188  6389  6685 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 13:44:52.188  6389  6685 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 13:44:52.188  6389  6741 D bt_userial_mct: Entering userial_read_thread()
08-29 13:44:52.189  6389  6683 I bt-btu  : btu_task received preload complete event
08-29 13:44:52.189  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 13:44:52.189  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 13:44:52.191  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 13:44:52.209  1033  1939 W libprocessgroup: failed to open /acct/uid_10034/pid_2186/cgroup.procs: No such file or directory
,08-29 13:44:52.236  1033  1648 I art     : Explicit concurrent mark sweep GC freed 123653(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.962ms total 91.406ms
,08-29 13:44:52.238  6389  6683 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 13:44:52.238  6389  6683 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:44:52.239  6389  6683 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 13:44:52.281  6715  6715 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:44:52.281  6715  6715 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:44:52.283  6715  6715 D PhoneMonitor: Register our PhoneStateListener
,08-29 13:44:52.305  6389  6683 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 13:44:52.305  6389  6683 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b2061 
,08-29 13:44:52.305  6389  6683 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b2061 
,08-29 13:44:52.308  6715  6715 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:44:52.314  6715  6715 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 13:44:52.324  6389  6639 E bt-btif : Calling BTA_HhEnable
08-29 13:44:52.324  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 13:44:52.324  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 13:44:52.324  6389  6683 W bt-l2cap: L2CAP - L2Ce_get_adapter_property service_mask
08-29 13:44:52.324  6389  6639 E bt-btif : L2CAP - L2Ce_get_adapter_property service_mask:0x2140040
08-29 13:44:52.325  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 13:44:52.325  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 13:44:52.325  6389  6639 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 13:44:52.330  6715  6715 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 13:44:52.331  6715  6715 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 13:44:52.331  6715  6715 D TelephonyAutoProfiling: [parse] Load xml
,08-29 13:44:52.332  6389  6683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:44:52.332  6389  6683 W bt-smp  : Plain text(LSB ~ MSB) = aa ff 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-29 13:44:52.332  6389  6683 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 cd f8 41 25 a5 15 c7 7d 6e a4 73 63 b2 19 b3 
08-29 13:44:52.332  6389  6683 W bt-btm  : Stopping oneshot timer
08-29 13:44:52.335  6715  6715 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 13:44:52.335  6715  6715 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 13:44:52.335  6715  6715 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 13:44:52.344  6715  6715 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-29 13:44:52.365  1033  1648 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6748 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:52.367  1033  1648 I ActivityManager: Killing 5966:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 13:44:52.491  1033  2010 W libprocessgroup: failed to open /acct/uid_10061/pid_5966/cgroup.procs: No such file or directory
,08-29 13:44:52.493  6389  6639 D BluetoothAdapterProperties: Name is: G3
,08-29 13:44:52.509  6389  6639 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:52.509  6389  6639 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:44:52.510  6389  6639 D bt_hci_bdroid: postload
,08-29 13:44:52.512  6389  6683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-29 13:44:52.513  6389  6639 D bte_conf: Device ID record 1 : primary
08-29 13:44:52.513  6389  6639 D bte_conf:   vendorId            = 00c4
08-29 13:44:52.513  6389  6639 D bte_conf:   vendorIdSource      = 0001
08-29 13:44:52.513  6389  6639 D bte_conf:   product             = 13a1
08-29 13:44:52.513  6389  6639 D bte_conf:   version             = 1000
08-29 13:44:52.513  6389  6639 D bte_conf:   clientExecutableURL = 
08-29 13:44:52.513  6389  6639 D bte_conf:   serviceDescription  = 
08-29 13:44:52.513  6389  6639 D bte_conf:   documentationURL    = 
08-29 13:44:52.513  6389  6639 D bte_conf: bte_load_did_conf no section named DID2.
08-29 13:44:52.515  6389  6685 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:44:52.515  6389  6685 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:44:52.515  6389  6685 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:44:52.515  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:44:52.517  6389  6636 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 13:44:52.517  6389  6636 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:44:52.517  6389  6636 D BluetoothAdapterProperties: State =  11
08-29 13:44:52.518  6389  6636 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-29 13:44:52.518  6389  6685 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:44:52.518  6389  6636 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 13:44:52.519  6389  6636 D BluetoothAdapterProperties: Setting state to 12
08-29 13:44:52.519  6389  6636 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:44:52.519  6389  6639 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:44:52.519  6389  6741 E bt_mct  : hci lib postload completed
08-29 13:44:52.519  6389  6639 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:44:52.519  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:52.519  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 13:44:52.519  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 13:44:52.520  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:44:52.514  6772  6772 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:52.522  6389  6636 I BluetoothAdapterState: Entering On State
08-29 13:44:52.524  6238  6255 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:44:52.527  6389  6636 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 13:44:52.527  6389  6636 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 13:44:52.527  6389  6636 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 13:44:52.528  6389  6636 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 13:44:52.524  6772  6772 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:52.533  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:44:52.533  1033  1033 D BluetoothA2dp: Proxy object connected
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:52.535  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:52.539  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:52.545  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:52.548  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:52.552  6238  6238 D BluetoothInputDevice: Proxy object connected
08-29 13:44:52.552  6238  6238 D HidProfile: Bluetooth service connected
08-29 13:44:52.553  6389  6639 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:44:52.553  6389  6639 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-29 13:44:52.557  1852  4366 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:52.562  6238  6254 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:44:52.562  6238  6254 D BluetoothPan: onBluetoothStateChange call bindService
08-29 13:44:52.566  1852  1852 D BluetoothHeadset: Proxy object connected
,08-29 13:44:52.570  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:52.572  6389  6636 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 13:44:52.573  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 13:44:52.574  6238  6774 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:44:52.576  1852  4365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:52.578  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 13:44:52.579  6238  6255 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:44:52.582  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:52.584  1033  1033 D BluetoothHeadset: Proxy object connected
08-29 13:44:52.586  6238  6238 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:44:52.586  6238  6238 D PanProfile: Bluetooth service connected
,08-29 13:44:52.590  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 13:44:52.590  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 13:44:52.592  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-29 13:44:52.598  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.598  1941  2099 D LGBluetoothAPIService: Message: 1
08-29 13:44:52.598  1941  2099 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 13:44:52.598  1033  1095 D BluetoothManagerService: Message: 40
08-29 13:44:52.599  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 13:44:52.602  1941  2099 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 13:44:52.608  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:44:52.612  6389  6389 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.613  6389  6389 D BluetoothMapService: STATE_ON
08-29 13:44:52.613  6778  6778 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 13:44:52.614  6389  6389 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-29 13:44:52.619  6389  6389 V BluetoothMapService: Handler(): got msg=1
08-29 13:44:52.622  6238  6238 D BluetoothMap: Proxy object connected
08-29 13:44:52.622  6238  6238 D MapProfile: Bluetooth service connected
08-29 13:44:52.622  6238  6238 D BluetoothMap: getConnectedDevices()
08-29 13:44:52.622  6389  6389 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 13:44:52.624  6389  6389 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 13:44:52.624  6389  6406 V BluetoothMapService: getConnectedDevices()
08-29 13:44:52.627  6389  6788 D BluetoothMapMasInstance: MAS initSocket()
,08-29 13:44:52.629  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 13:44:52.629  1941  2099 D LGBluetoothAPIService: Message: 100
08-29 13:44:52.629  1941  2099 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 13:44:52.630  6023  6023 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 13:44:52.633  6389  6788 D BluetoothMapMasInstance:   masId = 00
08-29 13:44:52.633  6389  6788 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 13:44:52.633  6389  6788 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 13:44:52.633  6389  6788 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 13:44:52.635  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:52.636  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:52.637  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:52.637  6238  6238 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 13:44:52.639  6389  6788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:52.643  1033  1095 D BluetoothManagerService: Message: 30
,08-29 13:44:52.644  6389  6788 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 13:44:52.644  6389  6788 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 13:44:52.644  6389  6788 D BluetoothMapMasInstance: Accepting socket connection...
08-29 13:44:52.645  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:52.645  6389  6389 V BluetoothPbapService: Pbap Service onCreate
08-29 13:44:52.645  6389  6639 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:44:52.645  6389  6389 V BluetoothPbapService: Starting PBAP service
08-29 13:44:52.646  6389  6639 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 13:44:52.647  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:52.647  6389  6389 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 13:44:52.648  6389  6389 V BluetoothPbapService: Pbap Service onBind
08-29 13:44:52.651  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:52.652  6389  6389 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.652  6389  6389 V BluetoothPbapService: state: 12
08-29 13:44:52.653  6389  6389 V BluetoothPbapService: Handler(): got msg=1
08-29 13:44:52.653  6238  6238 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 13:44:52.653  6389  6389 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 13:44:52.654  6389  6792 V BluetoothPbapService: Pbap Service initSocket
08-29 13:44:52.655  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:52.656  1033  1095 D BluetoothManagerService: Message: 30
,08-29 13:44:52.656  6389  6792 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:52.657  6389  6792 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 13:44:52.657  6389  6792 V BluetoothPbapService: Succeed to create listening socket 
08-29 13:44:52.657  6389  6792 V BluetoothPbapService: Accepting socket connection...
08-29 13:44:52.662  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 13:44:52.664  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:44:52.669  6238  6238 D BluetoothPbap: Proxy object connected
08-29 13:44:52.669  6238  6238 D PbapServerProfile: Bluetooth service connected
08-29 13:44:52.669  6238  6238 D BluetoothA2dp: Proxy object connected
08-29 13:44:52.670  6389  6389 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-29 13:44:52.670  6389  6389 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.670  6389  6389 V BluetoothPbapReceiver: ***********state = 12
08-29 13:44:52.671  6238  6238 D A2dpProfile: Bluetooth service connected
08-29 13:44:52.672  6238  6238 D BluetoothHeadset: Proxy object connected
08-29 13:44:52.673  6238  6238 D HeadsetProfile: Bluetooth service connected
08-29 13:44:52.674  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:52.674  2158  2158 D c       : Getting all permits...
08-29 13:44:52.674  2158  2158 D a       : Opening database...
08-29 13:44:52.678  2158  2158 D a       : Opening database auth.proximity.permit_store...
08-29 13:44:52.679  2158  2158 D a       : Closing database...
08-29 13:44:52.684  6238  6238 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:52.690  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:44:52.692  6238  6238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:44:52.693  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:44:52.696  6389  6389 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 13:44:52.697  6389  6389 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-29 13:44:52.703  6389  6389 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-29 13:44:52.723  6389  6389 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:44:52.723  6389  6389 V BtOppService: onCreate
,08-29 13:44:52.727  6389  6389 V BluetoothOppNotification: send message
,08-29 13:44:52.730  6389  6389 V BtOppService: Starting RfcommListener
08-29 13:44:52.736  6389  6389 D BluetoothOppPreference: Dumping Names:  
08-29 13:44:52.736  6389  6389 D BluetoothOppPreference: {}
08-29 13:44:52.736  6389  6389 D BluetoothOppPreference: Dumping Channels:  
08-29 13:44:52.736  6389  6389 D BluetoothOppPreference: {}
08-29 13:44:52.737  6389  6389 V BtOppService: onStartCommand
08-29 13:44:52.737  6389  6797 V BtOppService: Deleted complete outbound shares, number =  0
08-29 13:44:52.739  6389  6800 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:44:52.740  6389  6800 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:44:52.740  6389  6797 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 13:44:52.741  6389  6797 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 13:44:52.741  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.742  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 13:44:52.742  6389  6797 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b7e905d on behalf of 
08-29 13:44:52.744  6389  6389 V BluetoothOppNotification: new notify threadi!
08-29 13:44:52.745  6389  6389 V BluetoothOppNotification: send delay message
08-29 13:44:52.745  6389  6389 V BtOppService: start RfcommListener
08-29 13:44:52.746  6389  6801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:44:52.748  6389  6801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29cdfdd2 on behalf of 
08-29 13:44:52.748  6389  6389 V BtOppService: RfcommListener started
08-29 13:44:52.749  6389  6389 V BtOppService: ContentObserver received notification
08-29 13:44:52.749  6389  6389 V BtOppService: ContentObserver received notification
08-29 13:44:52.749  6389  6801 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:44:52.750  6389  6801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:44:52.751  6389  6800 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32773ea3 on behalf of 
08-29 13:44:52.752  6389  6801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26ed85a0 on behalf of 
08-29 13:44:52.753  6389  6801 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:44:52.755  6389  6800 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:44:52.755  6389  6802 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 13:44:52.755  6389  6800 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:44:52.756  6389  6801 V BluetoothOppNotification: outbound notification was removed.
08-29 13:44:52.756  6389  6801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 13:44:52.757  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:52.760  6389  6800 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b98d559 on behalf of 
08-29 13:44:52.761  6389  6800 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:44:52.761  6389  6802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:52.761  6389  6801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cea251e on behalf of 
08-29 13:44:52.763  6389  6802 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-29 13:44:52.763  6389  6802 V BtOppRfcommListener: Started RFCOMM listener....
08-29 13:44:52.763  6389  6802 I BtOppRfcommListener: Accept thread started.
08-29 13:44:52.763  6389  6802 V BtOppRfcommListener: Accepting connection...
08-29 13:44:52.764  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:52.764  6389  6389 V BluetoothFtpService: Ftp Service onCreate
08-29 13:44:52.764  6389  6389 I BluetoothFtpService: Ftp Service onCreate
08-29 13:44:52.765  6389  6389 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:44:52.765  6389  6389 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.765  6389  6800 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 13:44:52.765  6389  6389 V BluetoothFtpService: Starting Listening on sockets
08-29 13:44:52.765  6389  6389 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:44:52.765  6389  6389 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:44:52.765  6389  6389 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:44:52.765  6389  6389 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.765  6389  6801 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:44:52.765  6389  6389 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 13:44:52.766  6389  6389 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:44:52.767  6389  6389 V BluetoothFtpService: Handler(): got msg=1
,08-29 13:44:52.770  6389  6389 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-29 13:44:52.770  6389  6389 V BluetoothFtpService: Ftp Service initSocket
08-29 13:44:52.773  6389  6801 V BluetoothOppNotification: inbound notification was removed.
08-29 13:44:52.773  6389  6801 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 13:44:52.775  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:52.774  6389  6801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23355bcc on behalf of 
08-29 13:44:52.775  6389  6389 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:52.776  6389  6389 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-29 13:44:52.777  6389  6389 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 13:44:52.779  6389  6803 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 13:44:52.812  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:52.813  6389  6389 V BluetoothSapService: Sap Service onCreate
,08-29 13:44:52.818  6389  6389 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:52.818  6389  6389 V BluetoothSapService: state: 12
08-29 13:44:52.819  6389  6389 V BluetoothSapService: Starting SAP server process
08-29 13:44:52.814  6804  6804 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:52.814  6804  6804 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:44:52.822  6389  6389 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 13:44:52.823  6389  6805 V BluetoothSapService: Sap Service initRfcommSocket
08-29 13:44:52.824  1033  1777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:52.825  6389  6805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:52.826  6389  6805 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-29 13:44:52.826  6389  6805 V BluetoothSapService: Succeed to create listening socket 
08-29 13:44:52.826  6389  6805 V BluetoothSapService: Accepting socket connection...
,08-29 13:44:52.830  6804  6804 V BT_SAP  : Event pipe created
08-29 13:44:52.830  6804  6804 V BT_SAP  : create_server_socket qcom.sap.server
08-29 13:44:52.830  6804  6804 V BT_SAP  : created socket fd 6
08-29 13:44:53.021  1033  1049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6807 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 13:44:53.029  1033  1049 I ActivityManager: Killing 6087:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 13:44:53.061   310  6565 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 13:44:53.061   310  6565 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-29 13:44:53.061   310  6565 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-29 13:44:53.063  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:44:53.063  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-29 13:44:53.063  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s687ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:53.063  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s687ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:53.063  1033  6512 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 13:44:53.071   310  6571 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-29 13:44:53.072  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:44:53.076   310  6572 D libc-netbsd: res_queryN name = europe.pool.ntp.org., class = 1, type = 1
,08-29 13:44:53.077  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:44:53.077  1033  6570 D LocSvc_java: requestTime failed
08-29 13:44:53.077  1033  6570 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,08-29 13:44:53.079  1033  1048 W libprocessgroup: failed to open /acct/uid_10080/pid_6087/cgroup.procs: No such file or directory
08-29 13:44:53.104  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 13:44:53.104  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-29 13:44:53.134  6807  6807 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-29 13:44:53.137  6807  6807 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-29 13:44:53.148  6807  6807 V DrmService: Service onCreate
08-29 13:44:53.148  6807  6807 D DrmService: Received new request = 2
,08-29 13:44:53.154  6807  6827 I DrmSntpClient: Start Sync process
08-29 13:44:53.154  6807  6827 D DrmSntpClient: Server : 0
08-29 13:44:53.223  1033  1049 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6828 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:53.228  6807  6827 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-29 13:44:53.229  6807  6807 D DrmService: Completed !! request = 2
08-29 13:44:53.229  6807  6807 D DrmService: Request count = 0
08-29 13:44:53.233  6807  6807 V DrmService: Service onDestroy
08-29 13:44:53.238  1033  1939 I ActivityManager: Killing 6108:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 13:44:53.301  1033  2010 W libprocessgroup: failed to open /acct/uid_10097/pid_6108/cgroup.procs: No such file or directory
08-29 13:44:53.336  6828  6828 I art     : Almond Protected OAT
,08-29 13:44:53.346  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:53.346  1033  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:53.372  1033  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-29 13:44:53.373  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 13:44:53.413  6828  6828 D WeatherApplication: removeAccount
,08-29 13:44:53.415  6828  6828 D WeatherApplication: Account.length = 0
08-29 13:44:53.415  6828  6828 E WeatherApplication: OPERATOR:OPEN
08-29 13:44:53.422  6828  6828 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:53
08-29 13:44:53.426  6828  6828 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 13:44:53.426  6828  6828 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:44:53.429  6828  6828 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 13:44:53.432  6828  6828 D WeatherAncestor: connectivity changed - connection : true
08-29 13:44:53.434  6828  6828 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 13:44:53.446  6828  6828 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:44:53.447  6828  6828 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:44:53.447  6828  6828 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 13:44:53.477  6828  6828 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-29 13:44:53.477  6828  6828 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:53
,08-29 13:44:53.539  1033  1574 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6846 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:53.541  1033  1574 I ActivityManager: Killing 6144:com.lge.eula/1000 (adj 15): empty #17
,08-29 13:44:53.601  1033  1776 W libprocessgroup: failed to open /acct/uid_1000/pid_6144/cgroup.procs: No such file or directory
,08-29 13:44:53.712   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-29 13:44:53.712   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 13:44:53.712   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:44:53.713  6846  6867 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-29 13:44:53.715   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:44:53.715   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 13:44:53.715   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:44:53.715  6846  6867 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 13:44:53.740   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:44:53.740   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 13:44:53.740   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:44:53.740  6846  6869 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-29 13:44:53.745   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:44:53.745   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 13:44:53.745   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:44:53.745  6846  6869 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 13:44:53.746  6389  6389 V BluetoothOppNotification: new notify threadi!
08-29 13:44:53.746  6389  6389 V BluetoothOppNotification: send delay message
08-29 13:44:53.747  6389  6872 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:44:53.749  6389  6872 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@344268b8 on behalf of 
08-29 13:44:53.750  6389  6872 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:44:53.753  6389  6872 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:44:53.754  6389  6872 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@327ed691 on behalf of 
08-29 13:44:53.755  6389  6872 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:44:53.759  6389  6872 V BluetoothOppNotification: outbound notification was removed.
08-29 13:44:53.760  6389  6872 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:44:53.765  6389  6872 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a87b9f6 on behalf of 
08-29 13:44:53.766  6389  6872 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:44:53.768  6389  6872 V BluetoothOppNotification: inbound notification was removed.
08-29 13:44:53.768  6389  6872 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 13:44:53.772  6389  6872 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b751f7 on behalf of 
08-29 13:44:53.981  6846  6846 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 13:44:53.993  6846  6846 I LibraryLoader: Loading: webviewchromium
08-29 13:44:53.997  6846  6846 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1504-1508)
,08-29 13:44:53.997  6846  6846 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:44:54.004  6846  6846 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24f1fb27}
08-29 13:44:54.006  6846  6846 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:44:54.006  6846  6846 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:44:54.020  6846  6846 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 13:44:54.021  6846  6846 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:44:54.039  6846  6846 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 13:44:54.040  6846  6846 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 13:44:54.041  6846  6846 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-29 13:44:54.048   315   315 V AudioPolicyService: registerClient() client 0xb558a8c0, uid 10093
,08-29 13:44:54.049  6846  6892 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 13:44:54.066  6846  6846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:44:54.066  6846  6846 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:44:54.066  6846  6846 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:44:54.066  6846  6846 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:44:54.066  6846  6846 I Adreno-EGL: Remote Branch: 
08-29 13:44:54.066  6846  6846 I Adreno-EGL: Local Patches: 
08-29 13:44:54.066  6846  6846 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:44:54.155  6846  6846 I NSApplication: Starting up...
,08-29 13:44:54.222  1033  1574 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6905 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:54.223  1033  1574 I ActivityManager: Killing 5908:com.android.vending/u0a44 (adj 15): empty #17
,08-29 13:44:54.290  1033  2010 W libprocessgroup: failed to open /acct/uid_10044/pid_5908/cgroup.procs: No such file or directory
,08-29 13:44:54.299  1033  1777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:44:54.299  1033  1777 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1804dcb5 mBinding = false
,08-29 13:44:54.314  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:44:54.315  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:44:54.315  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 13:44:54.316  1033  1095 D BluetoothManagerService: Message: 2
08-29 13:44:54.316  1033  1095 D BluetoothManagerService: Sending off request.
08-29 13:44:54.317  6389  6643 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 13:44:54.318  6389  6636 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 13:44:54.318  6389  6636 D BluetoothAdapterProperties: Setting state to 13
08-29 13:44:54.318  6389  6636 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:44:54.319  6389  6636 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:44:54.319  6389  6636 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 13:44:54.321  6389  6639 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:54.322  6389  6636 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 13:44:54.324  6389  6788 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 13:44:54.325  6389  6792 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:54.325  6389  6802 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:54.326  6389  6805 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:54.326  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 13:44:54.326  6389  6636 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:44:54.327  6389  6683 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 13:44:54.327  6389  6803 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:54.329  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:54.329  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:54.330  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:54.330  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA,_Deregister() called for PSM: 0x0017
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 13:44:54.332  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 13:44:54.333  6389  6683 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:44:54.334  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:54.334  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:54.334  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:54.334  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:54.334  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 13:44:54.335  6023  6023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:54.335  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:54.337  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.342  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:44:54.351  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:54.353  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:54.358  6389  6389 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.359  6389  6389 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:44:54.359  6389  6389 V BtOppService: Receiver DISABLED_ACTION 
08-29 13:44:54.359  6389  6389 V BluetoothMapService: Handler(): got msg=4
08-29 13:44:54.359  6389  6389 D BluetoothMapService: MAP Service closeService in
08-29 13:44:54.359  6389  6389 D BluetoothMapMasInstance: MAP Service shutdown
08-29 13:44:54.359  6389  6389 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,08-29 13:44:54.360  6389  6389 V BluetoothMapService: MAP Service closeService out
08-29 13:44:54.360  6389  6389 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:54.360  6389  6389 V BtOppRfcommListener: close mBtServerSocket
08-29 13:44:54.361  6389  6802 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:44:54.361  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 13:44:54.361  6389  6389 V BtOppRfcommListener: waiting for thread to terminate
08-29 13:44:54.362  6389  6389 V BtOppRfcommListener: done waiting for thread to terminate
08-29 13:44:54.363  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:44:54.366  6389  6389 V BtOppService: onDestroy
08-29 13:44:54.370  6389  6389 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-29 13:44:54.373  6389  6389 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:44:54.373  6389  6389 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.373  6389  6389 V BluetoothPbapReceiver: ***********state = 13
08-29 13:44:54.374  6238  6238 D DockEventReceiver: finishStartingService: stopping service
08-29 13:44:54.375  6389  6389 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 13:44:54.377  6389  6389 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.377  6389  6389 V BluetoothPbapService: state: 13
08-29 13:44:54.377  6389  6389 V BluetoothPbapService: Pbap Service closeService in
08-29 13:44:54.378  6389  6389 V BluetoothPbapService: successfully stopped pbap service
08-29 13:44:54.378  6389  6389 V BluetoothPbapService: Pbap Service closeService out
08-29 13:44:54.378  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:54.379  6238  6238 D BluetoothPbap: Proxy object disconnected
08-29 13:44:54.379  6238  6238 D PbapServerProfile: Bluetooth service disconnected
08-29 13:44:54.379  6389  6389 V BluetoothPbapService: Pbap Service onDestroy
08-29 13:44:54.379  6389  6389 V BluetoothPbapService: Pbap Service closeService in
08-29 13:44:54.379  6389  6389 V BluetoothPbapService: Pbap Service closeService out
08-29 13:44:54.379  6389  6389 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 13:44:54.390  6905  6905 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:44:54.393  6238  6238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 13:44:54.398  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:44:54.398  6238  6238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 13:44:54.405  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 13:44:54.408  6389  6389 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 13:44:54.408  6389  6389 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 13:44:54.409  6389  6389 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 13:44:54.412  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.412  6389  6389 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:44:54.414  6389  6389 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:44:54.414  6389  6389 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.414  6389  6389 V BluetoothFtpService: Ftp Service closeService
08-29 13:44:54.414  6389  6389 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 13:44:54.416  6389  6389 V BluetoothFtpService: successfully stopped ftp service
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 13:44:54.417  6389  6389 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:44:54.419  6389  6389 V BluetoothFtpService: Ftp Service onDestroy
08-29 13:44:54.419  6389  6389 V BluetoothFtpService: Ftp Service closeService
,08-29 13:44:54.422  6389  6389 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:54.422  6389  6389 V BluetoothSapService: state: 13
08-29 13:44:54.422  6389  6389 V BluetoothSapService: Stopping SAP server process
08-29 13:44:54.423  6389  6389 V BluetoothSapService: Sap Service closeSapService in
08-29 13:44:54.423  6389  6389 V BluetoothSapService: Close listen Socket : 
08-29 13:44:54.423  6389  6389 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:44:54.424  6389  6389 V BluetoothSapService: Close sapd  Socket : 
08-29 13:44:54.427  6389  6389 V BluetoothSapService: Sap Service closeSapService out
08-29 13:44:54.428  6389  6389 V BluetoothSapService: Sap Service onDestroy
08-29 13:44:54.428  6389  6389 V BluetoothSapService: Sap Service closeSapService in
08-29 13:44:54.428  6389  6389 V BluetoothSapService: Close listen Socket : 
08-29 13:44:54.428  6389  6389 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:44:54.428  6389  6389 V BluetoothSapService: Close sapd  Socket : 
08-29 13:44:54.429  6389  6389 V BluetoothSapService: Sap Service closeSapService out
08-29 13:44:54.669  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 13:44:54.678  3733  3755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 13:44:54.697  2158  2158 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:54.709  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 13:44:54.709  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.709  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:44:54.709  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:44:54.713  6606  6606 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:44:54.718  6606  6606 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7b04e6a
08-29 13:44:54.718  6606  6606 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:44:54.718  6606  6606 D AppUp4:CustFacade: isPhone : true
08-29 13:44:54.718  6606  6606 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:44:54.718  6606  6606 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:44:54.723  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:54.723  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:54.726  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:54.728  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:54.734  4267  6947 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:44:54.739  6658  6658 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 13:44:54.742  4267  6948 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.743  4267  6948 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:54.752  6658  6950 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:54.763  3387  3387 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:44:54.763  3387  3387 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.764  3387  3387 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 13:44:54.766  6347  6952 W FormManager: Network not available. Please check & try again.
08-29 13:44:54.768  6715  6715 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:44:54.768  6715  6715 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:44:54.772  6347  6954 V FormManager: Network unavailable.
08-29 13:44:54.778  6828  6828 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:54
,08-29 13:44:54.781  6347  6954 V FormManager: Network unavailable.
08-29 13:44:54.782  6828  6828 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:44:54.782  6828  6828 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:44:54.782  6828  6828 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:44:54.782  6828  6828 D WeatherAncestor: connectivity changed - connection : true
08-29 13:44:54.782  6828  6828 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d6c03f8
08-29 13:44:54.783  6828  6828 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:44:54.784  6828  6828 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:44:54.784  6828  6828 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 13:44:54.784  6828  6828 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:44:54.784  6828  6828 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:54
08-29 13:44:54.809  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 13:44:54.811  3733  3755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 13:44:54.825  2158  2158 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:54.834  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:44:54.834  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.834  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:44:54.834  6606  6606 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:44:54.836  6606  6606 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 13:44:54.839  6606  6606 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7b04e6a
08-29 13:44:54.839  6606  6606 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:44:54.839  6606  6606 D AppUp4:CustFacade: isPhone : true
08-29 13:44:54.840  6606  6606 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:44:54.840  6606  6606 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:44:54.843  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.844  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:44:54.845  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:54.848  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:44:54.855  6658  6658 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 13:44:54.858  4267  6955 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:44:54.860  4267  6956 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.861  4267  6956 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:44:54.877  6658  6957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:54.885  6347  6959 W FormManager: Network not available. Please check & try again.
,08-29 13:44:54.892  3387  3387 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:44:54.892  3387  3387 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:54.892  3387  3387 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 13:44:54.896  6715  6715 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:44:54.897  6715  6715 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:44:54.906  6347  6960 V FormManager: Network unavailable.
,08-29 13:44:54.910  6828  6828 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:54
,08-29 13:44:54.912  6828  6828 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 13:44:54.912  6828  6828 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 13:44:54.912  6828  6828 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 13:44:54.912  6347  6960 V FormManager: Network unavailable.
,08-29 13:44:54.913  6828  6828 D WeatherAncestor: connectivity changed - connection : true
08-29 13:44:54.913  6828  6828 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d6c03f8
08-29 13:44:54.914  6828  6828 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:44:54.914  6828  6828 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-29 13:44:54.914  6828  6828 D ForecastDataCache: 2 : Cache is up-to-date, count: 0,
08-29 13:44:54.914  6828  6828 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:44:54.914  6828  6828 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:44:54
08-29 13:44:55.253  6389  6639 D bt_hci_bdroid: cleanup
,08-29 13:44:55.271  6389  6741 I bt_userial_mct: exiting userial_read_thread
08-29 13:44:55.271  6389  6741 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 13:44:55.271  6389  6685 I bt_lpm  : LPM is already off!!!
08-29 13:44:55.272  6389  6683 W bt-btif : ag scb idx 1 not allocated
08-29 13:44:55.272  6389  6683 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:44:55.272  6389  6683 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:55.272  6389  6683 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:44:55.273  6389  6639 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 13:44:55.273  6389  6685 I bt_vendor: hw_epilog_process
08-29 13:44:55.274  6389  6639 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 13:44:55.274  6389  6639 D bt_userial_mct: userial_close
08-29 13:44:55.274  6389  6639 E bt_userial_mct: pthread_join() FAILED result:3
08-29 13:44:55.274  6389  6639 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 13:44:55.279  6389  6639 D bt_hci_bdroid: set_power 0
08-29 13:44:55.279  6389  6639 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 13:44:55.279  6389  6639 I bt_vendor: bluetooth satus is on,
08-29 13:44:55.279  6389  6639 I bt_vendor: bt-vendor : resetting BT status
08-29 13:44:55.279  6389  6639 I bt_vendor: Starting hciattach daemon
08-29 13:44:55.279  6389  6639 I bt_vendor: try to set false
08-29 13:44:55.280  6389  6639 I bt_vendor: Starting hciattach daemon
,08-29 13:44:55.280  6389  6639 I bt_vendor: try to set false
,08-29 13:44:55.288  6389  6639 I bt_vendor: cleanup
08-29 13:44:55.290  6389  6683 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 13:44:55.291  6389  6639 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:44:55.291  6389  6639 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 13:44:55.292  6389  6636 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 13:44:55.296  6389  6389 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:44:55.300  6389  6389 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:44:55.300  6389  6389 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:55.300  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.301  6389  6649 D HeadsetStateMachine: Exit Disconnected: -1
08-29 13:44:55.306  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:55.306  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:55.306  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:55.307  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:55.307  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 13:44:55.308  6389  6389 D A2dpService: Received stop request...Stopping profile...
,08-29 13:44:55.311  6389  6675 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:44:55.315  6389  6389 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 13:44:55.317  6389  6636 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:44:55.318  6389  6389 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 13:44:55.318  6389  6389 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:55.318  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.320  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:55.320  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 13:44:55.321  6389  6389 D HidService: Received stop request...Stopping profile...
08-29 13:44:55.321  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
,08-29 13:44:55.325  6389  6389 D HealthService: Received stop request...Stopping profile...
08-29 13:44:55.326  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.327  6389  6389 D HeadsetStateMachine: Unbinding service...
08-29 13:44:55.329  6389  6389 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:44:55.330  6389  6389 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:44:55.330  6389  6389 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:44:55.330  6389  6389 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:44:55.330  6389  6389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:55.330  6389  6389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:55.330  6389  6389 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:44:55.331  6389  6389 D PanService: Received stop request...Stopping profile...
08-29 13:44:55.331  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.332  6389  6389 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:44:55.336  6389  6389 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:44:55.336  6389  6389 D BtGatt.GattService: stop()
08-29 13:44:55.336  6389  6389 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 13:44:55.337  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.339  6389  6389 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:44:55.339  6389  6389 D BluetoothMapService: stop()
08-29 13:44:55.340  6389  6389 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 13:44:55.340  6389  6389 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 13:44:55.341  6389  6389 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6c03f8
08-29 13:44:55.342  6389  6389 I BluetoothA2dpServiceJni: cleanupNative
08-29 13:44:55.343  6389  6676 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:44:55.343  6389  6389 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:44:55.343  6389  6389 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 13:44:55.343  6389  6389 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:44:55.344  6389  6389 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:44:55.344  6389  6389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:44:55.344  6389  6389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:55.344  6389  6389 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:55.345  6389  6389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:55.345  6389  6389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 13:44:55.350  6389  6389 V BluetoothMapService: Handler(): got msg=4
08-29 13:44:55.350  6389  6389 D BluetoothMapService: MAP Service closeService in
08-29 13:44:55.350  6389  6389 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:44:55.351  6389  6389 V BluetoothMapService: MAP Service closeService out
08-29 13:44:55.352  6389  6636 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:44:55.352  6389  6636 D BluetoothAdapterProperties: Setting state to 10
08-29 13:44:55.352  6389  6636 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:44:55.353  6389  6389 D BluetoothMapService: cleanup()
08-29 13:44:55.353  6389  6389 D BluetoothMapService: MAP Service closeService in
08-29 13:44:55.353  6389  6389 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:44:55.353  6389  6389 V BluetoothMapService: MAP Service closeService out
08-29 13:44:55.354  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:44:55.354  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 13:44:55.355  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 13:44:55.355  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:55.355  6389  6636 I BluetoothAdapterState: Entering OffState
08-29 13:44:55.357  6238  6774 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:44:55.360  1852  4366 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:55.361  6238  6774 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:44:55.362  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:55.362  6238  6774 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:44:55.364  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:55.364  6238  6774 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:55.365  6238  6774 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:55.365  6238  6774 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:44:55.366  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:55.367  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 13:44:55.367  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 13:44:55.369  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 13:44:55.369  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 13:44:55.369  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1804dcb5 mBinding = false
,08-29 13:44:55.371  1033  1095 D BluetoothManagerService: Sending unbind request.
08-29 13:44:55.376  6389  6639 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 13:44:55.377  6389  6389 I GKI_LINUX: GKI_exit_task 1 done
08-29 13:44:55.377  6389  6389 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 13:44:55.378  6389  6389 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 13:44:55.378  6389  6389 I art     : --- WEIRD: removing null entry 248
08-29 13:44:55.378  6389  6389 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 13:44:55.378  6389  6389 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 13:44:55.379  6389  6389 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 13:44:55.380  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-29 13:44:55.384  6389  6389 I art     : System.exit called, status: 0
08-29 13:44:55.384  6389  6389 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 13:44:55.403   315  2185 V AudioFlinger: 6389 died, releasing its sessions
08-29 13:44:55.403   315  2185 V AudioFlinger:  pid 1852 @ 0
08-29 13:44:55.403   315  2185 V AudioFlinger:  pid 3387 @ 1
08-29 13:44:55.403   315  2185 V AudioFlinger:  pid 3387 @ 2
,08-29 13:44:55.407  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-29 13:44:55.407  1941  2099 D LGBluetoothAPIService: Message: 101
,08-29 13:44:55.407  1941  2099 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 13:44:55.407  1941  2099 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,08-29 13:44:55.408  1941  2099 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 13:44:55.415  6238  6238 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-29 13:44:55.549  1033  1939 I ActivityManager: Process com.android.bluetooth (pid 6389) has died
08-29 13:44:55.549  1033  1939 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-29 13:44:55.550  1033  1939 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-29 13:44:55.557  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:55.559  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 13:44:55.560  1941  2099 D LGBluetoothAPIService: Message: 2
08-29 13:44:55.560  1941  2099 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 13:44:55.563  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:55.565  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:55.571  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 13:44:55.571  6238  6238 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 13:44:55.572  1601  1601 D BluetoothAdapter: 290912578: getState() :  mService = null. Returning STATE_OFF
08-29 13:44:55.573  1601  1601 D BluetoothAdapter: 290912578: getState() :  mService = null. Returning STATE_OFF
08-29 13:44:55.573  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:44:55.627  1033  2032 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6991 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-29 13:44:55.629  6238  6238 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:55.713  6991  6991 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 13:44:55.714  6991  6991 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:44:55.714  6991  6991 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-29 13:44:55.715  6991  6991 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:44:55.736  6991  6991 D BluetoothAdapterApp: Loading JNI Library
,08-29 13:44:55.773  6991  6991 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@ca3f8e0 Instance Count = 1
,08-29 13:44:55.780  6991  6991 D BluetoothAdapterApp: onCreate
,08-29 13:44:55.806  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 13:44:55.806  6991  6991 D ProfileConfigQcom: Adding HeadsetService
,08-29 13:44:55.806  6991  6991 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 13:44:55.806  6991  6991 D ProfileConfigQcom: Adding A2dpService
08-29 13:44:55.806  6991  6991 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 13:44:55.807  6991  6991 D ProfileConfigQcom: Adding HidService
08-29 13:44:55.807  6991  6991 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 13:44:55.807  6991  6991 D ProfileConfigQcom: Adding HealthService
08-29 13:44:55.808  6991  6991 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 13:44:55.809  6991  6991 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 13:44:55.809  6991  6991 D ProfileConfigQcom: Adding PanService
08-29 13:44:55.809  6991  6991 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 13:44:55.810  6991  6991 D ProfileConfigQcom: Adding GattService
08-29 13:44:55.810  6991  6991 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 13:44:55.810  6991  6991 D ProfileConfigQcom: Adding BluetoothMapService
08-29 13:44:55.810  6991  6991 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 13:44:55.811  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-29 13:44:55.815  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:55.816  6991  6991 V BluetoothPbapReceiver: ***********state = 10
,08-29 13:44:55.818  6991  6991 V LGMDMManagerInternal: Create singleton instance
,08-29 13:44:55.907  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:55.915  6238  6238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 13:44:55.916  6991  6991 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 13:44:55.917  6991  6991 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 13:44:55.920  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 13:44:55.921  1941  2099 D LGBluetoothAPIService: Message: 100
08-29 13:44:55.921  1941  2099 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 13:44:55.923  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:44:55.925  6238  6238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:44:55.925  6238  6238 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 13:44:55.928  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:44:55.931  6991  6991 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 13:44:55.935  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:55.937  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 13:44:55.938  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-29 13:44:55.938  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 13:44:55.939  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:55.939  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 13:44:55.941  6327  6327 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 13:44:57.335  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:57.335  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:58.394  1033  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 13:44:58.760  6846  6870 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 13:44:59.684  1033  2010 I ActivityManager: Killing 6164:com.lge.bnr/1000 (adj 15): empty #17
,08-29 13:44:59.719  1033  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6164/cgroup.procs: No such file or directory
,08-29 13:45:00.004  1033  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1040820259, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-29 13:45:00.024  6310  6310 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-29 13:45:00.025  6310  6310 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1879
,08-29 13:45:00.052  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-29 13:45:00.070  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-29 13:45:00.070  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 13:45:00.070  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 13:45:00.070  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-29 13:45:00.080  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 13:45:00.080  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-29 13:45:00.081  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-29 13:45:00.083  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 13:45:00.147  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1040820259 [*alarm*], flags=0x0
,08-29 13:45:00.356  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:00.356  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bc48b6c added. We now have 6 listener(s)
,08-29 13:45:00.356  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:00.373  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:00.373  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16b27535 added. We now have 7 listener(s)
08-29 13:45:00.373  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:00.375  6023  6083 I System.out: IsBluetoothEnabled
08-29 13:45:00.376  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:00.376  1033  1648 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 13:45:00.376  1033  1095 D BluetoothManagerService: Message: 2
08-29 13:45:00.380  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:00.382  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:00.382  1033  1049 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 13:45:00.396  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:45:00.396  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:45:00.396  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-29 13:45:00.397  1033  1095 D BluetoothManagerService: Message: 1
08-29 13:45:00.397  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 13:45:00.422  1033  1095 D BluetoothManagerService: Message: 20
08-29 13:45:00.422  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb4d720:true
,08-29 13:45:00.426  6991  6991 D BluetoothAdapterState: make
08-29 13:45:00.431  6991  6991 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 13:45:00.431  6991  6991 I bluedroid-qcom: init
08-29 13:45:00.432  6991  7023 I BluetoothAdapterState: Entering OffState
08-29 13:45:00.432  6991  6991 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:45:00.433  6991  6991 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:45:00.433  6991  6991 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:45:00.433  6991  6991 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:45:00.433  6991  6991 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 13:45:00.435  6991  6991 I bluedroid-qcom: get_profile_interface socket
08-29 13:45:00.435  6991  6991 I bluedroid-qcom: get_profile_interface map_client
,08-29 13:45:00.439  6991  7027 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 13:45:00.442  6991  7027 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 13:45:00.434  7026  7026 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:00.434  7026  7026 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:00.451  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:45:00.451  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 13:45:00.457  7026  7026 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 13:45:00.457  7026  7026 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 13:45:00.457  7026  7026 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 13:45:00.459  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 13:45:00.459  1033  1095 D BluetoothManagerService: Message: 40
08-29 13:45:00.459  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 13:45:00.460  6991  7007 I bluedroid-qcom: config_hci_snoop_log
08-29 13:45:00.462  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 13:45:00.462  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 13:45:00.462  7026  7026 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-29 13:45:00.467  6991  7027 D BluetoothAdapterProperties: Name is: G3
08-29 13:45:00.471  7026  7026 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 13:45:00.471  7026  7026 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 13:45:00.475  6991  7023 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 13:45:00.475  6991  7023 D BluetoothAdapterProperties: Setting state to 11
08-29 13:45:00.475  6991  7023 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 13:45:00.478  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:45:00.478  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 13:45:00.478  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 13:45:00.482  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:00.483  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:45:00.486  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:00.488  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 13:45:00.497  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:45:00.497  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:00.497  6991  6991 V BluetoothPbapReceiver: ***********state = 11
08-29 13:45:00.502  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:45:00.523  6991  7023 I LGBluetoothServiceJni: classInitNative: succeeds
,08-29 13:45:00.534  6238  6238 D BluetoothPermissionRequest: onReceive
08-29 13:45:00.538  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:45:00.538  6991  7023 D BluetoothBondStateMachine: make
,08-29 13:45:00.541  6991  7023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.541  6991  7044 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:45:00.541  6991  7023 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 13:45:00.541  6991  7023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.541  6991  7023 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 13:45:00.542  6991  7023 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 13:45:00.546  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.549  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:00.551  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:45:00.551  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:45:00.551  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:45:00.551  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:00.551  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-29 13:45:00.556  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.559  6991  6991 D HeadsetService: Received start request. Starting profile...
08-29 13:45:00.560  6991  6991 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:45:00.560  6991  6991 D LGBluetoothHfpAdapter: Version 1.6
08-29 13:45:00.563  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 13:45:00.565  6991  6991 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:45:00.565  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.565  6991  6991 D HeadsetStateMachine: make
08-29 13:45:00.605  6991  6991 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:45:00.606  6991  6991 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:45:00.684  1033  2010 I art     : Explicit concurrent mark sweep GC freed 37579(1788KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.842ms total 115.210ms
,08-29 13:45:00.686  6991  6991 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:45:00.686  6991  6991 I bluedroid-qcom: get_profile_interface handsfree
08-29 13:45:00.689  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 13:45:00.692  6991  6991 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 13:45:00.693   315  1383 V AudioPolicyService: registerClient() client 0xb1023e40, uid 1002
08-29 13:45:00.694   315  2185 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:45:00.694   315  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:45:00.694   315  2185 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:45:00.694  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.694  6991  6991 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:45:00.695   315  1384 V AudioFlinger: registerClient() client 0xb1433658, pid 6991
08-29 13:45:00.696   315  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.696   315  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:45:00.697  3387  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.697  3387  3402 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:45:00.697  1033  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.697  1033  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:45:00.697  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.697  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:45:00.697  6991  7007 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.698  1601  3085 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:45:00.698  1601  3085 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:45:00.698   315  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-29 13:45:00.698   315  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:45:00.698  3387  3404 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:45:00.698  3387  3404 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:45:00.699  1601  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:45:00.699  1033  1776 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-29 13:45:00.699  1601  2101 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:45:00.699  1033  1776 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 13:45:00.699  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:45:00.699  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:45:00.699  6991  7007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 13:45:00.699  6991  7007 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:45:00.699  6991  7007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 13:45:00.699  6991  6991 V ToneGenerator: Create Track: 0xb4928a80
08-29 13:45:00.700  6991  6991 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 13:45:00.700  6991  6991 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 13:45:00.700   315  2184 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:45:00.700   315  2184 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:45:00.700   315  2184 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:45:00.700   315  2184 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:45:00.701  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.701   315  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:45:00.701   315  2185 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:45:00.701   315  2185 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 13:45:00.702   315  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:45:00.702   315  2185 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:45:00.702  6991  6991 V AudioSystem: getLatency() output 2, latency 50
08-29 13:45:00.702  6991  6991 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 13:45:00.702  6991  6991 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 13:45:00.703   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:45:00.703   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:45:00.703   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:45:00.703   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:45:00.703   315  1384 V AudioFlinger: createTrack() lSessionId: 23
08-29 13:45:00.704  6991  6991 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 13:45:00.704   315  1384 V AudioFlinger: acquiring 23 from 6991, for 6991
08-29 13:45:00.704   315  1384 V AudioFlinger:  added new entry for 23
08-29 13:45:00.704  6991  6991 V ToneGenerator: ToneGenerator INIT OK, time: 138216
08-29 13:45:00.704  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.705  6991  7046 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 13:45:00.705  6991  7046 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:45:00.705  6991  7046 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:45:00.705  6991  7046 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 13:45:00.706   315   315 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6991
08-29 13:45:00.707  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.708   315   315 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 13:45:00.708   315   315 V voice   : voice_set_parameters: enter: bt_samplera,te=8000
08-29 13:45:00.708   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 13:45:00.708   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 13:45:00.708   315   315 V voice   : voice_set_parameters: exit with code(0)
08-29 13:45:00.708   315   315 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 13:45:00.708   315   315 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 13:45:00.708   315   315 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 13:45:00.708   315   315 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 13:45:00.708   315   315 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 13:45:00.708   315   315 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 13:45:00.709  6991  7046 V ToneGenerator: ToneGenerator destructor
08-29 13:45:00.709  6991  7046 V ToneGenerator: stopTone
08-29 13:45:00.709  6991  7046 V ToneGenerator: Delete Track: 0xb4928a80
08-29 13:45:00.709  6991  6991 D A2dpService: Received start request. Starting profile...
08-29 13:45:00.710  6991  6991 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:45:00.710  6991  6991 V Avrcp   : make
08-29 13:45:00.710  6991  7046 V AudioTrack: ~AudioTrack, releasing session id from 6991 on behalf of 6991
08-29 13:45:00.711  6991  6991 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 13:45:00.711  6991  6991 I bluedroid-qcom: get_profile_interface avrcp
08-29 13:45:00.711   315  1384 V AudioFlinger: releasing 23 from 6991 for 6991
08-29 13:45:00.711   315  1384 V AudioFlinger:  decremented refcount to 0
08-29 13:45:00.711   315  1384 V AudioFlinger: purging stale effects
08-29 13:45:00.711   315  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 13:45:00.711   315  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 13:45:00.711   315  1259 V AudioPolicyService: AudioCommandThread() waking up
08-29 13:45:00.711   315  1384 V AudioFlinger: PlaybackThread::Track destructor
08-29 13:45:00.711   315  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 13:45:00.711   315  1259 V AudioPolicyManager: releaseOutput() 2
08-29 13:45:00.712   315  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 13:45:00.712   315  1384 V AudioFlinger: removeClient_l() pid 6991, calling pid 315
08-29 13:45:00.714  6991  7023 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:45:00.724  6991  6991 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 13:45:00.725  6991  6991 E AudioManager: No RCC entry present to update
08-29 13:45:00.725  6991  6991 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 13:45:00.727  6991  6991 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 13:45:00.728  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 13:45:00.728  6991  6991 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 13:45:00.732  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 13:45:00.759  6991  7023 V LGMDMManager: Create singleton instance
,08-29 13:45:00.762  6991  7023 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:45:00.853  1033  2032 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:45:00.854  1033  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:45:00.925  1033  1920 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 13:45:00.931  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 13:45:00.935  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:45:00.935  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:45:00.936  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 13:45:00.936  6991  6991 I BluetoothA2dpServiceJni: classInitNative
08-29 13:45:00.936  6991  6991 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:45:00.936  6991  6991 D A2dpStateMachine: make
08-29 13:45:00.942  6991  6991 I bluedroid-qcom: get_profile_interface a2dp
,08-29 13:45:00.943  6991  7052 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 13:45:00.945  6991  6991 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:45:00.945  6991  6991 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 13:45:00.946  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.947  6991  6991 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:45:00.948  6991  6991 D HidService: Received start request. Starting profile...
08-29 13:45:00.948  6991  6991 I bluedroid-qcom: get_profile_interface hidhost
08-29 13:45:00.948  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.949  6991  7051 D A2dpStateMachine: Enter Disconnected: -2
08-29 13:45:00.949  6991  6991 D HeadsetStateMachine: Proxy object connected
08-29 13:45:00.949  6991  6991 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 13:45:00.949  6991  6991 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 13:45:00.951  6991  6991 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:45:00.952  6991  6991 D HealthService: Received start request. Starting profile...
08-29 13:45:00.955  6991  6991 I bluedroid-qcom: get_profile_interface health
08-29 13:45:00.955  6991  6991 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:45:00.956  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.956  6991  6991 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:45:00.958  6991  6991 D PanService: Received start request. Starting profile...
08-29 13:45:00.958  6991  6991 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:45:00.958  6991  6991 I bluedroid-qcom: get_profile_interface pan
08-29 13:45:00.965  6991  6991 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 13:45:00.965  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.966  6991  6991 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 13:45:00.969  6991  6991 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:45:00.970  6991  6991 D BtGatt.GattService: Received start request. Starting profile...
,08-29 13:45:00.970  6991  6991 D BtGatt.GattService: start()
08-29 13:45:00.971  6991  6991 I bluedroid-qcom: get_profile_interface gatt
08-29 13:45:00.972  6991  6991 D BtGatt.AdvertiseManager: advertise manager created
08-29 13:45:00.978  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.979  6991  7046 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 13:45:00.979  6991  7046 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:45:00.979  6991  7046 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 13:45:00.985  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 13:45:00.989  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:00.990  6991  6991 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 13:45:00.992  6991  6991 V BluetoothMapService: BluetoothMapBinder()
08-29 13:45:00.993  6991  6991 D BluetoothMapService: Received start request. Starting profile...
08-29 13:45:00.994  6991  6991 D BluetoothMapService: start()
08-29 13:45:01.000  6991  6991 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-29 13:45:01.000  6991  6991 D BluetoothMapEmailAppObserver: createReceiver()
08-29 13:45:01.003  6991  6991 D BluetoothMapEmailAppObserver: initObservers()
08-29 13:45:01.003  6991  6991 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 13:45:01.022  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
,08-29 13:45:01.027  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 13:45:01.031  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:45:01.034  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:45:01.035  6991  6991 V PanService: [BTUI] SIM Extra State :ABSENT
,08-29 13:45:01.038  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:45:01.042  6991  6991 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 13:45:01.042  6991  6991 V BluetoothMapService: Handler(): got msg=1
,08-29 13:45:01.044  6991  7023 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 13:45:01.044  6991  7023 I bluedroid-qcom: enable
08-29 13:45:01.044  6991  7063 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 13:45:01.045  6991  7063 I bt-btu  : btu_task pending for preload complete event
08-29 13:45:01.045  6991  7023 I bt_hci_bdroid: init
08-29 13:45:01.047  6991  7023 I bt_vendor: bt-vendor : init
08-29 13:45:01.048  6991  7023 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:45:01.048  6991  7023 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:45:01.048  6991  7023 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 13:45:01.048  6991  7023 D bt_userial_mct: userial_init
,08-29 13:45:01.049  6991  7023 D bt_hci_bdroid: set_power 1
08-29 13:45:01.049  6991  7023 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 13:45:01.049  6991  7023 I bt_vendor: Starting hciattach daemon
08-29 13:45:01.049  6991  7023 I bt_vendor: try to set true
,08-29 13:45:01.044  7066  7066 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:01.044  7066  7066 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:01.093  7067  7067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 13:45:01.238  7073  7073 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 13:45:01.255  7074  7074 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:45:01.293  7079  7079 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:45:01.306  7080  7080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-29 13:45:01.318  7081  7081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:45:01.331  7082  7082 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-29 13:45:01.370  7084  7084 I libmdmdetect: ESOC framework not supported
,08-29 13:45:01.372  7084  7084 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 13:45:01.380  7084  7084 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 13:45:01.380  7084  7084 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 13:45:01.380  7084  7084 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 13:45:01.380  7084  7084 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 13:45:01.380  7084  7084 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 13:45:01.380  7084  7084 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 13:45:01.380  7084  7084 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 13:45:01.415  7084  7085 E QC-QMI  : qmi_client [7084] 15: failed to locate client data
08-29 13:45:01.416   489   489 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 13:45:01.416   489   489 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 13:45:01.473  7086  7086 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 13:45:01.490  7087  7087 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:45:01.506  6991  7023 I bt_vendor: bluetooth satus is on
,08-29 13:45:01.506  6991  7023 D bt_hci_bdroid: preload
08-29 13:45:01.507  6991  7065 D bt_userial_mct: userial_open(port:0)
08-29 13:45:01.507  6991  7065 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 13:45:01.511  6991  7065 I bt_vendor: Done intiailizing UART
,08-29 13:45:01.511  6991  7065 I bt_vendor: Done intiailizing UART
,08-29 13:45:01.512  6991  7065 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-29 13:45:01.512  6991  7065 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 13:45:01.512  6991  7089 D bt_userial_mct: Entering userial_read_thread(),
08-29 13:45:01.512  6991  7063 I bt-btu  : btu_task received preload complete event
08-29 13:45:01.513  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 13:45:01.513  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-29 13:45:01.515  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003,
,08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_L2CAP,
,08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_A2D,
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_BTM,
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:45:01.518  6991  7063 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:45:01.519  6991  7063 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:45:01.519  6991  7063 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 13:45:01.519  6991  7063 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:45:01.519  6991  7063 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:45:01.519  6991  7063 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 13:45:01.617  6991  7063 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 13:45:01.637  6991  7063 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b2061 
08-29 13:45:01.637  6991  7063 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b2061 
08-29 13:45:01.664  6991  7027 E bt-btif : Calling BTA_HhEnable
08-29 13:45:01.664  6991  7027 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 13:45:01.665  6991  7027 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 13:45:01.669  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 13:45:01.669  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 13:45:01.669  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 13:45:01.669  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 13:45:01.669  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 13:45:01.670  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:45:01.670  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:45:01.671  6991  7027 D BluetoothAdapterProperties: Name is: G3
08-29 13:45:01.672  6991  7027 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:45:01.673  6991  7027 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:45:01.673  6991  7027 D bt_hci_bdroid: postload
08-29 13:45:01.673  6991  7065 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:45:01.674  6991  7065 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:45:01.675  6991  7063 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 13:45:01.675  6991  7065 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:45:01.676  6991  7027 D bte_conf: Device ID record 1 : primary
,08-29 13:45:01.676  6991  7027 D bte_conf:   vendorId            = 00c4
08-29 13:45:01.676  6991  7027 D bte_conf:   vendorIdSource      = 0001
08-29 13:45:01.676  6991  7027 D bte_conf:   product             = 13a1
08-29 13:45:01.676  6991  7027 D bte_conf:   version             = 1000
08-29 13:45:01.676  6991  7027 D bte_conf:   clientExecutableURL = 
08-29 13:45:01.676  6991  7027 D bte_conf:   serviceDescription  = 
08-29 13:45:01.676  6991  7027 D bte_conf:   documentationURL    = 
08-29 13:45:01.676  6991  7027 D bte_conf: bte_load_did_conf no section named DID2.
08-29 13:45:01.680  6991  7023 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 13:45:01.680  6991  7023 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:45:01.680  6991  7023 D BluetoothAdapterProperties: State =  11
08-29 13:45:01.680  6991  7023 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 13:45:01.680  6991  7023 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 13:45:01.681  6991  7023 D BluetoothAdapterProperties: Setting state to 12
08-29 13:45:01.681  6991  7023 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:45:01.686  6991  7027 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:45:01.684  7094  7094 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:01.689  1033  1095 D BluetoothManagerService: Message: 60
08-29 13:45:01.689  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 13:45:01.689  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 13:45:01.689  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:45:01.691  6991  7063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:45:01.691  6991  7063 W bt-smp  : Plain text(LSB ~ MSB) = fc 5b 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:45:01.691  6991  7063 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f ff 84 f4 70 28 df ed 6e 83 74 62 5f 00 b3 8a 
08-29 13:45:01.691  6991  7065 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:45:01.691  6991  7063 W bt-btm  : Stopping oneshot timer
08-29 13:45:01.692  6991  7027 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:45:01.684  7094  7094 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:01.698  6991  7089 E bt_mct  : hci lib postload completed
,08-29 13:45:01.714  6991  7023 I BluetoothAdapterState: Entering On State
,08-29 13:45:01.726  6991  7023 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 13:45:01.726  6991  7023 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 13:45:01.726  6991  7023 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 13:45:01.729  6991  7023 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-29 13:45:01.731  6991  7063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:45:01.731  6991  7063 W bt-smp  : Plain text(LSB ~ MSB) = 8f 47 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:45:01.731  6991  7063 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 2c d3 83 6e a5 3a 0b 7a f2 ec 11 63 dd 5c 24 
08-29 13:45:01.732  6991  7063 W bt-btm  : Stopping oneshot timer
08-29 13:45:01.736  6991  7027 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:45:01.736  6991  7027 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 13:45:01.737  1033  1033 D BluetoothA2dp: Proxy object connected
08-29 13:45:01.746  6991  7063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:45:01.746  6991  7063 W bt-smp  : Plain text(LSB ~ MSB) = e2 03 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:45:01.746  6991  7063 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 18 af 61 46 71 57 43 5a 9a 0d f0 89 6b 70 d7 
,08-29 13:45:01.749  6991  7063 W bt-btm  : Stopping oneshot timer
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:01.753  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:45:01.759  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:01.762  6991  7063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:45:01.762  6991  7063 W bt-smp  : Plain text(LSB ~ MSB) = 9e 0f 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:45:01.762  6991  7063 W bt-smp  : Encrypted text(LSB ~ MSB) = 17 d6 65 e9 c8 10 29 fe c0 58 a2 6e 62 80 83 c7 
08-29 13:45:01.762  6991  7063 W bt-btm  : Stopping oneshot timer
08-29 13:45:01.767  6991  7023 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 13:45:01.767  6238  6774 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:45:01.775  6991  7063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:45:01.775  6991  7063 W bt-smp  : Plain text(LSB ~ MSB) = 3d 38 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:45:01.775  6991  7063 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 db 23 f9 17 d6 5f 10 c7 42 a5 a0 67 c7 6f d7 
,08-29 13:45:01.777  6991  7063 W bt-btm  : Stopping oneshot timer
08-29 13:45:01.784  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:01.798  1852  1852 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.801  6238  6774 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:45:01.801  6238  6774 D BluetoothPan: onBluetoothStateChange call bindService
08-29 13:45:01.826  1852  4365 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:45:01.831  6238  6238 D BluetoothInputDevice: Proxy object connected
08-29 13:45:01.831  7099  7099 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 13:45:01.831  6238  6238 D HidProfile: Bluetooth service connected
08-29 13:45:01.836  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.836  6238  6238 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:45:01.836  6238  6238 D PanProfile: Bluetooth service connected
08-29 13:45:01.837  6238  6774 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:45:01.840  1852  4366 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:45:01.842  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.843  6238  6255 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:01.845  6238  6238 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.845  6238  6238 D HeadsetProfile: Bluetooth service connected
08-29 13:45:01.845  6238  6774 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:45:01.847  6238  6255 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:45:01.847  6238  6238 D BluetoothA2dp: Proxy object connected
08-29 13:45:01.847  6238  6238 D A2dpProfile: Bluetooth service connected
08-29 13:45:01.849  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:01.849  1033  1033 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.850  6238  6238 D BluetoothMap: Proxy object connected
08-29 13:45:01.850  6238  6238 D MapProfile: Bluetooth service connected
08-29 13:45:01.850  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 13:45:01.850  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 13:45:01.851  6238  6238 D BluetoothMap: getConnectedDevices()
08-29 13:45:01.852  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.852  1941  2099 D LGBluetoothAPIService: Message: 1
08-29 13:45:01.852  1941  2099 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-29 13:45:01.852  1941  2099 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 13:45:01.852  1941  2099 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 13:45:01.856  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:45:01.858  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:01.859  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 13:45:01.859  1033  1095 D BluetoothManagerService: Message: 40
08-29 13:45:01.859  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 13:45:01.859  6991  6991 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.859  6991  6991 D BluetoothMapService: STATE_ON
08-29 13:45:01.859  6991  6991 V BluetoothMapService: Handler(): got msg=1
08-29 13:45:01.860  6991  6991 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 13:45:01.861  6991  7116 D BluetoothMapMasInstance: MAS initSocket()
08-29 13:45:01.862  6991  7116 D BluetoothMapMasInstance:   masId = 00
08-29 13:45:01.862  6991  7116 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 13:45:01.862  6991  7116 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 13:45:01.862  6991  7116 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 13:45:01.863  6991  7047 V BluetoothMapService: getConnectedDevices()
08-29 13:45:01.864  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:01.866  6991  7116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:01.868  6991  7116 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,08-29 13:45:01.868  6991  7116 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-29 13:45:01.868  6991  7116 D BluetoothMapMasInstance: Accepting socket connection...
08-29 13:45:01.869  6991  7027 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:45:01.869  6991  7027 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 13:45:01.871  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:01.875  6238  6238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 13:45:01.876  6238  6238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:45:01.884  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:01.885  6991  6991 V BluetoothPbapService: Pbap Service onCreate
,08-29 13:45:01.885  6991  6991 V BluetoothPbapService: Starting PBAP service
08-29 13:45:01.886  6991  6991 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 13:45:01.886  6991  6991 V BluetoothPbapService: Pbap Service onBind
08-29 13:45:01.888  6991  6991 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.888  6991  6991 V BluetoothPbapService: state: 12
08-29 13:45:01.888  6238  6238 D DockEventReceiver: finishStartingService: stopping service
08-29 13:45:01.888  6991  6991 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:45:01.888  6991  6991 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.888  6991  6991 V BluetoothPbapReceiver: ***********state = 12
08-29 13:45:01.890  6238  6238 D BluetoothPbap: Proxy object connected
08-29 13:45:01.890  6238  6238 D PbapServerProfile: Bluetooth service connected
08-29 13:45:01.891  6991  6991 V BluetoothPbapService: Handler(): got msg=1
08-29 13:45:01.891  6991  6991 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 13:45:01.893  6991  7118 V BluetoothPbapService: Pbap Service initSocket
08-29 13:45:01.894  2158  2158 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:45:01.894  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:01.894  2158  2158 D c       : Getting all permits...
08-29 13:45:01.894  2158  2158 D a       : Opening database...
08-29 13:45:01.895  6991  7118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:01.896  6991  7118 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 13:45:01.896  6991  7118 V BluetoothPbapService: Succeed to create listening socket 
08-29 13:45:01.896  6991  7118 V BluetoothPbapService: Accepting socket connection...
,08-29 13:45:01.898  2158  2158 D a       : Opening database auth.proximity.permit_store...
08-29 13:45:01.900  2158  2158 D a       : Closing database...
08-29 13:45:01.910  6238  6238 D BluetoothPermissionRequest: onReceive
,08-29 13:45:01.913  6238  6238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:45:01.915  6238  6238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:45:01.918  6991  6991 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 13:45:01.920  6991  6991 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 13:45:01.926  6991  6991 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 13:45:01.947  6991  6991 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 13:45:01.947  6991  6991 V BtOppService: onCreate
,08-29 13:45:01.951  6991  6991 V BluetoothOppNotification: send message
08-29 13:45:01.954  6991  6991 V BtOppService: Starting RfcommListener
08-29 13:45:01.957  6991  6991 D BluetoothOppPreference: Dumping Names:  
08-29 13:45:01.958  6991  6991 D BluetoothOppPreference: {}
08-29 13:45:01.958  6991  6991 D BluetoothOppPreference: Dumping Channels:  
08-29 13:45:01.958  6991  6991 D BluetoothOppPreference: {}
08-29 13:45:01.958  6991  6991 V BtOppService: onStartCommand
08-29 13:45:01.959  6991  7126 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:45:01.962  6991  7123 V BtOppService: Deleted complete outbound shares, number =  0
08-29 13:45:01.962  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:45:01.962  6991  6991 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:45:01.965  6991  7123 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 13:45:01.966  6991  6991 V BluetoothOppNotification: new notify threadi!
08-29 13:45:01.967  6991  7123 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 13:45:01.967  6991  6991 V BluetoothOppNotification: send delay message
08-29 13:45:01.968  6991  6991 V BtOppService: start RfcommListener
08-29 13:45:01.969  6991  7123 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b7e905d on behalf of 
08-29 13:45:01.971  6991  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:45:01.973  6991  6991 V BtOppService: RfcommListener started
08-29 13:45:01.974  6991  6991 V BtOppService: ContentObserver received notification
08-29 13:45:01.975  6991  7128 V BtOppRfcommListener: Starting RFCOMM listener....
,08-29 13:45:01.976  6991  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29cdfdd2 on behalf of 
08-29 13:45:01.976  1033  1777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:01.976  6991  7127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:45:01.977  6991  7128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:01.979  6991  7128 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 13:45:01.979  6991  7126 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:45:01.979  6991  7126 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:45:01.979  6991  7128 V BtOppRfcommListener: Started RFCOMM listener....
08-29 13:45:01.979  6991  7128 I BtOppRfcommListener: Accept thread started.
08-29 13:45:01.979  6991  7128 V BtOppRfcommListener: Accepting connection...
08-29 13:45:01.981  6991  7127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32773ea3 on behalf of 
08-29 13:45:01.981  6991  7126 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26ed85a0 on behalf of 
08-29 13:45:01.983  6991  7126 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:45:01.983  6991  7127 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:45:01.984  6991  7126 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 13:45:01.984  6991  7127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:45:01.986  6991  7127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b98d559 on behalf of 
08-29 13:45:01.987  6991  7127 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 13:45:01.990  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:01.990  6991  6991 V BluetoothFtpService: Ftp Service onCreate
,08-29 13:45:01.990  6991  6991 I BluetoothFtpService: Ftp Service onCreate
08-29 13:45:01.990  6991  6991 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:45:01.990  6991  6991 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.990  6991  6991 V BluetoothFtpService: Starting Listening on sockets
08-29 13:45:01.991  6991  6991 V BtOppService: ContentObserver received notification
08-29 13:45:01.991  6991  7127 V BluetoothOppNotification: outbound notification was removed.
08-29 13:45:01.991  6991  7127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 13:45:01.991  6991  6991 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:45:01.992  6991  7127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a3521ff on behalf of 
08-29 13:45:01.994  6991  6991 V BluetoothFtpService: Handler(): got msg=1
08-29 13:45:01.995  6991  7127 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:45:01.995  6991  6991 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 13:45:01.996  6991  6991 V BluetoothFtpService: Ftp Service initSocket
08-29 13:45:01.998  6991  7130 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:45:01.998  6991  7130 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 13:45:02.000  1033  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:45:02.001  6991  7127 V BluetoothOppNotification: inbound notification was removed.
08-29 13:45:02.001  6991  7127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 13:45:02.001  6991  6991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:02.002  6991  7130 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23355bcc on behalf of 
08-29 13:45:02.002  6991  6991 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-29 13:45:02.003  6991  6991 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 13:45:02.005  6991  7131 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 13:45:02.007  6991  7130 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:45:02.008  6991  7127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b786e15 on behalf of 
08-29 13:45:02.008  6991  7130 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 13:45:02.021  6991  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a0370d1
08-29 13:45:02.021  6991  6991 V BluetoothSapService: Sap Service onCreate
08-29 13:45:02.023  6991  6991 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:02.023  6991  6991 V BluetoothSapService: state: 12
,08-29 13:45:02.023  6991  6991 V BluetoothSapService: Starting SAP server process
,08-29 13:45:02.014  7132  7132 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:02.014  7132  7132 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:02.027  6991  6991 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 13:45:02.028  6991  7133 V BluetoothSapService: Sap Service initRfcommSocket
08-29 13:45:02.029  1033  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:02.030  6991  7133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:02.032  6991  7133 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 13:45:02.032  6991  7133 V BluetoothSapService: Succeed to create listening socket 
08-29 13:45:02.032  6991  7133 V BluetoothSapService: Accepting socket connection...
08-29 13:45:02.037  7132  7132 V BT_SAP  : Event pipe created
08-29 13:45:02.037  7132  7132 V BT_SAP  : create_server_socket qcom.sap.server
08-29 13:45:02.037  7132  7132 V BT_SAP  : created socket fd 6
,08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:02.424  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:02.437  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:45:02.447  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:02.447  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25b03dca added. We now have 8 listener(s)
08-29 13:45:02.447  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:02.455  1033  1975 D WifiServiceImplEx: setWifiEnabled: false pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:45:02.456  1033  1975 D WifiService: setWifiEnabled: false pid=6023, uid=10118
08-29 13:45:02.456  1033  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:45:02.461  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:02.465  1033  2028 D WifiServiceImplEx: setWifiEnabled: true pid=6023, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:45:02.465  1033  2028 D WifiService: setWifiEnabled: true pid=6023, uid=10118
08-29 13:45:02.465  1033  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:45:02.491  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 13:45:02.491  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 13:45:02.491  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-29 13:45:02.493  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-29 13:45:02.493  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 13:45:02.496  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini],
08-29 13:45:02.496  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:45:02.496  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 13:45:02.496  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:45:02.496  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 13:45:02.496  1033  1537 E WifiHW  : unknown target_country: EU , set to default
,08-29 13:45:02.496  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
,08-29 13:45:02.496  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 13:45:02.496  1033  1537 I WifiUtil: gEnableBmps=1
08-29 13:45:02.970  6991  6991 V BluetoothOppNotification: new notify threadi!
,08-29 13:45:02.971  6991  6991 V BluetoothOppNotification: send delay message
,08-29 13:45:02.992  6991  7152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:45:02.996  6991  7152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@327ed691 on behalf of 
08-29 13:45:02.996  6991  7152 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:45:02.998  6991  7152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:45:02.999  6991  7152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a87b9f6 on behalf of 
08-29 13:45:02.999  6991  7152 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 13:45:03.003  6991  7152 V BluetoothOppNotification: outbound notification was removed.
,08-29 13:45:03.003  6991  7152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:45:03.005  6991  7152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b751f7 on behalf of 
08-29 13:45:03.005  6991  7152 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:45:03.008  6991  7152 V BluetoothOppNotification: inbound notification was removed.
08-29 13:45:03.008  6991  7152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 13:45:03.009  6991  7152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5115864 on behalf of 
08-29 13:45:03.064   310   890 D SoftapController: Softap fwReload - Ok
,08-29 13:45:03.075  1033  1537 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (575ms)
08-29 13:45:03.077   310   890 D CommandListener: Setting iface cfg
08-29 13:45:03.077   310   890 D CommandListener: Trying to bring down wlan0
,08-29 13:45:03.081   310   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:45:03.086  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:45:03.086  1033  1095 D Tethering: InitialState.processMessage what=4
08-29 13:45:03.099   310  7154 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 13:45:03.117  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:45:03.122  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 13:45:03.122  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:45:03.136  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:45:03.136  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:45:03.136  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 13:45:03.134  7155  7155 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:03.142  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:03.134  7155  7155 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:03.149  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 13:45:03.184  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:03.185  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 13:45:03.192  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 13:45:03.192  1033  1537 D WifiMonitor: connecting to supplicant
08-29 13:45:03.198  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:45:03.199  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 13:45:03.199  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:45:03.199  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:45:03.200  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:45:03.201  7155  7155 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 13:45:03.201  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:45:03.201  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:45:03.201  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:45:03.201  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:45:03.201  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:45:03.201  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:45:03.204  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:45:03.204  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:45:03.204  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:45:03.204  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:45:03.204  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:45:03.205  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:45:03.205  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:45:03.205  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:45:03.205  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:45:03.205  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:45:03.205  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 13:45:03.217  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:45:03.220  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:45:03.228  6347  7173 W FormManager: Network not available. Please check & try again.
08-29 13:45:03.234  7155  7155 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:45:03.235  6347  7174 V FormManager: Network unavailable.
08-29 13:45:03.235  7155  7155 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 13:45:03.239  6347  7174 V FormManager: Network unavailable.
,08-29 13:45:03.240  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:45:03.315  7155  7155 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:45:03.407  7155  7155 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 13:45:03.414  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 13:45:03.414  7155  7155 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 13:45:03.417  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:45:03.419  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 13:45:03.419  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 13:45:03.419  1033  7177 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 13:45:03.419  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 13:45:03.419  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 13:45:03.419  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:45:03.420  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:45:03.420  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:45:03.421  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:45:03.422  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-29 13:45:03.423  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:03.425  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:03.426  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:03.427  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 13:45:03.427  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 13:45:03.428  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 13:45:03.428  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 13:45:03.428  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 13:45:03.429  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:45:03.429  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:45:03.429  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:45:03.429  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 13:45:03.430  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-29 13:45:03.430  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
08-29 13:45:03.430  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 13:45:03.431  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 13:45:03.438  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-29 13:45:03.448  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-29 13:45:03.449  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:45:03.449  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
,08-29 13:45:03.449  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 13:45:03.450  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-29 13:45:03.450  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 13:45:03.450  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-29 13:45:03.450  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 13:45:03.451  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 13:45:03.452  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 13:45:03.452  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 13:45:03.452  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 13:45:03.453  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:45:03.453  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 13:45:03.453  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 13:45:03.453  1033  1537 D WifiNative-HAL: Setting external_sim to 1
08-29 13:45:03.453  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 13:45:03.454  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 13:45:03.454  1033  1537 I WifiNative-HAL: startHal
08-29 13:45:03.454  1033  1537 D wifi    : setting scan oui 0x95278fe0
08-29 13:45:03.454  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:45:03.454  1033  1537 I WifiNative-HAL: startHal
08-29 13:45:03.454  1033  1537 D wifi    : setting scan oui 0x95278fe0
08-29 13:45:03.455  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 13:45:03.455  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 13:45:03.455  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 13:45:03.455  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 13:45:03.456  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 13:45:03.456  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-29 13:45:03.456  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:45:03.456  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:45:03.456  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 13:45:03.456  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-29 13:45:03.457  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 13:45:03.457  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:45:03.457  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:45:03.457  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.457  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.457  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-29 13:45:03.457  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:45:03.457  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:45:03.457  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.457  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.458  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 13:45:03.458  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:45:03.458  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-29 13:45:03.458  7155  7155 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 13:45:03.458  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 13:45:03.458  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:45:03.459  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:45:03.459  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:45:03.460  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:03.460  1033  1537 E WifiNative: : [140,956,849 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 13:45:03.460  1033  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 13:45:03.460  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
08-29 13:45:03.460  1033  1537 D WifiNative-wlan0: doString: [STATUS]
08-29 13:45:03.461  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:45:03.461  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 13:45:03.461  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:45:03.461  1033  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:45:03.461  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:45:03.462  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:45:03.462  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.464   310   890 D CommandListener: Setting iface cfg
08-29 13:45:03.464   310   890 D CommandListener: Trying to bring up p2p0
08-29 13:45:03.464  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:45:03.464  1033  1536 D LGWifiP2pService: P2pEnablingState
08-29 13:45:03.464  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.464  1033  1536 D LGWifiP2pService: P2p socket connection successful
08-29 13:45:03.464  1033  1536 D LGWifiP2pService: P2pEnabledState
08-29 13:45:03.468  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 13:45:03.468  1941  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 13:45:03.468  1941  2282 D WfdsService: Set the WFDS Monitor: true
08-29 13:45:03.469  1941  2282 D WfdsMonitor: WfdsMonitorThread create
08-29 13:45:03.469  1941  2282 D WfdsMonitor: WFDS Monitor is created and started
08-29 13:45:03.469  1941  2282 D WfdsService: WiFi: Supplicant connection re-established
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:03.470  6023  6023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:45:03.472  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 13:45:03.472  6023  6023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:45:03.473  ,1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 13:45:03.473  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 13:45:03.473  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 13:45:03.474  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 13:45:03.474  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 13:45:03.474  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:45:03.474  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-29 13:45:03.474  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 13:45:03.474  1033  1536 D LGWifiP2pService: before postfix = G3
08-29 13:45:03.474  1033  1536 D WifiServerServiceExt: postfix byte check : 2
08-29 13:45:03.474  1033  1536 D LGWifiP2pService: after postfix = G3
08-29 13:45:03.474  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 13:45:03.475  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 13:45:03.475  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 13:45:03.475  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 13:45:03.476  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 13:45:03.476  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 13:45:03.476  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 13:45:03.476  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:45:03.476  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-29 13:45:03.476  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 13:45:03.476  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 13:45:03.477  1033  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.477  1033  1555 I WifiNative-HAL: startHal
08-29 13:45:03.477  1033  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.477  1941  2282 D WfdsService: Receive the WFDS_ENABLE Method
08-29 13:45:03.477  1941  2282 D WfdsService: Set the WFDS Monitor: true
08-29 13:45:03.477  1941  2282 D WfdsService: Connected to the supplicant for wfds
08-29 13:45:03.477  1941  2282 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 13:45:03.477  1941  2282 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-29 13:45:03.477  1941  2282 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
08-29 13:45:03.477  1941  2282 D WfdsService: selectPreferredScanChannel [36]
08-29 13:45:03.477  1941  2282 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 13:45:03.478  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 13:45:03.479  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 13:45:03.479  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 13:45:03.479  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 13:45:03.480  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 13:45:03.480  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 13:45:03.480  1033  1555 D wifi    : getting scan capabilities on interface[1] = 0x95278fe0
08-29 13:45:03.480  1033  1555 D wifi    : failed to get capabilities : -3
08-29 13:45:03.480  1033  1555 E WifiScanningService: could not get scan capabilities
08-29 13:45:03.480  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 13:45:03.480  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:45:03.481  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 13:45:03.481  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 13:45:03.481  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 13:45:03.481  1941  1941 D WfdsService: isConnected: false
08-29 13:45:03.482  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 13:45:03.482  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 13:45:03.482  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 13:45:03.483  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 13:45:03.483  1941  7178 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 13:45:03.483  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 13:45:03.483  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 13:45:03.483  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 13:45:03.483  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 13:45:03.483  1941  1941 D WfdsService: Update P2p Interface State: 3
08-29 13:45:03.484  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 13:45:03.484  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 13:45:03.485  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:45:03.486  1941  7178 E CtrlSupplicant: Succeed to open control connection
08-29 13:45:03.488  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:45:03.488  1941  7178 E CtrlSupplicant: Succeed to open monitor connection
08-29 13:45:03.493  1941  7178 D WfdsMonitor: Supplicant connection established
08-29 13:45:03.493  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 13:45:03.493  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 13:45:03.494  1033  1536 D LGWifiP2pService: InactiveState
08-29 13:45:03.494  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:03.494  1033  1536 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.494  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.494  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 13:45:03.494  1941  2282 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-29 13:45:03.494  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:45:03.495  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.495  1941  7178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:45:03.495  7155  7155 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:45:03.495  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.496  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:45:03.497  1033  7177 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.497  1033  1033 E WifiServerServiceExt: No p2p device connected
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.497  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.498  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.498  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:45:03.499  1941  2282 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 13:45:03.499  7155  7155 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.499  1941  7178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.499  1941  7178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.499  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:45:03.499  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.499  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.499  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:45:03.500  7155  7155 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:45:03.500  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.500  1941  7178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.500  1033  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 13:45:03.500  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:45:03.500  7155  7155 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.500  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:45:03.501  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:45:03.501  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 13:45:03.501  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.501  1941  7178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.501  1033  7177 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  7177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:45:03.501  1033  7177 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:45:03.501  1033  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.501  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:03.503  6347  7180 W FormManager: Network not available. Please check & try again.
08-29 13:45:03.503  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 13:45:03.503  7155  7155 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:45:03.505  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 13:45:03.505  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:45:03.505  1033  7177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:45:03.505  1033  7177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:45:03.506  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 13:45:03.506  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 13:45:03.507  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 13:45:03.507  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
08-29 13:45:03.507  1033  1537 D WifiNative-wlan0: SCAN: returned false
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:03.508  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:45:03.508  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=141005  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:45:03.508  6347  7181 V FormManager: Network unavailable.
08-29 13:45:03.509  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=141007  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:45:03.510  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 13:45:03.510  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 13:45:03.511  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 13:45:03.511  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 13:45:03.511  7155  7155 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 13:45:03.512  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:03.512  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:03.512  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:03.513  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:45:03.513  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.513  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:03.513  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:45:03.513  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:45:03.514  4267  4267 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:45:03.515  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:45:03.516  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:45:03.516  6347  7181 V FormManager: Network unavailable.
08-29 13:45:03.520  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 13:45:03.521  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 13:45:03.522  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 13:45:03.522  4267  7182 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:45:03.524  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3680073c Bundle[{}]
08-29 13:45:03.525  6023  6083 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:45:03.525  6023  6083 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 13:45:03.525  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 13:45:03.526  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:45:03.526  4267  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:45:03.527  4267  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:45:03.527  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 13:45:03.528  6023  6083 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 13:45:03.528  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 13:45:03.529  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 13:45:03.529  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 13:45:03.529  7155  7155 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 13:45:03.530  1033  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:45:03.530  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:45:03.531  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:45:03.531  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:45:03.532  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:45:03.537  6023  6083 I System.out: Running OutgoingSocketThread
08-29 13:45:03.539  6023  7184 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 767)
08-29 13:45:03.541  6023  7184 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54483
08-29 13:45:03.541  6023  7184 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:45:03.542  1033  1938 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7185 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 13:45:03.544  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:03.544  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 13:45:03.641  7185  7185 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 13:45:03.641  7185  7185 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 13:45:03.653  7185  7185 V [BNRBootReceiver]: Boot Receiver Return
08-29 13:45:03.656  7185  7185 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 13:45:03.660  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:45:03.678  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:03.687  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:45:03.696  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:45:03.697  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:03.701  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:45:03.705  1033  1574 I ActivityManager: Killing 6606:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 13:45:03.784  1033  1938 W libprocessgroup: failed to open /acct/uid_10011/pid_6606/cgroup.procs: No such file or directory
,08-29 13:45:04.036  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-29 13:45:04.036  1033  7177 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-29 13:45:04.051  7155  7155 E wpa_supplicant: USIM:  scard_init function
08-29 13:45:04.051  7155  7155 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 13:45:04.057  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 13:45:04.057  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-29 13:45:04.057  1033  7177 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 13:45:04.057  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:45:04.057  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-29 13:45:04.061  1033  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 13:45:04.062  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 13:45:04.062  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 13:45:04.062  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 13:45:04.063  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 13:45:04.078  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=141575  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 13:45:04.085  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.085  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.085  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:45:04.087  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.087  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:04.090  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:45:04.102  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.102  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.102  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:45:04.103  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=141600  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 13:45:04.104  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:04.104  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 13:45:04.111  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.111  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 13:45:04.116  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.120  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 13:45:04.127  6238  6238 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 13:45:04.132  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.144  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.153  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.161  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.161  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:45:04.165  6310  6310 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:45:04.170  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.174  7155  7155 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:45:04.181  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 13:45:04.181  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 13:45:04.181  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 13:45:04.183  7155  7155 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:45:04.183  7155  7155 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:45:04.189  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-29 13:45:04.192  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=141683  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 13:45:04.192  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:45:04.193  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:45:04.193  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:45:04.193  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:45:04.195  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:45:04.205  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=141702  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 13:45:04.205  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 13:45:04.205  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:45:04.205  1033  7177 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:45:04.205  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 13:45:04.205  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:45:04.205  1033  7177 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:45:04.206  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:45:04.206  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:45:04.206  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141703
08-29 13:45:04.206  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141703
,08-29 13:45:04.206  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141704
08-29 13:45:04.207  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141704
08-29 13:45:04.207  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141705
08-29 13:45:04.210  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=141707  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:45:04.214  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=141711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:45:04.215  1033  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:04.215  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-29 13:45:04.215  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:04.216  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:04.216  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:45:04.217  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=141714  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:45:04.218  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=141715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:45:04.220  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 13:45:04.220  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.221  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:04.221  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.221  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 13:45:04.223  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.224  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.224  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 13:45:04.224  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.226  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.227  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:04.228  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.228  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:04.229  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 13:45:04.229  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=141726
08-29 13:45:04.229  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=141726
08-29 13:45:04.229  1033  1537 D WifiNative-wlan0: doString: [STATUS]
08-29 13:45:04.230  1033  7177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:45:04.230  1033  7177 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:45:04.231  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:45:04.232  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:45:04.232  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
,08-29 13:45:04.239  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 13:45:04.239  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 13:45:04.241  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.242  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.243  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.243  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:45:04.244  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.244  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 13:45:04.247  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:45:04.247  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.247  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:45:04.249  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.253  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.253  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:04.254  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 13:45:04.254  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:45:04.254  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:45:04.254  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
08-29 13:45:04.254  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:45:04.254  1033  1543 D ConnectivityService: NetworkAgent connected
08-29 13:45:04.254  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.255  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:45:04.255  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:45:04.260  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:45:04.260  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:45:04.260  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:45:04.260  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:45:04.260  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:45:04.260  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:45:04.262  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.264  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:45:04.265  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:45:04.267  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:45:04.267  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:45:04.267  6238  6238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:45:04.267  6238  6238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:45:04.267   310   890 D CommandListener: Setting iface cfg
,08-29 13:45:04.268  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:45:04.268  6238  6238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:45:04.269  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 13:45:04.269  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:45:04.269  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:45:04.269  6238  6238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:45:04.269  6238  6238 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 13:45:04.269  6238  6238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:45:04.273  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.274  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 13:45:04.274  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=141772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:45:04.275  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=141772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:45:04.275  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=141773  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 13:45:04.276  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141774  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:45:04.277  1033  7229 D DhcpStateMachine: StoppedState
08-29 13:45:04.277  1033  7229 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:45:04.277  1033  7229 D DhcpStateMachine: WaitBeforeStartState
08-29 13:45:04.277  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141774  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:45:04.277  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141775  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:45:04.279  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:04.279  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 13:45:04.280  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14286] from screen [on:0 period:-702678248] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 13:45:04.280  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-702678248] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 13:45:04.281  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 13:45:04.285  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.286  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.286  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.286  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.287  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.287  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.288  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:45:04.288  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 13:45:04.288  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-29 13:45:04.291  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:04.291  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:45:04.292  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=6,0,0
08-29 13:45:04.292  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=6,0,0
08-29 13:45:04.292  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 13:45:04.292  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 13:45:04.292  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:45:04.293  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 13:45:04.293  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 13:45:04.293  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
08-29 13:45:04.293  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 13:45:04.293  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 13:45:04.293  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 13:45:04.294  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 13:45:04.294  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:45:04.294  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:45:04.294  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cfcd221 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.294  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cfcd221 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.294  1033  7229 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.294  1033  7229 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 13:45:04.295   310   890 D CommandListener: Setting iface cfg
08-29 13:45:04.295   310   890 D CommandListener: Trying to bring up wlan0
08-29 13:45:04.296  1033  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 13:45:04.297  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 13:45:04.297  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:45:04.297  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:45:04.297  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 13:45:04.297  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:45:04.297  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.297  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.297  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:45:04.297  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:45:04.298  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 13:45:04.298  7155  7155 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 13:45:04.298  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 13:45:04.298  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,08-29 13:45:04.300  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.306  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.306  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.306  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:45:04.309  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.314  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.319  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:45:04.319  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.320  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.320  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.320  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.321  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.321  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.321  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 13:45:04.322  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:04.322  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 13:45:04.322  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:45:04.323  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:45:04.323  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 13:45:04.323  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
08-29 13:45:04.325  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.325  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 13:45:04.326  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.326  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.326  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:45:04.326  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.329  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 13:45:04.330  1033  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-29 13:45:04.330  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.330  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.330  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:45:04.331  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.331  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.331  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:45:04.342  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 13:45:04.343  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:45:04.344  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.344  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.344  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:45:04.347  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 13:45:04.347  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 13:45:04.348  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.348  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:45:04.348  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.348  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:45:04.348  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:45:04.349  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:45:04.349  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.352  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.352  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:45:04.352  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.354  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.357  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:45:04.357  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:45:04.357  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.360  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:45:04.360  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 13:45:04.361  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.361  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 13:45:04.362   310   890 E Netd    : netlink response contains error (File exists)
08-29 13:45:04.362  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 13:45:04.363  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 13:45:04.363  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 13:45:04.363  1033  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 13:45:04.365  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.365  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.365  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:45:04.366  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:45:04.366  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:45:04.366  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.366  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.366  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.366  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 13:45:04.366  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:04.366  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.366  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:04.366  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 13:45:04.366  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 13:45:04.366  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.366  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 13:45:04.366  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-29 13:45:04.366  1033  1543 D ConnectivityService:    accepting network in place of null
08-29 13:45:04.366  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.367  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.367  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:45:04.367  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.367  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:04.368  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:45:04.368  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 13:45:04.368  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:45:04.369   310  7236 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 13:45:04.370  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is ,processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.373  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 13:45:04.374  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:45:04.374  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:45:04.374  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:45:04.375  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:45:04.375  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 13:45:04.375   310  7237 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:45:04.375  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 13:45:04.375  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:45:04.376  1033  1543 D ConnectivityService: validation of new default Network = false
08-29 13:45:04.376  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 13:45:04.376  1033  1543 D DSQN    : enableDataServiceNotify 
08-29 13:45:04.376  1033  1543 D DSQN    : start dsqn bin
,08-29 13:45:04.384  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.384  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.384  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.385  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.386  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:45:04.374  7238  7238 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:04.374  7238  7238 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:04.389  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.396  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 13:45:04.396  7238  7238 E DSQN    : DSQN ssw
08-29 13:45:04.399  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.408  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.409  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.409  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:45:04.415  1816  7242 I CheckinService: active receiver: enabled
,08-29 13:45:04.424  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.426  1816  7242 I CheckinService: Preparing to send checkin request
08-29 13:45:04.427  1816  7242 I EventLogService: Accumulating logs since 1472471004293
,08-29 13:45:04.431  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:45:04.432  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.433  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.433  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.438   310  7236 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 13:45:04.438  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.444  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.444  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.445  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:45:04.448  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:45:04.454  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:45:04.458  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.463  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.463  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.464  6310  6310 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:45:04.467  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.471  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:45:04.472  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:45:04.476  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:45:04.477  1816  7242 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 13:45:04.479   310  7236 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 13:45:04.484  1033  1542 D WifiService: New client listening to asynchronous messages
08-29 13:45:04.484  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:45:04.491  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:45:04.491  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.492  6310  6310 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:45:04.493  6310  6310 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:45:04.493  6310  6310 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:45:04.496  1033  7229 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 13:45:04.497  1033  7229 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 13:45:04.497  1033  7229 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 13:45:04.498  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:45:04.494  7245  7245 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:04.494  7245  7245 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:45:04.504  6256  6256 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 13:45:04.507  6256  6256 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:45:04.512   310   889 D LGDataListener: argv[0]=dsqncommand
08-29 13:45:04.512   310   889 D LGDataListener: argv[1]=wlan0
08-29 13:45:04.512   310   889 D LGDataListener: argv[2]=1
08-29 13:45:04.512   310   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 13:45:04.512  7245  7245 I dhcpcd  : version 5.5.6 starting
08-29 13:45:04.513  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 13:45:04.513  1033  1093 D DSQN    : start to monitor internet connection
08-29 13:45:04.515  7245  7245 E dhcpcd  : get_duid: m
08-29 13:45:04.515  6238  6238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:45:04.515  7245  7245 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 13:45:04.515  7245  7245 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 13:45:04.527  6238  6238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:45:04.536  6310  6310 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:45:04.537  6310  6310 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:45:04.539  6023  6083 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 768)
08-29 13:45:04.540  6023  6083 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 768)
08-29 13:45:04.540  6310  6310 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 13:45:04.541  6310  6310 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:45:04.542  6310  6310 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:45:04.542  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 11:45:03 GMT], X-Android-Received-Millis=[1472471104541], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472471104509]}
08-29 13:45:04.542  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 13:45:04.542  1033  7227 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 13:45:04.542  1033  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.543  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.543  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:04.543  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.543  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 13:45:04.543  1033  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-29 13:45:04.543  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 13:45:04.543  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.543  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.544  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:04.544  1033  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.544  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 13:45:04.545  1033  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.545  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:45:04.545  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:04.545  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:04.546  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:45:04.547  6023  6083 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 773)
08-29 13:45:04.549  6023  6083 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 13:45:04.549  6023  6083 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 774)
08-29 13:45:04.557  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.557  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@131a0b3b added. We now have 2 listener(s)
,08-29 13:45:04.558  1033  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.561  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.561  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.561  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.562  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.562  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c24f258 added. We now have 9 listener(s)
08-29 13:45:04.562  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.563  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:45:04.565  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:04.572  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:04.573  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:45:04.575  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.575  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.576  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:04.576  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:45:04.576  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.576  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47c6c96 added. We now have 3 listener(s)
08-29 13:45:04.579  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.579  1033  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.581  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.583  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.583  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.583  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.583  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.584  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24142017 added. We now have 10 listener(s)
08-29 13:45:04.584  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:04.584  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:04.584  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.584  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.585  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.585  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.585  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.585  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.585  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@131a0b3b removed from the list
08-29 13:45:04.585  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.585  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c24f258 removed from the list
08-29 13:45:04.585  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:04.585  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.586  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.586  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.587  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.587  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.587  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.587  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c24f258 not in the list
08-29 13:45:04.587  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.587  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.588  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.588  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.588  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.588  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24142017 removed from the list
08-29 13:45:04.588  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.588  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.588  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.588  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.588  6023  6083 V org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47c6c96 removed from the list
08-29 13:45:04.589  7245  7245 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:45:04.589  7245  7245 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:45:04.589  7245  7245 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:45:04.589  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.589  7245  7245 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 13:45:04.589  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2722dc04 added. We now have 2 listener(s)
08-29 13:45:04.589  7245  7245 D dhcpcd  : wlan0: sending REQUEST (xid 0xa089ee31), next in 3.64 seconds
08-29 13:45:04.590  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.592  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.592  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.592  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.592  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.592  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f915ed added. We now have 9 listener(s)
08-29 13:45:04.592  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.593  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:45:04.595  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:04.600  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:45:04.602  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.602  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:04.603  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.603  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a30a6b3 added. We now have 3 listener(s)
08-29 13:45:04.603  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.604  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.606  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.606  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.606  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.606  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.606  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.606  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af3b470 added. We now have 10 listener(s)
08-29 13:45:04.606  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.606  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:04.606  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:04.606  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:04.606  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.606  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:45:04.609  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:45:04.610  1033  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.614  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:45:04.614  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:45:04.616  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:04.617  7245  7245 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 13:45:04.617  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.618  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:45:04.618  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.618  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.621  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:04.621  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.621  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.621  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.621  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.621  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.621  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.621  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2722dc04 removed from the list
08-29 13:45:04.621  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.621  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f915ed removed from the list
08-29 13:45:04.621  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:04.621  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.622  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.622  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:04.623  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.623  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.623  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.623  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f915ed not in the list
08-29 13:45:04.623  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.623  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.625  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.625  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:45:04.625  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:04.625  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.625  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.626  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af3b470 removed from the list
08-29 13:45:04.626  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.626  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.626  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.626  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.626  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a30a6b3 removed from the list
08-29 13:45:04.627  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.627  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@884fb0f added. We now have 2 listener(s)
08-29 13:45:04.627  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.630  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.630  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.630  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.630  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.630  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b7a79c added. We now have 9 listener(s)
08-29 13:45:04.630  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.631  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:45:04.633  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: bind: Binding a new listener
,08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:04.636  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:45:04.638  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.638  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:04.638  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.638  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bbbad7a added. We now have 3 listener(s)
08-29 13:45:04.638  7245  7245 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 13:45:04.638  7245  7245 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 13:45:04.638  7245  7245 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 13:45:04.639  1033  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.639  7245  7245 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 13:45:04.639  7245  7245 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:45:04.639  7245  7245 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:45:04.639  7245  7245 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:45:04.639  7245  7245 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 13:45:04.642  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.643  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.643  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.643  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.643  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.643  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3420392b added. We now have 10 listener(s)
08-29 13:45:04.643  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.644  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:04.644  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to adverti,sements only
08-29 13:45:04.644  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:04.644  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:04.645  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.645  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:45:04.648  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:04.653  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:45:04.702  1033  1574 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7259 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-29 13:45:04.702  1033  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:45:04.711  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:45:04.712  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:45:04.715  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:45:04.716  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.719  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:45:04.719  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:04.719  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.719  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.720  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.720  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.720  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.720  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.720  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@884fb0f removed from the list
08-29 13:45:04.720  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.720  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b7a79c removed from the list
08-29 13:45:04.720  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:04.720  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.720  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.720  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.721  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.721  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.721  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.721  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b7a79c not in the list
08-29 13:45:04.721  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.721  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.722  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.722  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:45:04.722  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:04.722  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.722  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.722  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3420392b removed from the list
08-29 13:45:04.722  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.722  6023  6083 W org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.722  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.723  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.723  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bbbad7a removed from the list
08-29 13:45:04.723  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.723  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c72746 added. We now have 2 listener(s)
08-29 13:45:04.724  1033  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.726  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.726  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.726  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.726  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.726  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e73d07 added. We now have 9 listener(s)
08-29 13:45:04.726  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.726  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:04.736  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:04.740  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:04.741  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.741  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:04.741  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.741  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad8545d added. We now have 3 listener(s)
08-29 13:45:04.742  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.743  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.745  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.747  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.747  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.747  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.747  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.747  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14be71d2 added. We now have 10 listener(s)
08-29 13:45:04.747  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.747  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:04.747  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:04.747  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:04.747  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.747  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:45:04.749  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:45:04.750  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.757  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:45:04.758  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:45:04.759  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:04.759  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.761  6023  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-29 13:45:04.762  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:04.762  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.762  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.762  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.762  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.762  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.762  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.762  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c72746 removed from the list
08-29 13:45:04.762  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.762  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e73d07 removed from the list
08-29 13:45:04.762  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:04.762  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.763  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.763  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.765  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.765  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.766  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.766  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e73d07 not in the list
08-29 13:45:04.766  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.766  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.768  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:04.769  6023  6083 D BluetoothLeScanner: could not find callback wrapper
08-29 13:45:04.769  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:04.769  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.769  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.769  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14be71d2 removed from the list
08-29 13:45:04.769  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.769  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.769  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.769  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.769  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad8545d removed from the list
08-29 13:45:04.770  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.770  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cad959 added. We now have 2 listener(s)
08-29 13:45:04.771  1033  1777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.773  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.774  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.774  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.774  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.774  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dd91e added. We now have 9 listener(s)
08-29 13:45:04.774  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.775  7259  7259 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 13:45:04.775  7259  7259 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 13:45:04.775  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:45:04.777  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-2,9 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:04.780  6023  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:04.782  6023  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:04.782  6023  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:04.782  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:04.782  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e822fcc added. We now have 3 listener(s)
08-29 13:45:04.782  1033  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:45:04.783  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.785  6023  6023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:04.786  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:45:04.786  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:04.786  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:04.787  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:04.787  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc6b215 added. We now have 10 listener(s)
08-29 13:45:04.787  6023  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:04.787  6023  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:04.787  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.787  6023  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:04.787  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.787  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.787  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:04.787  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.787  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cad959 removed from the list
08-29 13:45:04.787  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.787  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dd91e removed from the list
08-29 13:45:04.788  6023  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:04.788  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.789  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.789  6023  6083 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.790  6023  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dd91e not in the list
08-29 13:45:04.790  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.790  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:04.790  6023  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc6b215 removed from the list
08-29 13:45:04.790  6023  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:04.790  6023  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:04.790  6023  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:04.791  6023  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:04.791  6023  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e822fcc removed from the list
08-29 13:45:04.791  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 13:45:04.792  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:45:04.792  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-29 13:45:04.792  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:04.792  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:45:04.792  6023  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:04.800  7259  7259 I MultiDex: VM with version 2.1.0 has multidex support
08-29 13:45:04.800  7259  7259 I MultiDex: install
08-29 13:45:04.800  7259  7259 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 13:45:04.803  6023  7287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 781, name: My test thread name)
08-29 13:45:04.803  6023  7287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 781, thread name: My test thread name)
08-29 13:45:04.803  6023  7287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 781, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:45:04.805  6023  7289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 783, name: My test thread name)
08-29 13:45:04.806  6023  7289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 783, thread name: My test thread name)
08-29 13:45:04.806  6023  7289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 783, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:45:04.807  7259  7259 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 13:45:04.808  6023  6083 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:45:04.808  6023  6083 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:45:04.808  6023  6083 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:45:04.808  6023  6083 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:45:04.808  6023  6083 D com.test.thalitest.ThaliTestRunner: Total duration: 22822 ms
08-29 13:45:04.810  6023  6083 I jxcore-log: *Native tests were executed*
08-29 13:45:04.810  6023  6083 I jxcore-log: 
08-29 13:45:04.810  2158  2158 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 13:45:04.814  6023  6083 I jxcore-log: Total number of executed tests:  80
08-29 13:45:04.814  6023  6083 I jxcore-log: 
08-29 13:45:04.814  6023  6083 I jxcore-log: Number of passed tests:  80
08-29 13:45:04.814  6023  6083 I jxcore-log: 
08-29 13:45:04.814  6023  6083 I jxcore-log: Number of failed tests:  0
08-29 13:45:04.814  6023  6083 I jxcore-log: 
08-29 13:45:04.814  6023  6083 I jxcore-log: Number of ignored tests:  0
08-29 13:45:04.814  6023  6083 I jxcore-log: 
08-29 13:45:04.815  6023  6083 I jxcore-log: Total duration:  22822
08-29 13:45:04.815  6023  6083 I jxcore-log: 
,08-29 13:45:04.815  6023  6083 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:45:04.815  6023  6083 I jxcore-log: 
08-29 13:45:04.818  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.818  6023  6083 I jxcore-log: 
08-29 13:45:04.821  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.821  6023  6083 I jxcore-log: 
08-29 13:45:04.822  2158  2158 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-29 13:45:04.822  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.822  6023  6083 I jxcore-log: 
08-29 13:45:04.822  2158  2158 D c       : Getting all permits...
08-29 13:45:04.822  2158  2158 D a       : Opening database...
08-29 13:45:04.823  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.823  6023  6083 I jxcore-log: 
08-29 13:45:04.824  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.824  6023  6083 I jxcore-log: 
08-29 13:45:04.824  2158  2158 D a       : Opening database auth.proximity.permit_store...
08-29 13:45:04.825  2158  2158 D a       : Closing database...
08-29 13:45:04.833  6023  6023 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 13:45:04.834  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.834  6023  6083 I jxcore-log: 
08-29 13:45:04.840  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.840  6023  6083 I jxcore-log: 
08-29 13:45:04.842  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.842  6023  6083 I jxcore-log: 
08-29 13:45:04.843  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.843  6023  6083 I jxcore-log: 
08-29 13:45:04.844  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:04.844  6023  6083 I jxcore-log: 
08-29 13:45:04.845  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.845  6023  6083 I jxcore-log: 
,08-29 13:45:04.846  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.846  6023  6083 I jxcore-log: 
08-29 13:45:04.848  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.848  6023  6083 I jxcore-log: 
08-29 13:45:04.849  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.849  6023  6083 I jxcore-log: 
08-29 13:45:04.850  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.850  6023  6083 I jxcore-log: 
08-29 13:45:04.851  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.851  6023  6083 I jxcore-log: 
08-29 13:45:04.851  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.851  6023  6083 I jxcore-log: 
08-29 13:45:04.852  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.852  6023  6083 I jxcore-log: 
08-29 13:45:04.854  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.854  6023  6083 I jxcore-log: 
08-29 13:45:04.854  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:04.854  6023  6083 I jxcore-log: 
08-29 13:45:04.855  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.855  6023  6083 I jxcore-log: 
08-29 13:45:04.856  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:04.856  6023  6083 I jxcore-log: 
,08-29 13:45:04.857  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:04.857  6023  6083 I jxcore-log: 
08-29 13:45:04.857  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:04.857  6023  6083 I jxcore-log: 
08-29 13:45:04.858  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:04.858  6023  6083 I jxcore-log: 
08-29 13:45:04.859  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:04.859  6023  6083 I jxcore-log: 
08-29 13:45:04.860  6023  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:04.860  6023  6083 I jxcore-log: 
08-29 13:45:04.901  1033  7229 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 13:45:04.903  1033  7229 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-29 13:45:04.904  1033  7229 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-29 13:45:04.904  1033  7229 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 13:45:04.904  1033  7229 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 13:45:04.904  1033  7229 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:45:04.904  1033  7229 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 13:45:04.904  1033  7229 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 13:45:04.905  1033  7229 D DhcpStateMachine: RunningState
08-29 13:45:05.102  7259  7278 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:45:05.102  7259  7278 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:45:05.189  7298  7298 D AndroidRuntime: 
08-29 13:45:05.189  7298  7298 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:45:05.189  7303  7303 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 13:45:05.193  7298  7298 D AndroidRuntime: CheckJNI is OFF
08-29 13:45:05.279  7303  7303 I dex2oat : dex2oat took 90.283ms (threads: 4)
,08-29 13:45:05.297  7259  7278 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:45:05.297  7259  7278 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:45:05.297  7259  7278 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:45:05.297  7259  7278 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:45:05.297  7259  7278 I Adreno-EGL: Remote Branch: 
08-29 13:45:05.297  7259  7278 I Adreno-EGL: Local Patches: 
08-29 13:45:05.297  7259  7278 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:45:05.357  7298  7298 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:45:05.384  1033  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-29 13:45:05.385  1033  1091 I ActivityManager: Killing 6023:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-29 13:45:05.421  7259  7278 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:45:05.421  7259  7278 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:45:05.421  7259  7278 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:45:05.421  7259  7278 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:45:05.421  7259  7278 I Adreno-EGL: Remote Branch: 
08-29 13:45:05.421  7259  7278 I Adreno-EGL: Local Patches: 
08-29 13:45:05.421  7259  7278 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:45:05.442  1033  1049 I WindowState: WIN DEATH: Window{3cd139b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:45:05.443  1033  1542 D WifiService: Client connection lost with reason: 4
,08-29 13:45:05.451  1033  1049 D InputDispatcher: Window went away: Window{3cd139b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:45:05.595  1033  1091 E libprocessgroup: failed to kill 1 processes for processgroup 6023
,08-29 13:45:05.601  1033  1091 I ActivityManager:   Force finishing activity ActivityRecord{25b25373 u0 com.test.thalitest/.MainActivity t6}
08-29 13:45:05.616   339   348 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 13:45:05.617  1033  1975 W ActivityManager: Spurious death for ProcessRecord{39d62de7 6023:com.test.thalitest/u0a118}, curProc for 6023: null
08-29 13:45:05.617  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 13:45:05.618  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ba92b65 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 13:45:05.618  1941  2892 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 13:45:05.619  1941  2892 D SplitWindowPolicy: topRunningActivity=ActivityInfo{75e703a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 13:45:05.621  1033  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-29 13:45:05.653  2030  2030 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 13:45:05.654  2030  2030 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-29 13:45:05.661  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 13:45:05.661  3698  3698 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 13:45:05.663  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 13:45:05.668  6991  6991 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 13:45:05.668  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 13:45:05.673  4424  4424 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 13:45:05.673  2464  2599 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 13:45:05.674  4424  4424 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 13:45:05.675  4424  4424 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 13:45:05.675  4424  4424 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 13:45:05.675  4424  4424 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:45:05.675  4424  4424 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:45:05.675  4424  4424 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:45:05.675  4424  4424 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:45:05.675  4424  4424 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.675  4424  4424 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:45:05.675  4424  4424 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:45:05.675  4424  4424 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:45:05.679  1033  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:45:05.694  4543  4543 I art     : Explicit concurrent mark sweep GC freed 746(43KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 551us total 58.735ms
,08-29 13:45:05.716  1033  1975 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:45:05.721  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 13:45:05.722  2030  2102 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-29 13:45:05.722  1033  1033 D administrator: Handling package changes for user 0
08-29 13:45:05.725  3733  3733 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 13:45:05.726  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-29 13:45:05.727  3698  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-29 13:45:05.729  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 13:45:05.745  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-29 13:45:05.757  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 13:45:05.759  2030  2030 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 13:45:05.768  2030  2030 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-29 13:45:05.770  2030  2030 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 13:45:05.776  2158  2158 I ConfigService: onCreate
08-29 13:45:05.778  2158  2158 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 13:45:05.781  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 13:45:05.782  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 13:45:05.783  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-29 13:45:05.784  3698  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 13:45:05.784  3698  3716 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , display: false
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , animation: false }
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , display: false
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , animation: false }
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , display: false
08-29 13:45:05.788  2030  2030 I GBoardWebViewUtils: , animation: false }
,08-29 13:45:05.792  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 13:45:05.792  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 13:45:05.795  2030  7327 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 13:45:05.798  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-29 13:45:05.798  1869  1869 D SplitUIService: removed split : 
08-29 13:45:05.805  2158  2158 I ConfigService: onBind returning update interface
,08-29 13:45:05.807  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 13:45:05.808  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 13:45:05.810  1033  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 13:45:05.820  1033  1648 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:45:05.820  1033  1648 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:45:05.829  1033  1049 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7332 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-29 13:45:05.839   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 240us total 11.906ms
,08-29 13:45:05.849   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 9.479ms
08-29 13:45:05.852  2158  2158 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 13:45:05.852  2158  2158 I ConfigService: onBind returning config service
08-29 13:45:05.854  2158  2158 I ConfigService: onDestroy
08-29 13:45:05.859   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.447ms
,08-29 13:45:05.861  1816  7341 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 13:45:05.865  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-29 13:45:05.865  1869  1869 I SplitUIService: split app #11
08-29 13:45:05.888  1033  1574 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:45:05.900  1033  1777 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7345 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-29 13:45:05.902  1033  1048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:45:05.902  6991  6991 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-29 13:45:05.921  2030  2030 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-29 13:45:05.946  5508  7369 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-29 13:45:05.951  7259  7278 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:45:05.951  7259  7278 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:45:05.951  7259  7278 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:45:05.951  7259  7278 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:45:05.951  7259  7278 I Adreno-EGL: Remote Branch: 
08-29 13:45:05.951  7259  7278 I Adreno-EGL: Local Patches: 
08-29 13:45:05.951  7259  7278 I Adreno-EGL: Reconstruct Branch: 
08-29 13:45:05.965  7332  7332 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-29 13:45:05.967   330   430 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-29 13:45:05.967  3153  7375 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-29 13:45:05.983  1601  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 13:45:05.983  1601  1653 D KeyguardModel: createShortcutInfo...
,08-29 13:45:05.987  1601  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 13:45:05.987  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:05.992  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 13:45:05.993  1601  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:45:05.993  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 13:45:05.994  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 13:45:06.004  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.004  1601  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 13:45:06.008  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 13:45:06.011  1601  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 13:45:06.011  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.011  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.015  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 13:45:06.016  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 13:45:06.017  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 13:45:06.018  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-29 13:45:06.021  1816  7373 I PeopleContactsSync: CP2 sync disabled
08-29 13:45:06.021  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 13:45:06.021  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:45:06.024  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.025  1601  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 13:45:06.025  1601  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 13:45:06.025  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.029  1816  7371 W GmsApplication: Using Auth Proxy for data requests.
,08-29 13:45:06.030  1601  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:45:06.030  1601  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 13:45:06.030  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 13:45:06.030  1601  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 13:45:06.031  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.031  1601  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 13:45:06.032  1601  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 13:45:06.032  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.039  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 13:45:06.039  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:45:06.039  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-29 13:45:06.040  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 13:45:06.040  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a9a3d9a u0 com.lge.launcher2/.Launcher t5} time:143551
08-29 13:45:06.044  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 13:45:06.044  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 13:45:06.044  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 13:45:06.046  1601  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 13:45:06.046  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.048  1816  7371 W GmsApplication: Using Auth Proxy for data requests.
08-29 13:45:06.049  1033  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 13:45:06.049  1601  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 13:45:06.049  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.050  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.050  1601  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 13:45:06.051  1601  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 13:45:06.051  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.052  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.052  1601  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 13:45:06.053  1601  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 13:45:06.053  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.054  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 13:45:06.054  1601  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:45:06.054  1601  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 13:45:06.054  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 13:45:06.054  1816  4683 I Icing   : doRemovePackageData com.test.thalitest
08-29 13:45:06.054  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.057  2030  2830 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 13:45:06.057  2030  2830 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 13:45:06.061  1601  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 13:45:06.061  1601  1653 D KeyguardModel: createShortcutInfo...
08-29 13:45:06.066  2030  2030 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 13:45:06.067  2613  2613 D [Concierge]Service: onStartCommand(). Type : 8
08-29 13:45:06.067  2613  2613 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 13:45:06.068  2613  2613 D [Concierge]Service: Update widget ID : 11
08-29 13:45:06.069  2030  2030 D [Concierge]WidgetView: change position of spinner
08-29 13:45:06.070  2030  2030 I [Concierge]WidgetView: initWebView(). Time : 1472471106070
08-29 13:45:06.070  2613  2613 D [Concierge]Service: onStartCommand(). Type : 0
,08-29 13:45:06.077  1816  7343 I art     : Explicit concurrent mark sweep GC freed 22111(1508KB) AllocSpace objects, 20(320KB) LOS objects, 51% free, 29MB/61MB, paused 2.024ms total 127.539ms
08-29 13:45:06.078  7345  7345 I AppUp4:AppBoxCP: onCreate
08-29 13:45:06.079  7345  7345 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 13:45:06.079  1033  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.079  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.079  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.080  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.080  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.080  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:45:06.081  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-29 13:45:06.082  1033  1543 D ConnectivityService: identical MTU - not setting
08-29 13:45:06.082  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:45:06.082  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 13:45:06.082  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:45:06.082  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:06.082  1033  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:45:06.084  7345  7345 I AppUp4:DB:  setFingerPrint start
08-29 13:45:06.084  7345  7345 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 13:45:06.087  1601  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 13:45:06.089  1033  1939 I ActivityManager: Killing 6658:com.lge.email/u0a23 (adj 15): empty #17
08-29 13:45:06.093  7345  7345 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 13:45:06.093  7345  7345 I AppUp4:DB:  SDK version = 21
08-29 13:45:06.093  7345  7345 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 13:45:06.158  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-29 13:45:06.158  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-29 13:45:06.159  1033  2010 W libprocessgroup: failed to open /acct/uid_10023/pid_6658/cgroup.procs: No such file or directory
08-29 13:45:06.160  7345  7345 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 13:45:06.161  1033  1101 I art     : Explicit concurrent mark sweep GC freed 86927(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.494ms total 394.506ms
08-29 13:45:06.163  2030  2030 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 113876633
08-29 13:45:06.164  2030  2030 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 13:45:06.164  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 13:45:06.167  2030  2030 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fc73a2e
08-29 13:45:06.167  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 13:45:06.168  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 13:45:06.168  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.174  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 13:45:06.175  2030  2030 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 13:45:06.175  2030  2030 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-29 13:45:06.179  2030  2030 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472470990466, New one : 1472471106070
08-29 13:45:06.179  2030  2030 D [Concierge]WidgetView: Unregister all receivers
08-29 13:45:06.179  2030  2030 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 13:45:06.179  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.181  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 13:45:06.182  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 13:45:06.183  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 13:45:06.184  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 13:45:06.185  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 13:45:06.191  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.191  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:45:06.195  7298  7298 D AndroidRuntime: Shutting down VM
08-29 13:45:06.202  7345  7345 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 13:45:06.205   310  7380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 13:45:06.205   310  7380 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-29 13:45:06.230  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:45:06.235  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 13:45:06.251  1033  1920 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7381 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 13:45:06.251  1033  1920 I ActivityManager: Killing 6715:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 13:45:06.264  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 13:45:06.271  2030  2030 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-29 13:45:06.271  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-29 13:45:06.272  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:45:06.292  2030  2030 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c877cda time:143804
,08-29 13:45:06.329  1033  2032 W libprocessgroup: failed to open /acct/uid_10046/pid_6715/cgroup.procs: No such file or directory
,08-29 13:45:06.333  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 13:45:06.350  7381  7381 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:45:06.351  7381  7381 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:45:06.351  7381  7381 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 13:45:06.352  7381  7381 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 13:45:06.352  7381  7381 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 13:45:06.382  2158  2175 I art     : Explicit concurrent mark sweep GC freed 4297(242KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 520us total 15.152ms
08-29 13:45:06.392  2030  2030 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 13:45:06.411  7381  7381 I SystemConfig: BUILD Country: EU
08-29 13:45:06.411  7381  7381 I SystemConfig: BUILD Operator: OPEN
,08-29 13:45:06.432  2030  2882 I GBoardtInterface: onReloaded()
,08-29 13:45:06.434  1033  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7399 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 13:45:06.435  2030  2030 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 13:45:06.436  3698  3716 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:45:06.439  3698  3717 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:45:06.444  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-29 13:45:06.445  3698  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 13:45:06.445  3698  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-29 13:45:06.448  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-29 13:45:06.449  3698  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 13:45:06.449  3698  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 13:45:06.449  3698  4448 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 13:45:06.449  3698  4448 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 13:45:06.450  3698  3716 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:45:06.452  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 13:45:06.452  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 13:45:06.453  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 13:45:06.453  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 13:45:06.457  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 13:45:06.457  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-29 13:45:06.458  1033  1938 I ActivityManager: Killing 6748:com.android.chrome/u0a57 (adj 15): empty #17
08-29 13:45:06.491  2394  2518 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-29 13:45:06.491  1033  1776 W libprocessgroup: failed to open /acct/uid_10057/pid_6748/cgroup.procs: No such file or directory
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:45:06.499  2394  2518 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:06.501  7381  7416 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 13:45:06.502  7381  7416 I SystemConfig: existFile = false
08-29 13:45:06.502  7381  7416 I SystemConfig: canReadFile = false
08-29 13:45:06.502  7381  7416 I SystemConfig: systemFeature RCS result false
08-29 13:45:06.502  7381  7416 D SystemConfig: refreshRcsSupport() :false
,08-29 13:45:06.504  2394  7421 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 13:45:06.510  2394  7421 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-29 13:45:06.511  2394  7421 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 13:45:06.511  2394  7421 E AndroidRuntime: Process: android.process.acore, PID: 2394
08-29 13:45:06.511  2394  7421 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:45:06.511  2394  7421 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
