#### Test 757892685a40176_thali06_HTC-HTC One M9 Logs


```
--------- beginning of system
07-12 17:43:31.820  1130  3842 I ActivityManager: Recipient 7263
,--------- beginning of main
07-12 17:43:31.870  1130  3394 D Process : killProcessQuiet, pid=7289
07-12 17:43:31.870  1130  3394 I ActivityManager: Killing 7289:com.htc.widget.hmsproc2/u0a36 (adj 15): empty #17
07-12 17:43:31.870  1130  3394 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
07-12 17:43:31.990  1130  1153 I ActivityManager: Recipient 7289
07-12 17:43:32.040  7955  7955 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-12 17:43:32.040  7955  7955 W HTCLOG  : mask=0x18
07-12 17:43:32.120  1130  2943 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-12 17:43:32.130  3680  4175 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-12 17:43:32.140  3680  4175 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-12 17:43:32.140  3680  4175 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-12 17:43:32.140  1130  1167 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 17:43:32.150  3680  4175 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-12 17:43:32.150  4222  7957 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-12 17:43:32.170  3350  3350 D Nfc-Utils: isNxpCodebase: isNxp=false
07-12 17:43:32.170  3680  4175 E ExternalAccountType: Unsupported attribute readOnly
07-12 17:43:32.180  3376  3376 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
07-12 17:43:32.180  1130  1130 W PackageManager: Unable to load service info ResolveInfo{2188f4be com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-12 17:43:32.180  1130  1130 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-12 17:43:32.180  1130  1130 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-12 17:43:32.190  4222  4222 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
07-12 17:43:32.200  7927  7953 I SetupWizard.FrpHelper: FRP status: supported: true, challengeRequired: false
07-12 17:43:32.210  1130  1153 D PMS     : acquireWL(1bedb83): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.210  1130  3842 D PMS     : releaseWL(1bedb83): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.210  1130  1130 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-12 17:43:32.210  1130  3677 D PMS     : acquireWL(2f779100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.220  1130  1167 D LocationProviderProxy: applying state to connected service
07-12 17:43:32.230  1130  3963 D PMS     : releaseWL(2f779100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.240  7955  7959 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-12 17:43:32.240  7955  7959 W HTCLOG  : mask=0x18
07-12 17:43:32.240  7955  7959 E cutils-trace: Error opening trace file: Permission denied (13)
07-12 17:43:32.240  1130  1167 D LocationProviderProxy: applying state to connected service
07-12 17:43:32.250  1130  1167 D PMS     : acquireWL(2ef023f5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.250  1130  3844 D PMS     : releaseWL(2ef023f5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.260  1130  3963 D PMS     : acquireWL(2bb2258a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.260  1130  3964 D PMS     : releaseWL(2bb2258a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.280  1130  3844 D PMS     : acquireWL(1be9dbe2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.300  7955  7955 D CustomizationManager: ====startRecUseTime====
07-12 17:43:32.300  1130  3705 D PMS     : releaseWL(1be9dbe2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.300  7955  7955 D htc.customization.log.level:  is 
07-12 17:43:32.300  7955  7955 W CustomizationLogLevel: Level value is invalid, use default level 2
07-12 17:43:32.320  1130  2992 D PMS     : acquireWL(165dab73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.340  1130  3844 D PMS     : releaseWL(165dab73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.360  7955  7955 D CustomizationManager:  Read ACC file spent 0.029 (s)
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__016
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__031
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:43:32.360  7955  7955 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:43:32.360  7955  7955 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = application
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = system
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = ACC
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 42507
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23420
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 24002
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23430
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27205
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 17:43:32.360  7955  7955 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:43:32.360  7955  7955 D CustomizationManager:  Read CID file spent 0.061 (s)
07-12 17:43:32.360  7955  7955 D CustomizationManager:  All configurations done spent 0.061 (s)
07-12 17:43:32.370  1130  3677 D PMS     : acquireWL(1e113a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.370  6521  6521 I CmaSystemUpdateService: receiver: Intent { act=com.google.android.gms.update.BOOT_START_SERVICE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
07-12 17:43:32.380  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-12 17:43:32.380  3405  3869 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1b0be533 +
07-12 17:43:32.380  3405  3869 I Prism.WidgetManager: onLoadItems() +
07-12 17:43:32.390  6521  6521 I CmaSystemUpdateService: receiver: Intent { act=com.google.android.gms.update.BOOT_START_SERVICE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
07-12 17:43:32.400  1130  3401 D PMS     : acquireWL(3e3096a9): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 6521 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.400  1130  3716 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7955 on display 0
07-12 17:43:32.410  1130  1185 D PMS     : acquireHCC(395d8bcf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1130 1000 null
07-12 17:43:32.410  3405  3869 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 17:43:32.410  1130  3716 V WindowManager: addAppToken: AppWindowToken{2ce7053a token=Token{3852f465 ActivityRecord{1e87c95c u0 com.test.thalitest/.MainActivity t124}}} to stack=1 task=124 at 0
07-12 17:43:32.410  1130  1185 D PMS     : acquireHCC(6d115eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1130 1000 null
07-12 17:43:32.420  1130  3716 D PMS     : acquireWL(3a761f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1130 1000 null
07-12 17:43:32.420  1130  1176 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/3
07-12 17:43:32.420  7955  7955 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-12 17:43:32.420  7955  7955 W HTCLOG  : mask=0x18
07-12 17:43:32.420  6521  6521 D CmaSystemUpdateService: onCreate
07-12 17:43:32.420  7955  7972 W HTCLOG  : use specified tag [Vector], func [0].
07-12 17:43:32.420  7955  7972 W HTCLOG  : mask=0x18
07-12 17:43:32.420  7955  7973 W HTCLOG  : use specified tag [Vector], func [0].
07-12 17:43:32.420  7955  7973 W HTCLOG  : mask=0x18
07-12 17:43:32.420  3405  3405 I FeedHostManager: [onPause]
07-12 17:43:32.420  3405  3405 I FeedProviderManager: onPause
07-12 17:43:32.420  6521  6521 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
07-12 17:43:32.420  3405  3405 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@23b4f8eb
07-12 17:43:32.420  3405  4852 I SocialFeedProvider: +onPause
07-12 17:43:32.420  3405  4852 I SocialFeedProvider: -onPause
07-12 17:43:32.420  3405  3405 I ContextualWidget: onPause
07-12 17:43:32.420  1130  1153 D PMS     : releaseWL(1e113a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.420  3405  3405 I ContextualWidget: notifyWidgetDeactive
07-12 17:43:32.430  1130  1176 V WindowManager: Adding window Window{1085763 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2d345234 u0 com.htc.launcher/com.htc.launcher.Launcher})
07-12 17:43:32.440  1130  3392 I ActivityManager: Start proc 7976:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 17:43:32.440  7976  7976 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:32.440  7976  7976 W HTCLOG  : mask=0x18
07-12 17:43:32.480  1130  3537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-12 17:43:32.480  1130  2940 V AlarmManager: sending alarm PendingIntent{219f06bf: PendingIntentRecord{1372923f com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=57065, Int=0
07-12 17:43:32.480  1130  2940 V AlarmManager: sending alarm PendingIntent{3b7e418c: PendingIntentRecord{b02c0d5 com.aiqidii.mercury broadcastIntent}}, i=null, t=1, cnt=1, w=1468338203606, Int=86400000
07-12 17:43:32.480  1130  2940 V AlarmManager: sending alarm PendingIntent{ab30ea: PendingIntentRecord{30c74fdb com.aiqidii.mercury broadcastIntent}}, i=null, t=1, cnt=1, w=1468338203609, Int=86400000
07-12 17:43:32.480  6521  6521 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
07-12 17:43:32.510  1130  3241 I ActivityManager: Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
07-12 17:43:32.510  3106  3106 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 17:43:32.510  1130  1169 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-12 17:43:32.510  3106  3106 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 17:43:32.510  1130  1169 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1085763 u0 Starting com.test.thalitest}
07-12 17:43:32.510  1130  1169 D StatusBarManagerService: hiding MENU key
07-12 17:43:32.520  6521  7997 I SystemUpdateTask: cancelUpdate (empty URL)
07-12 17:43:32.520  6521  7997 I CmaSystemUpdateService: active receiver: disabled
07-12 17:43:32.520  1130  3716 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateServiceActiveReceiver, state=2, flag=1, pid=6521, uid=10020, userID:0
07-12 17:43:32.520  6521  7997 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-12 17:43:32.530  1130  1153 I ActivityManager: Resuming delayed broadcast
07-12 17:43:32.530  6521  7997 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-12 17:43:32.530  3405  3405 I TrimMemoryManager: [trimMemory] 20
07-12 17:43:32.550  7976  7976 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-12 17:43:32.560  1130  3964 I ActivityManager: Delay finish: com.google.android.gms/.security.snet.SnetReceiver
07-12 17:43:32.560  1130  3392 D PMS     : releaseWL(3e3096a9): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 WorkSource{10020 com.google.android.gms}
07-12 17:43:32.570  6521  6521 D CmaSystemUpdateService: onDestroy
07-12 17:43:32.570  3405  3869 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 17:43:32.590  1130  3844 I ActivityManager: Resuming delayed broadcast
07-12 17:43:32.610  4222  8002 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-12 17:43:32.620  7976  7976 I LibraryLoader: Time to load native libraries: 41 ms (timestamps 7218-7259)
07-12 17:43:32.620  7976  7976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:43:32.630  7976  7976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {faca921}
,07-12 17:43:32.640  7976  7976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:43:32.640  7976  7976 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 17:43:32.650  7976  7976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:43:32.650  7976  7976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:32.650  7976  7976 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:43:32.680  7976  8005 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-12 17:43:32.690  7976  8009 D BluetoothAdapter: 949109062: getState() :  mService = null. Returning STATE_OFF,
,07-12 17:43:32.700  3405  3869 W asset   : Copying FileAsset 0xac550090 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,07-12 17:43:32.700  7976  7976 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-12 17:43:32.700  7976  7976 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345,
07-12 17:43:32.700  7976  7976 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
,07-12 17:43:32.710  7976  7976 W HTCLOG  : use specified tag [libEGL], func [3].
07-12 17:43:32.710  7976  7976 W HTCLOG  : mask=0x18
,07-12 17:43:32.710  7976  7976 W HTCLOG  : use specified tag [libEGL], func [3].,
07-12 17:43:32.710  7976  7976 W HTCLOG  : mask=0x18
07-12 17:43:32.710  7976  7976 I Adreno  : QUALCOMM build                   : 065751b, 
07-12 17:43:32.710  7976  7976 I Adreno  : Build Date                       : 04/15/15
07-12 17:43:32.710  7976  7976 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-12 17:43:32.710  7976  7976 I Adreno  : Local Branch                     : 
07-12 17:43:32.710  7976  7976 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-12 17:43:32.710  7976  7976 I Adreno  : Remote Branch                    : NONE
07-12 17:43:32.710  7976  7976 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,07-12 17:43:32.730  1130  3677 D PMS     : acquireWL(4fd4343): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:32.760  3405  3869 I Prism.WidgetManager: onLoadItems() -
,07-12 17:43:32.760  3405  3869 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1b0be533 -
,07-12 17:43:32.760  1130  3241 D PMS     : releaseWL(4fd4343): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:32.790  7976  8015 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-12 17:43:32.800  7976  7976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:32.800  7976  7976 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,07-12 17:43:32.810  7976  7976 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-12 17:43:32.820  7976  7976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:43:32.820  7976  7976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:32.830  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-12 17:43:32.830  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-12 17:43:32.830  3405  3405 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-12 17:43:32.850  3405  3405 I Launcher: Deferring update until onResume
07-12 17:43:32.850  3405  3405 D Launcher: waitUntilResume // bindAppsUpdated
,07-12 17:43:32.880  7976  8026 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,07-12 17:43:32.880  7976  8026 W HTCLOG  : mask=0x18
,07-12 17:43:32.930  1130  3842 D PMS     : acquireWL(191c3497): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms},
,07-12 17:43:32.950  1130  3401 D PMS     : releaseWL(191c3497): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms},
,07-12 17:43:32.950  1130  3705 D PMS     : acquireWL(cd29684): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 7874 10102 null,
,07-12 17:43:32.960  1130  3964 D PMS     : releaseWL(cd29684): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-12 17:43:32.970  1130  3842 D PMS     : acquireWL(c4f3aa2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.000  1130  2992 V WindowManager: Adding window Window{282496f0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1085763 u0 Starting com.test.thalitest})
,07-12 17:43:33.010  1130  3394 D PMS     : releaseWL(c4f3aa2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.030  1130  3844 D PMS     : acquireWL(2b319469): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.030  7976  7976 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-12 17:43:33.030  7976  7976 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-12 17:43:33.030  7976  7976 W HTCLOG  : mask=0x18
07-12 17:43:33.030  7976  7976 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 17:43:33.030  7976  7976 W HTCLOG  : mask=0x18
,07-12 17:43:33.030  7976  8026 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,07-12 17:43:33.030  7976  8026 W HTCLOG  : mask=0x18
07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
,07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [Surface], func [3].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
07-12 17:43:33.040  7976  8026 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-12 17:43:33.040  7976  8026 W HTCLOG  : mask=0x18
,07-12 17:43:33.050  1130  3963 D PMS     : releaseWL(2b319469): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.060  7469  7469 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:33.060  7469  8031 I DFPI.ApkInstallService: onHandleIntent
,07-12 17:43:33.060  7469  8031 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-12 17:43:33.070  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-12 17:43:33.070  7469  8031 I DFPI.SystemPropertiesUtil: value = HTC__102
07-12 17:43:33.070  7469  8031 I DFPI.ApkInstallService: deviceCID = HTC__102
07-12 17:43:33.070  7469  8031 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:33.070  7469  8031 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-12 17:43:33.070  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-12 17:43:33.070  7559  8033 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 17:43:33.070  7559  8033 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:33.070  7559  8033 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:33.070  7559  8033 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.070  7559  8033 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.070  7559  8033 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.070  7559  8033 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 17:43:33.070  7559  8033 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-12 17:43:33.070  7559  8033 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
,07-12 17:43:33.070  7559  8033 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
,07-12 17:43:33.090  3287  8035 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC),
07-12 17:43:33.090  3287  8035 D WeatherUtility: Weather sync is On
07-12 17:43:33.090  7469  7469 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:33.100  1130  1152 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,07-12 17:43:33.100  7469  8036 I DFPI.ApkInstallService: onHandleIntent,
07-12 17:43:33.100  7469  8036 I DFPI.ApkInstallService: Media Scan Finished Case 
07-12 17:43:33.100  7469  8036 I DFPI.SystemPropertiesUtil: value = HTC__102
07-12 17:43:33.100  1130  1153 I ActivityManager: Resuming delayed broadcast
07-12 17:43:33.100  7469  8036 I DFPI.ApkInstallService: deviceCID = HTC__102
07-12 17:43:33.100  7469  8036 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:33.100  7469  8036 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-12 17:43:33.100  3287  8035 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jul 12 18:43:33 GMT+02:00 2016
,07-12 17:43:33.100  3287  8035 W WSP     : [Receiver] can't get active network info
,07-12 17:43:33.100  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:33.100  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-12 17:43:33.100  1130  3392 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,07-12 17:43:33.110  7559  8037 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 17:43:33.110  7559  8037 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:33.110  7559  8037 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:33.110  7559  8037 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.110  7559  8037 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.110  7559  8037 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.110  7559  8037 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 17:43:33.110  7559  8037 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
,07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-12 17:43:33.110  1130  3850 I ActivityManager: Resuming delayed broadcast
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-12 17:43:33.110  7559  8037 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-12 17:43:33.110  7559  8037 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
,07-12 17:43:33.110  7976  7976 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@116f9fce, mServedView=org.apache.cordova.engine.SystemWebView{168bfeef VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1d228dfc
,07-12 17:43:33.110  3287  3287 V WSP     : [SyncService] no data connection, stop sync service
,07-12 17:43:33.120  7469  7469 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:33.120  7408  8034 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-12 17:43:33.120  1130  3716 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,07-12 17:43:33.120  1130  1176 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +698ms
07-12 17:43:33.130  1130  3844 I InputMethodManagerService: Disable input method client, pid=3405
07-12 17:43:33.130  1130  3844 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-12 17:43:33.130  7469  8039 I DFPI.ApkInstallService: onHandleIntent
07-12 17:43:33.130  7469  8039 I DFPI.ApkInstallService: Media Scan Finished Case 
07-12 17:43:33.130  3106  3106 I PhoneStatusBar: setImeWindowStatus(false,false)
07-12 17:43:33.130  1130  3844 I InputMethodManagerService: Enable input method client, pid=7976
,07-12 17:43:33.130  7469  8039 I DFPI.SystemPropertiesUtil: value = HTC__102
07-12 17:43:33.130  7469  8039 I DFPI.ApkInstallService: deviceCID = HTC__102
07-12 17:43:33.130  7469  8039 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:33.130  7469  8039 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-12 17:43:33.130  1130  3842 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:33.140  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:33.140  7559  7559 I SoundPicker: SoundPickerReceiver [onReceive] startService,
07-12 17:43:33.140  1130  3963 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-12 17:43:33.140  7559  8042 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 17:43:33.140  7559  8042 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:33.140  7559  8042 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:33.140  7559  8042 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:33.140  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-12 17:43:33.140  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.140  7559  8042 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:33.140  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-12 17:43:33.140  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.140  7559  8042 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-12 17:43:33.140  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-12 17:43:33.140  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 17:43:33.140  7559  8042 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-12 17:43:33.140  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
,07-12 17:43:33.140  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 17:43:33.140  7559  8042 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-12 17:43:33.150  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-12 17:43:33.150  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
,07-12 17:43:33.150  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-12 17:43:33.150  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
,07-12 17:43:33.150  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-12 17:43:33.150  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-12 17:43:33.150  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-12 17:43:33.150  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-12 17:43:33.150  7559  8042 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-12 17:43:33.150  7559  8042 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 17:43:33.150  1130  3844 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:33.160  7408  8034 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-12 17:43:33.170  1130  3392 I ActivityManager: Start proc 8043:com.htc.calendar/u0a7 for broadcast com.htc.calendar/.ProviderChangeReceiver
,07-12 17:43:33.180  1130  3716 D PMS     : releaseWL(3a761f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-12 17:43:33.180  8043  8043 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:33.180  8043  8043 W HTCLOG  : mask=0x18
07-12 17:43:33.180   578   578 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 140us total 12.141ms
07-12 17:43:33.180  7976  7976 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7976
,07-12 17:43:33.190   578   578 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 87us total 7.225ms
07-12 17:43:33.190  1130  1130 D PMS     : releaseWL(1fbd074b): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 null
,07-12 17:43:33.200   578   578 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 90us total 7.438ms
,07-12 17:43:33.200  8043  8043 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 17:43:33.210  7408  8034 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-12 17:43:33.220  8043  8043 D CalendarApplication: onCreate
,07-12 17:43:33.220  8043  8043 D ProviderChangeReceiver: ---------------------------------------------------
,07-12 17:43:33.220  8043  8043 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-12 17:43:33.220  8043  8067 D HtcAlertService: start to updateAlertNotification!
07-12 17:43:33.220  1130  3677 I ActivityManager: Killing 7309:com.htc.bgp/u0a8 (adj 15): empty #17
07-12 17:43:33.220  1130  3677 D Process : killProcessQuiet, pid=7309
07-12 17:43:33.220  1130  3677 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
,07-12 17:43:33.220  1130  3844 D PMS     : acquireWL(9b69d9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfo_proxy+
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-12 17:43:33.230   535  8069 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-12 17:43:33.230   535  8069 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 17:43:33.230   535  8069 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 17:43:33.230   535  8069 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 17:43:33.230  4222  8068 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-12 17:43:33.230  1130  3705 D PMS     : releaseWL(9b69d9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:33.250  7976  7976 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,07-12 17:43:33.290  1130  3842 I ActivityManager: Recipient 7309
,07-12 17:43:33.310  1130  5654 I art     : Explicit concurrent mark sweep GC freed 28995(1576KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.168ms total 116.040ms
,07-12 17:43:33.350  8070  8070 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:33.350  8070  8070 W HTCLOG  : mask=0x18
,07-12 17:43:33.350  1130  3963 I ActivityManager: Start proc 8070:com.htc.bgp/u0a8 for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider
,07-12 17:43:33.370  8070  8070 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 17:43:33.380  7976  8038 D jxcore_app_log: JniHelper::setJavaVM(0xab6a5b70), pthread_self() = -1402698320
,07-12 17:43:33.380  1130  3964 D PMS     : acquireWL(31f4cf38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7408 10114 null,
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 17:43:33.380  7976  8038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa7a39 added. We now have 1 listener(s)
07-12 17:43:33.380  1130  3392 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-12 17:43:33.390  7976  8038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
07-12 17:43:33.390  7976  8038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
07-12 17:43:33.390  7976  8038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:43:33.390  7976  8038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:43:33.390  7976  8038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31236e2c added. We now have 1 listener(s)
07-12 17:43:33.390  7976  8038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:43:33.390  7976  8038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:43:33.390  1130  2983 D WifiService: New client listening to asynchronous messages
07-12 17:43:33.390  7976  8038 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 17:43:33.390  7976  8038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:43:33.390  7976  8038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:43:33.390  7976  8038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:43:33.390  7976  8038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 17:43:33.400  7976  8038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:43:33.400  8070  8070 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-12 17:43:33.400  8070  8070 W HTCLOG  : mask=0x18
07-12 17:43:33.400  1130  3392 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-12 17:43:33.400  7976  8038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-12 17:43:33.400  7976  8038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:43:33.400  7976  8038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:43:33.400  7976  8038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:43:33.400  7976  8038 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:43:33.400  7976  8038 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:43:33.400  1130  1185 D PMS     : releaseHCC(395d8bcf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-12 17:43:33.400  1130  1185 D PMS     : releaseHCC(6d115eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
07-12 17:43:33.400  8070  8070 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@38924146(com.htc.providers.calendar.HtcCalendarProvider@284d4f07)
,07-12 17:43:33.420  8070  8099 D CalendarProvider2: wait start:true
,07-12 17:43:33.420  1130  3844 I ActivityManager: Delaying start of: ServiceRecord{2ebec8b9 u0 com.android.providers.calendar/.EmptyService}
,07-12 17:43:33.430  8070  8099 D CalendarProvider2: wait end:false
,07-12 17:43:33.450  4222  4222 D WearableService: callingUid 10020, callindPid: 4222
07-12 17:43:33.450  8043  8067 D HtcAlertService: No fired or scheduled alerts
07-12 17:43:33.450  8043  8067 D HtcAlertUtils: -- cancelReminderNotification --
,07-12 17:43:33.450  8043  8067 D HtcAlertUtils: broadcastExistReminder!
07-12 17:43:33.450  3186  3186 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-12 17:43:33.450  1130  3716 I ActivityManager: Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,07-12 17:43:33.470  7408  7408 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
,07-12 17:43:33.470  7408  7408 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 17:43:33.480  7408  7408 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-12 17:43:33.480  7976  7976 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
07-12 17:43:33.490  1130  1168 I ActivityManager: Waited long enough for: ServiceRecord{1fbd2f69 u0 com.aiqidi.nemo/com.reefs.service.localserver.LocalServerControllerService}
,07-12 17:43:33.490  1130  3963 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7408, uid=10114, userID:0
,07-12 17:43:33.500  1130  3844 D PMS     : releaseWL(31f4cf38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,07-12 17:43:33.500  7408  8094 I MusicLeanback: Conditions not met for autocaching.
07-12 17:43:33.500  7408  8094 I MusicLeanback: Stop autocaching.
,07-12 17:43:33.500  1130  1152 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:33.520  7168  7168 D CDMountReceiver: whether to enable CD Auto-mount: true
07-12 17:43:33.520  7168  7168 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,07-12 17:43:33.530  1130  1130 D ValidateNoPeople: setContact(com.nero.android.htc.sync,0.0,false)
,07-12 17:43:33.540  7408  7408 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-12 17:43:33.550  7408  8104 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
07-12 17:43:33.550  3186  3210 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true, isForDotMatrix: false
,07-12 17:43:33.550  7168  7168 D CDMountReceiver: enable CD Auto-mount: true
,07-12 17:43:33.560  7168  8105 D HTCUtilities: enable auto-mount
,07-12 17:43:33.560  7168  8105 I HtcMountManagerAdapter: mHtcMountManager is  null
07-12 17:43:33.560  7168  8105 I HtcMountManagerAdapter: mStorageManager is  not null
,07-12 17:43:33.560  1130  2992 D VoldConnector: SND -> {7 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,07-12 17:43:33.570  1130  2945 D VoldConnector: RCV <- {200 7 mountISO operation succeeded}
07-12 17:43:33.570  1130  2992 D MountService: mountISO: /system/etc/PCTOOL.ISO
,07-12 17:43:33.570  3106  3106 I RemoteViews: apply:com.nero.android.htc.sync 0 9 4 38,
,07-12 17:43:33.580  3106  3106 I RemoteViews: apply:com.nero.android.htc.sync 1 13 2 53,
,07-12 17:43:33.590  1130  3401 I ActivityManager: Start proc 8106:com.google.android.partnersetup/u0a23 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-12 17:43:33.590  3106  3106 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-12 17:43:33.600  8106  8106 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:33.600  8106  8106 W HTCLOG  : mask=0x18,
,07-12 17:43:33.600  1130  2940 V AlarmManager: sending alarm PendingIntent{1dc46744: PendingIntentRecord{26aee02d com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1468338213612, Int=0
,07-12 17:43:33.660  1130  3844 I ActivityManager: Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
07-12 17:43:33.660  1130  3844 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:33.660  3680  3680 E PackageActionReceiver: ACTION_PACKAGE_ADDED
,07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]PackageInstalledReceiver: PackageInstalledReceiver Received::Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.htc.mirrorlinkserver/.PackageInstalledReceiver (has extras) }
,07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]PackageInstalledReceiver: Counter : 1
07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_ADDED
07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]MirrorLinkServer: New Application installed : com.test.thalitest
07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]d: onApplicationInstalled
07-12 17:43:33.670  1130  3963 I ActivityManager: Killing 7610:com.htc.updater/u0a68 (adj 15): empty #17
07-12 17:43:33.670  1130  3963 D Process : killProcessQuiet, pid=7610
07-12 17:43:33.670  4988  4988 W [MirrorLinkServer]d: Cannot find find the  com.mirrorlink.android.app.LAUNCH intent.
07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]d: com.test.thalitest is not a MirrorLink-aware app.
07-12 17:43:33.670  1130  3963 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 ,
,07-12 17:43:33.670  3287  8132 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
07-12 17:43:33.670  3287  8132 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-12 17:43:33.670  4988  8133 I [MirrorLinkServer]d: Database Update Progress State : false,
07-12 17:43:33.670  4988  8133 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-12 17:43:33.670  4988  4988 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-12 17:43:33.670  4988  4988 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service,
,07-12 17:43:33.770  1130  3705 I ActivityManager: Recipient 7610
,07-12 17:43:33.780  3405  3405 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
,07-12 17:43:33.780  3405  3405 I ContextualWidget: package com.test.thalitest added
,07-12 17:43:33.790  3405  4039 I ContextualWidget: handleMessage, what=1003 mode=GettingOut maxcount=8
,07-12 17:43:33.790  1130  1152 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,07-12 17:43:33.790  6286  8135 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-12 17:43:33.800  6521  8122 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 193 ms
,07-12 17:43:33.810  6286  8135 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
07-12 17:43:33.810  6286  8135 W HTCLOG  : mask=0x18
,07-12 17:43:33.850  3405  4039 I ContextualWidget: MFU.onDownloadDataSetChanged,
07-12 17:43:33.850  3405  4039 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-12 17:43:33.860  3405  3405 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId c290d125-fbe3-4eb2-8ecd-f0c87fa22911, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
07-12 17:43:33.860  3405  3405 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId c290d125-fbe3-4eb2-8ecd-f0c87fa22911, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-12 17:43:33.870  1130  2992 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:33.890  1130  3850 I ActivityManager: Start proc 8136:com.htc.cs.dm/u0a88 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
,07-12 17:43:33.900  8136  8136 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 17:43:33.900  8136  8136 W HTCLOG  : mask=0x18
,07-12 17:43:33.920  7716  7772 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 17:43:33.930  1130  3401 D PMS     : acquireWL(222d48c8): PARTIAL_WAKE_LOCK  Icing 0x1 6521 10020 WorkSource{10069 com.google.android.googlequicksearchbox}
,07-12 17:43:33.970  8136  8136 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8136 dbg=false s=true,
07-12 17:43:33.970  8136  8136 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-12 17:43:33.970  1130  3963 I ActivityManager: Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
07-12 17:43:33.970  1130  3963 D Process : killProcessQuiet, pid=7667
07-12 17:43:33.970  1130  3963 I ActivityManager: Killing 7667:com.htc.autobot/u0a27 (adj 15): empty #17
07-12 17:43:33.970  1130  3963 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
07-12 17:43:33.970  1130  3842 D PMS     : releaseWL(222d48c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:34.120  1130  3705 I ActivityManager: Recipient 7667
,07-12 17:43:34.180  1130  1153 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:34.190  3376  4267 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-12 17:43:34.190  3376  4267 D PhoneApp: -- N1 =1
,07-12 17:43:34.190  3376  4267 D PhoneApp: -- N2 =0
,07-12 17:43:34.190  1130  1153 I ActivityManager: Start proc 8161:com.google.android.apps.docs/u0a90 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-12 17:43:34.190  3376  4267 D PhoneApp: -- N3 =0
,07-12 17:43:34.200  1130  3241 D PMS     : acquireWL(1c237d47): PARTIAL_WAKE_LOCK  Icing 0x1 6521 10020 WorkSource{10069 com.google.android.googlequicksearchbox}
,07-12 17:43:34.210  8161  8161 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:34.210  8161  8161 W HTCLOG  : mask=0x18
,07-12 17:43:34.230  7976  8098 W jxcore-log: Initializing JXcore engine
07-12 17:43:34.230  7976  8098 W jxcore-log: JXcore engine is ready
,07-12 17:43:34.240  6286  8135 I ApplicationLogger: canRun() : Opted Out
,07-12 17:43:34.250  3405  5300 I SocialFeedProvider: +disConnect socialManager
07-12 17:43:34.250  3405  5300 I SocialFeedProvider: disconnect socialManager
,07-12 17:43:34.260  3405  5300 I SocialFeedProvider: -disConnect socialManager
,07-12 17:43:34.270  7976  8098 W jxcore-log: Starting JXcore engine
,07-12 17:43:34.320  8161  8161 D DocsApplication: Plugin installer initialized.,
,07-12 17:43:34.330  7976  8098 W jxcore-log: Platform android
07-12 17:43:34.330  7976  8098 W jxcore-log: 
07-12 17:43:34.330  7976  8098 W jxcore-log: Process ARCH arm
07-12 17:43:34.330  7976  8098 W jxcore-log: 
07-12 17:43:34.330  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-12 17:43:34.330  3405  3869 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1b0be533 +
07-12 17:43:34.330  3405  3869 I Prism.WidgetManager: onLoadItems() +
,07-12 17:43:34.340  8161  8161 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{131b37a5 com.google.android.apps.docs}
,07-12 17:43:34.350  1130  2940 I ActivityManager: Start proc 8183:com.htc.sense.news/u0a59 for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper
,07-12 17:43:34.350  1130  2940 V AlarmManager: sending alarm PendingIntent{37322974: PendingIntentRecord{cb52e9d com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1468338214352, Int=0
,07-12 17:43:34.360  6286  8135 I ContactLogger: canRun() : Opted Out,
07-12 17:43:34.360  6286  8135 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 564 ms] updated apps [took 442 ms] updated contacts [took 122 ms]
07-12 17:43:34.360  8183  8183 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:34.360  8183  8183 W HTCLOG  : mask=0x18
,07-12 17:43:34.370  8161  8161 D TAG     : onCreate()
,07-12 17:43:34.380  8161  8161 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,07-12 17:43:34.420  8183  8183 I MultiDex: VM with version 2.1.0 has multidex support,
07-12 17:43:34.420  8183  8183 I MultiDex: install
07-12 17:43:34.420  8183  8183 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 17:43:34.420  8070  8070 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
07-12 17:43:34.430  8070  8070 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-12 17:43:34.430  1130  3963 D Process : killProcessQuiet, pid=7694
07-12 17:43:34.430  1130  3963 I ActivityManager: Killing 7694:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-12 17:43:34.430  1130  3963 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 17:43:34.440  7976  8098 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:43:34.440  7976  8098 I jxcore-log: 
,07-12 17:43:34.440  7976  8098 W jxcore-log: JXcore engine is started
07-12 17:43:34.450  1130  3842 I ActivityManager: Recipient 7694
,07-12 17:43:34.450  7976  8038 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:43:34.460  7976  7976 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:43:34.460  7976  8098 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 17:43:34.460  7976  8098 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 17:43:34.470  7976  7976 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-12 17:43:34.470  7976  7976 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 17:43:34.660  8205  8205 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-12 17:43:34.660  8205  8205 W HTCLOG  : mask=0x18
,07-12 17:43:34.670  7976  8038 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 201ms. Plugin should use CordovaInterface.getThreadPool().
07-12 17:43:34.670  1130  3392 D PMS     : acquireWL(190a6e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1130 1000 null
07-12 17:43:34.670  7976  7976 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-12 17:43:34.670  7976  7976 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 17:43:34.690  1130  3537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-12 17:43:34.690  8183  8210 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG,
07-12 17:43:34.690  8183  8210 I SocialManager[SocialBiLogHelper]: last commit ulog time 1468298547496
,07-12 17:43:34.690  8183  8210 I SocialManager[SocialBiLogHelper]: skip commit this time
07-12 17:43:34.690  1130  3401 I ActivityManager: Killing 7743:com.google.android.gm.exchange/u0a156 (adj 15): empty #17
07-12 17:43:34.690  1130  3401 D Process : killProcessQuiet, pid=7743
07-12 17:43:34.690  1130  3401 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 17:43:34.710  3405  3869 E Prism.WidgetManager: The same lists. No need to update. skip it.,
07-12 17:43:34.710  3405  3869 I Prism.WidgetManager: onLoadItems() -
07-12 17:43:34.710  3405  3869 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1b0be533 -
,07-12 17:43:34.790  1130  3844 I ActivityManager: Recipient 7743,
,07-12 17:43:34.810  3405  3405 I FeedHostManager: [onResume],
,07-12 17:43:34.810  3405  3405 I FeedProviderManager: onResume
07-12 17:43:34.810  3405  4852 I SocialFeedProvider: +onResume
07-12 17:43:34.810  3405  4852 I SocialFeedProvider: updateAccounts - Accounts is no change,
07-12 17:43:34.810  3405  4852 I SocialFeedProvider: -onResume
07-12 17:43:34.810  3405  3405 I ConnectivityHelper: [getCurrentConnectionType] no network connection
07-12 17:43:34.810  3405  3405 I ContextualWidget: onResume
07-12 17:43:34.810  3405  3405 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
,07-12 17:43:34.810  3405  4039 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-12 17:43:34.810  3405  3405 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-12 17:43:34.810  3405  3405 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-12 17:43:34.810  3405  4039 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-12 17:43:34.810  1130  1153 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-12 17:43:34.810  1130  3392 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 17:43:34.810  1130  3401 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-12 17:43:34.820  1130  1169 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-12 17:43:34.820  1130  3716 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
07-12 17:43:34.820  1130  1169 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2d345234 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-12 17:43:34.820  3106  3106 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 17:43:34.820  1130  1169 D StatusBarManagerService: hiding MENU key
07-12 17:43:34.820  3106  3106 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-12 17:43:34.820  3405  3405 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-12 17:43:34.820  3405  3405 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-12 17:43:34.830  3106  3106 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-12 17:43:34.830  1130  3964 I InputMethodManagerService: Disable input method client, pid=7976
07-12 17:43:34.830  1130  3964 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-12 17:43:34.830  1130  3964 I InputMethodManagerService: Enable input method client, pid=3405
07-12 17:43:34.830  7976  7976 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection,
,07-12 17:43:34.850  1130  1153 D PMS     : releaseWL(190a6e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-12 17:43:34.860  1130  1169 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-12 17:43:34.860  1130  1169 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2d345234 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-12 17:43:34.860  3106  3106 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 17:43:34.860  1130  1169 D StatusBarManagerService: hiding MENU key
07-12 17:43:34.860  3106  3106 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-12 17:43:34.880  1130  1168 D Process : killProcessQuiet, pid=7803
07-12 17:43:34.880  1130  1168 I ActivityManager: Killing 7803:com.htc.mobiledata:remote/u0a39 (adj 15): empty #17
07-12 17:43:34.880  1130  1168 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,07-12 17:43:34.890  3405  8212 D HtcTelephonyManager: wrong phone slot in non-dual projects
,07-12 17:43:34.900  1130  3705 I ActivityManager: Recipient 7803
,07-12 17:43:34.940  8205  8215 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-12 17:43:34.940  8205  8215 W HTCLOG  : mask=0x18
07-12 17:43:34.940  8205  8215 E cutils-trace: Error opening trace file: Permission denied (13),
,07-12 17:43:34.940  3405  8212 D HtcTelephonyManager: wrong phone slot in non-dual projects
,07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4,
07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfo_proxy+
07-12 17:43:34.950  3405  8212 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-12 17:43:34.950   535  8228 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-12 17:43:34.950   535  8228 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 17:43:34.960   535  8228 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 17:43:34.960   535  8228 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 17:43:34.960  3405  8212 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-12 17:43:34.960  3405  8212 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:34.960  3405  8212 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-12 17:43:34.960  3405  8212 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:43:34.960  3405  8212 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:34.960  3405  8212 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:34.960  3405  8212 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:34.960  3405  8212 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:34.960  3405  8212 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-12 17:43:34.960  3405  8212 W System.err: ,	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-12 17:43:34.960  3405  8212 W System.err: 	,at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
,07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-12 17:43:34.960  3405  8212 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
07-12 17:43:34.960  3405  8212 W System.err: 	... 9 more
,07-12 17:43:34.990  8205  8205 D CustomizationManager: ====startRecUseTime====,
07-12 17:43:34.990  8205  8205 D htc.customization.log.level:  is 
07-12 17:43:34.990  8205  8205 W CustomizationLogLevel: Level value is invalid, use default level 2
07-12 17:43:34.990  7976  7976 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 17:43:34.990  7976  7976 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-12 17:43:34.990  7976  7976 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:43:34.990  7976  7976 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 17:43:34.990  7976  7976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:43:34.990  7976  7976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:43:34.990  7976  7976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:43:34.990  7976  7976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:43:34.990  7976  7976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa7a39 removed from the list
07-12 17:43:34.990  7976  7976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:43:34.990  7976  7976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31236e2c removed from the list
07-12 17:43:34.990  7976  7976 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:43:34.990  7976  7976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-12 17:43:34.990  7976  7976 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:43:35.030  7976  7976 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7976,
,07-12 17:43:35.040  8205  8205 D CustomizationManager:  Read ACC file spent 0.029 (s)
,07-12 17:43:35.040  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 17:43:35.040  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__016
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__031
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:43:35.050  8205  8205 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:43:35.050  8205  8205 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = application
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = system
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = ACC
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 42507
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
,07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23420,
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 24002
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23430
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27205
,07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
,07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 17:43:35.050  8205  8205 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:43:35.050  8205  8205 D CustomizationManager:  Read CID file spent 0.063 (s)
07-12 17:43:35.050  8205  8205 D CustomizationManager:  All configurations done spent 0.063 (s)
,07-12 17:43:35.080  1130  3716 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8205, uid=2000
,07-12 17:43:35.080  1130  1168 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 17:43:35.080  1130  1168 D Process : killProcessQuiet, pid=7976
07-12 17:43:35.080  1130  1168 I ActivityManager: Killing 7976:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
07-12 17:43:35.080  1130  1168 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,07-12 17:43:35.130  1130  1187 W PackageSettings: Skipping PackageSetting{20e9136 com.example.hello/10193} due to missing metadata
,07-12 17:43:35.150   555   555 W HTCLOG  : use specified tag [Vector], func [0].
07-12 17:43:35.160   555   555 W HTCLOG  : mask=0x18
,07-12 17:43:35.190  1130  3850 I ActivityManager: Recipient 7976
07-12 17:43:35.190  1130  2983 D WifiService: Client connection lost with reason: 4
,07-12 17:43:35.190  3240  3240 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-12 17:43:35.190  3240  3240 W HTCLOG  : mask=0x18
07-12 17:43:35.190  3240  3240 E InputEventReceiver: Looper::removeFd(32) is failed, result(0), input channel 'ClientState{1e1b5dc6 uid 10000 pid 7976} (c)'
,07-12 17:43:35.240  6521  6661 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox
,07-12 17:43:35.290  1130  3850 W ActivityManager: Spurious death for ProcessRecord{3126d736 7976:com.test.thalitest/u0a0}, curProc for 7976: null,
07-12 17:43:35.290  1130  1187 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-12 17:43:35.320  3186  3186 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
,07-12 17:43:35.320  1130  2949 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000,
07-12 17:43:35.320  3186  3186 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
07-12 17:43:35.320  1130  2949 V NetworkPolicy: writePolicyLocked()
07-12 17:43:35.320  1130  2948 D PMS     : acquireWL(1e0130c2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1130 1000 null
07-12 17:43:35.330  4988  4988 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-12 17:43:35.330  4988  4988 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-12 17:43:35.340  4988  4988 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-12 17:43:35.340  4988  4988 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-12 17:43:35.350  1130  2943 W SystemReader: Cannot find grip_rejection_width, use default value instead,
07-12 17:43:35.350  1130  3401 D PMS     : acquireWL(3871ca10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
07-12 17:43:35.350  4222  4613 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 17:43:35.350  1130  3716 D PMS     : releaseWL(3871ca10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:35.360  3680  4175 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-12 17:43:35.360  3405  3405 I art     : Explicit concurrent mark sweep GC freed 45337(3MB) AllocSpace objects, 19(12MB) LOS objects, 31% free, 35MB/51MB, paused 1.009ms total 69.303ms
07-12 17:43:35.370  4988  4988 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-12 17:43:35.370  4988  4988 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-12 17:43:35.370  4988  4988 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-12 17:43:35.370  4988  4988 D [MirrorLinkServer]d: onApplicationRemoved
07-12 17:43:35.370  4988  4988 I [MirrorLinkServer]d: Package name found : com.test.thalitest
07-12 17:43:35.370  4988  8233 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-12 17:43:35.370  4988  4988 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-12 17:43:35.370  4988  4988 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-12 17:43:35.370  4988  4988 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-12 17:43:35.370  4988  4988 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-12 17:43:35.370  4988  4988 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-12 17:43:35.380  3680  4175 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-12 17:43:35.380  6286  6286 I art     : Explicit concurrent mark sweep GC freed 9497(580KB) AllocSpace objects, 1(24KB) LOS objects, 31% free, 4MB/6MB, paused 1.417ms total 70.365ms
,07-12 17:43:35.380  1130  2949 D NetworkPolicy: notifyPoliciesChangeLocked: no change
07-12 17:43:35.380  1130  2949 V NetworkPolicy: updateNetworkEnabledLocked()
07-12 17:43:35.380  1130  2949 V NetworkPolicy: updateNotificationsLocked()
,07-12 17:43:35.390  3405  4197 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-12 17:43:35.400  3680  4175 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm,
,07-12 17:43:35.400  3680  4175 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
07-12 17:43:35.410  1130  2948 D PMS     : releaseWL(1e0130c2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-12 17:43:35.410  3376  3376 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-12 17:43:35.420  1130  1167 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-12 17:43:35.420  8161  8235 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-12 17:43:35.420  8161  8235 W HTCLOG  : mask=0x18
07-12 17:43:35.420  3680  4175 E ExternalAccountType: Unsupported attribute readOnly
,07-12 17:43:35.440  6521  6661 D Icing   : Loaded CLD2 Version V2.0 - 20141016,
,07-12 17:43:35.480  1130  2992 I ActivityManager: Start proc 8239:com.google.android.apps.plus/u0a126 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-12 17:43:35.490  8161  8161 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 17:43:35.490  8239  8239 W HTCLOG  : use specified tag [FDManager], func [0].
,07-12 17:43:35.490  8239  8239 W HTCLOG  : mask=0x18
,07-12 17:43:35.500  1130  1167 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 17:43:35.500  1130  1130 W PackageManager: Unable to load service info ResolveInfo{2293870f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-12 17:43:35.500  1130  1130 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-12 17:43:35.500  1130  1130 W PackageManager: ,	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:43:35.500  1130  1130 W PackageManager: ,	at android.os.Handler.dispatchMessage(Handler.java:95),
07-12 17:43:35.500  1130  1130 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:35.500  1130  1130 W PackageManager: 	,at com.android.server.SystemServer.run(SystemServer.java:331),
07-12 17:43:35.500  1130  1130 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-12 17:43:35.500  1130  1130 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825),
,07-12 17:43:35.530  1130  1187 I art     : Explicit concurrent mark sweep GC freed 30922(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 2.284ms total 225.630ms
,07-12 17:43:35.530  8239  8239 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 17:43:35.560  8205  8205 I art     : System.exit called, status: 0,
07-12 17:43:35.560  8205  8205 W HTCLOG  : use specified tag [Vector], func [0].
07-12 17:43:35.560  8205  8205 W HTCLOG  : mask=0x18
,07-12 17:43:35.580  6521  6661 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF,
,07-12 17:43:35.590  3350  3350 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-12 17:43:35.600  1130  3850 D PMS     : releaseWL(1c237d47): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:35.610  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
07-12 17:43:35.610  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-12 17:43:35.670  1130  1130 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-12 17:43:35.780  1130  3850 D PMS     : acquireWL(288d3cb6): PARTIAL_WAKE_LOCK  AsyncService 0x1 8239 10126 null
,07-12 17:43:35.810  1130  3392 D PMS     : releaseWL(288d3cb6): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-12 17:43:35.840  8161  8161 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-12 17:43:35.850  1130  3844 D Process : killProcessQuiet, pid=7829
07-12 17:43:35.850  1130  3844 I ActivityManager: Killing 7829:com.htc.mobiledata/u0a39 (adj 15): empty #17
07-12 17:43:35.850  1130  3844 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 17:43:35.860  6521  8275 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-12 17:43:35.860  6521  8274 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-12 17:43:35.980  1130  3705 I ActivityManager: Recipient 7829,
,07-12 17:43:36.060  1130  1168 I ActivityManager: Waited long enough for: ServiceRecord{3173213f u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,07-12 17:43:36.060  6521  8275 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-12 17:43:36.070  6521  8275 E Vision  : Failed to find package com.test.thalitest
,07-12 17:43:36.070  6521  8275 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-12 17:43:36.080  6521  6521 D AsyncTaskServiceImpl: Submit a task: nwp
,07-12 17:43:36.080  1130  3716 I ActivityManager: Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,07-12 17:43:36.090  1130  3241 D PMS     : acquireWL(17cc9489): PARTIAL_WAKE_LOCK  Icing 0x1 6521 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:36.090  1130  3844 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:36.100  6521  7791 E WorkSourceUtil: Could not find package: com.test.thalitest
,07-12 17:43:36.100  6521  6661 D nwp     : Processing package: com.test.thalitest
,07-12 17:43:36.100  6521  6652 E Icing   : Package com.test.thalitest not found
,07-12 17:43:36.100  6521  6661 W nwp     : Failed to find package com.test.thalitest
,07-12 17:43:36.100  6521  7247 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-12 17:43:36.100  6521  7247 E IcingInternalCorpora: Failed to open Apps corpus file.
,07-12 17:43:36.110  6521  7247 E IcingInternalCorpora: Failed to append to component name file.
,07-12 17:43:36.110  1130  3241 D PMS     : releaseWL(17cc9489): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-12 17:43:36.160  1130  3394 I ActivityManager: Start proc 8280:com.android.vending/u0a57 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,07-12 17:43:36.170  1130  3842 D PMS     : acquireWL(3059839a): PARTIAL_WAKE_LOCK  Icing 0x1 6521 10020 WorkSource{10020 com.google.android.gms}
,07-12 17:43:36.180  8280  8280 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 17:43:36.180  8280  8280 W HTCLOG  : mask=0x18
,07-12 17:43:36.200  6521  7247 W IcingInternalCorpora: Failed to write entries to Apps corpus file.
,07-12 17:43:36.290  1130  3716 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=8280, uid=10057, userID:0
,07-12 17:43:36.290  8280  8280 W global  : [apache-http] Connection GC has been deprecated!
,07-12 17:43:36.310  8280  8280 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-12 17:43:36.370  8280  8280 E PlayRollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,07-12 17:43:36.380  8280  8280 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.,
,07-12 17:43:36.390  8280  8280 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:43:36.390  8280  8322 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-12 17:43:36.390  8280  8322 W HTCLOG  : mask=0x18
07-12 17:43:36.390  8280  8280 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:43:36.390  8280  8322 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at com.go,ogle.android.finsky.j.av.iterator(SourceFile:15316)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.390  8280  8322 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: Failed to write crash file cnt=0 ts=0 cause=null.
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash806713: open failed: EROFS (Read-only file system)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at com.google.android.finsky.a.a(SourceFile:180)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at com.google.android.finsky.a.uncaughtException(SourceFile:98)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.400  8280  8322 W Finsky.CrashDetector: 	... 6 more
07-12 17:43:36.400  8280  8322 E AndroidRuntime: FATAL EXCEPTION: libraries-thread
07-12 17:43:36.400  8280  8322 E AndroidRuntime: Process: com.android.vending, PID: 8280
07-12 17:43:36.400  8280  8322 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at com.google.android.finsky.j.av.iterator(SourceFile:15316)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.400  8280  8322 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.400  1130  3677 E ActivityManager: App crashed! Process: com.android.vending
,07-12 17:43:36.410  1130  3963 D PMS     : acquireWL(32f9e2fd): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 7874 10102 null
07-12 17:43:36.420  8280  8280 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
07-12 17:43:36.410  1130  2992 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=8280, uid=10057, userID:0
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.420  8280  8324 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: Can't write: system_app_crash
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.410  1130  8323 E DropBoxManagerService: 	... 5 more
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.430  8280  8325 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: crash in the same process: AsyncTask #1
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.420  8280  8324 E AndroidRuntime_2_crash: 	... 4 more
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: crash in the same process: AsyncTask #2
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.430  8280  8325 E AndroidRuntime_3_crash: 	... 4 more
07-12 17:43:36.440  1130  1152 I ActivityManager: Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,07-12 17:43:36.460  1130  3842 I ActivityManager: Delaying start of: ServiceRecord{317b0b69 u0 com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService}
07-12 17:43:36.470  1130  3842 D PMS     : releaseWL(32f9e2fd): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-12 17:43:36.480  1130  1169 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-12 17:43:36.480  3106  3106 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 17:43:36.480  1130  1169 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{396e856d u0 Application Error: com.android.vending}
07-12 17:43:36.480  3106  3106 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 17:43:36.480  1130  1169 D StatusBarManagerService: hiding MENU key
,07-12 17:43:36.490  8280  8304 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,07-12 17:43:36.590  1130  1168 I ActivityManager: Waited long enough for: ServiceRecord{327baf04 u0 com.nero.android.htc.sync/.PowerDisconService},
07-12 17:43:36.590  1130  1168 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:36.600  3794  3958 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
,07-12 17:43:36.610  3405  3405 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
07-12 17:43:36.610  3405  3405 I ContextualWidget: package com.google.android.gms changed,
07-12 17:43:36.610  3287  8331 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,07-12 17:43:36.610  3287  8331 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-12 17:43:36.610  3794  3958 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
07-12 17:43:36.610  3794  3958 W HTCLOG  : mask=0x18
07-12 17:43:36.610  3794  3958 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x558eefa820
07-12 17:43:36.610  3405  4039 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
07-12 17:43:36.620  3794  3958 W ContactsProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2162)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11533)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1819)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.620  3794  3958 W ContactsProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:43:36.640  6286  8333 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 17:43:36.650  3405  4039 I ContextualWidget: MFU.onDataSetChanged,
07-12 17:43:36.650  1130  2992 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
07-12 17:43:36.650  3405  4039 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-12 17:43:36.650  3405  4039 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-12 17:43:36.650  3405  4039 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-12 17:43:36.650  3405  4039 I ContextualWidget: sync all data, download=1 recommend=4
07-12 17:43:36.650  3405  4039 I ContextualWidget: sync all data, mode=GettingOut count=10
07-12 17:43:36.650  3405  4039 I ContextualWidget: notifyDataChanged, list size 8
07-12 17:43:36.650  3405  3405 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
07-12 17:43:36.650  3405  3734 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-12 17:43:36.660  1130  3705 D PMS     : acquireWL(32412bb4): PARTIAL_WAKE_LOCK  AsyncService 0x1 8239 10126 null,
07-12 17:43:36.660  1130  1152 D PMS     : releaseWL(32412bb4): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-12 17:43:36.670  1130  3964 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:36.680  6521  8275 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 17:43:36.680  3405  8332 I ContextualWidget: com.test.thalitest is not installed
07-12 17:43:36.680  3405  8332 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-12 17:43:36.690  3405  8332 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
07-12 17:43:36.690  3405  8332 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-12 17:43:36.690  3405  8332 W HTCLOG  : mask=0x18
07-12 17:43:36.690  3405  8332 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac2fc2e8
07-12 17:43:36.690  3405  8332 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
07-12 17:43:36.690  3405  8332 E AndroidRuntime: Process: com.htc.launcher, PID: 3405
07-12 17:43:36.690  3405  8332 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2129)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageChanged(HtcContextualWidgetService.java:304)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:186)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.690  3405  8332 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.690  1130  3844 E ActivityManager: App crashed! Process: com.htc.launcher
07-12 17:43:36.690  1130  3844 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-12 17:43:36.700  1130  3844 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-12 17:43:36.700  1130  3844 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-12 17:43:36.700  1130  3844 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-12 17:43:36.700  1130  3844 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.700  1130  3844 W System.err: 	... 14 more
07-12 17:43:36.700  1130  3844 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-12 17:43:36.700  1130  3844 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-12 17:43:36.700  1130  3844 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-12 17:43:36.700  1130  3844 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-12 17:43:36.700  1130  3844 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-12 17:43:36.700  1130  3844 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.700  1130  3844 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.700  1130  3844 W System.err: 	... 14 more
07-12 17:43:36.710  6286  8333 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-12 17:43:36.710  6286  8333 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-12 17:43:36.710  6286  8333 W HTCLOG  : mask=0x18
07-12 17:43:36.710  6286  8333 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x558ef8b700
07-12 17:43:36.720  1130  3241 I ActivityManager: Start proc 8336:com.htc.autobot/u0a27 for broadcast com.htc.autobot/.AlarmReceiver
07-12 17:43:36.720  1130  3844 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
07-12 17:43:36.720  1130  3844 D PMS     : acquireWL(34c94b52): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1130 1000 null
07-12 17:43:36.720  1130  8349 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-12 17:43:36.720  1130  8349 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1468338216735.dbox_tmp: open failed: EROFS (Read-only file system)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.720  1130  8349 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.720  1130  8349 E ErrorReport: 	... 4 more
,07-12 17:43:36.730  1130  3537 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-12 17:43:36.730  1130  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.730  1130  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.730  1130  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-12 17:43:36.730  1130  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-12 17:43:36.730  8336  8336 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-12 17:43:36.730  8336  8336 W HTCLOG  : mask=0x18
07-12 17:43:36.730  1130  3537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-12 17:43:36.730  1130  3537 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.730  1130  3537 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.730  1130  3537 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.730  1130  3537 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.730  1130  3537 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.730  1130  3537 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.730  1130  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.730  1130  3537 W System.err: 	... 12 more
07-12 17:43:36.740   571   571 I art     : Explicit concurrent mark sweep GC freed 8636(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 138us total 24.385ms
07-12 17:43:36.740  6286  8333 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,07-12 17:43:36.750  6286  8333 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-12 17:43:36.750  6286  8333 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6286,
07-12 17:43:36.750  6286  8333 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	,at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: ,	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.750  6286  8333 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.750  6521  6661 I Icing   : updateResources: need to parse owf{com.google.android.gms}
07-12 17:43:36.750  3405  3405 I FeedHostManager: [onPause]
07-12 17:43:36.750  3405  3405 I FeedProviderManager: onPause
07-12 17:43:36.750  3405  3405 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@23b4f8eb
07-12 17:43:36.750  3405  4852 I SocialFeedProvider: +onPause
07-12 17:43:36.750  3405  4852 I SocialFeedProvider: -onPause
,07-12 17:43:36.760  1130  3964 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-12 17:43:36.760   571   571 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 142us total 17.269ms
,07-12 17:43:36.760  6521  8275 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,07-12 17:43:36.770  1130  8362 E DropBoxManagerService: Can't write: system_app_crash
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.770  1130  8362 E DropBoxManagerService: 	... 5 more
07-12 17:43:36.770  3405  3405 I ContextualWidget: onPause
07-12 17:43:36.770  3405  3405 I ContextualWidget: notifyWidgetDeactive
,07-12 17:43:36.770  6521  7247 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-12 17:43:36.770  6521  7247 E IcingInternalCorpora: Failed to open Apps corpus file.
07-12 17:43:36.770  6521  7247 E IcingInternalCorpora: Failed to append to component name file.
,07-12 17:43:36.780  6521  7247 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,07-12 17:43:36.780  1130  3705 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,07-12 17:43:36.780  1130  3705 V WindowManager: addAppToken: AppWindowToken{d34c050 token=Token{38a0f613 ActivityRecord{13972d02 u0 com.htc.launcher/.Launcher t125}}} to stack=0 task=125 at 0
07-12 17:43:36.780   571   571 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 112us total 19.258ms
,07-12 17:43:36.790  1130  3537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-12 17:43:36.790  8336  8336 D AlarmReceiver: ACTION_RESTART_INTENT
,07-12 17:43:36.790  3405  3405 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@16514c01 for type 0
07-12 17:43:36.790  3405  3405 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@16514c01 for type 1
07-12 17:43:36.790  3405  3405 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@16514c01 for type 3
07-12 17:43:36.790  3405  3405 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@16514c01 for type 2
,07-12 17:43:36.800  6521  8279 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationT,ask.run(BaseAsyncOperationService.java:177)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.800  6521  8279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: Couldn't open games_3a3529a.db for writing (will try read-only):
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-12 17:43:36.8,00  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.800  6521  8279 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.800  6521  8279 W SQLiteOpenHelper: Opened games_3a3529a.db in read-only mode
07-12 17:43:36.810  1130  3241 I ActivityManager: Delay finish: com.htc.autobot/.AlarmReceiver
07-12 17:43:36.810  3405  3405 I OrientationManager: [release]
07-12 17:43:36.810  3405  3405 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20
07-12 17:43:36.810  3405  3405 I ContextualWidget: onDestroy
07-12 17:43:36.810  8336  8336 D LocalBluetoothProfile: getPriorityOnValue = 100
07-12 17:43:36.810  8336  8336 D LocalBluetoothProfile: getPriorityOffValue = 0
07-12 17:43:36.810  3405  4039 I ContextualWidget: handleMessage, what=1030 mode=GettingOut maxcount=8
07-12 17:43:36.810  3405  4039 I ContextualWidget: release
07-12 17:43:36.820  6521  7247 W IcingInternalCorpora: Failed to write entries to Apps corpus file.
07-12 17:43:36.830  8336  8336 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
07-12 17:43:36.830  8336  8336 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
07-12 17:43:36.830  3405  3405 I ContextualWidget: new instance com.htc.launcher.htcwidget.HtcContextualWidgetController@16e3f47
07-12 17:43:36.830  3405  3405 I ContextualWidget: unlockModeChange
07-12 17:43:36.840  3405  3405 I ContextualWidget: notifyWidgetDeactive
07-12 17:43:36.840  6521  8365 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-12 17:43:36.840  6521  8365 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-12 17:43:36.840  6521  8365 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-12 17:43:36.840  6521  8365 I GCore-Chimera-Crash: ==
07-12 17:43:36.840  6521  8365 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-12 17:43:36.840  1130  3241 I ActivityManager: Delaying start of: ServiceRecord{24c49414 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,07-12 17:43:36.840  6521  8365 E AndroidRuntime: FATAL EXCEPTION: GamesProviderWorker,
07-12 17:43:36.840  6521  8365 E AndroidRuntime: Process: com.google.android.gms, PID: 6521
07-12 17:43:36.840  6521  8365 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1730)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1651)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.840  6521  8365 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.840  1130  3401 E ActivityManager: App crashed! Process: com.google.android.gms
,07-12 17:43:36.850  1130  8370 E DropBoxManagerService: Can't write: system_app_crash
,07-12 17:43:36.850  1130  8370 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:36.850  1130  8370 E DropBoxManagerService: 	... 5 more
,07-12 17:43:36.870  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@5720d24 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.870  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@5720d24 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.870  3405  3405 E ActivityThread: ,	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:325)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedAdapter.<init>(CalendarFeedAdapter.java:98)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedProvider.onCreate(CalendarFeedProvider.java:19)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-12 17:43:36.870  3405  3405 E ActivityThread: ,	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.870  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@6b4b0b6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.870  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@6b4b0b6 that was originally registered here. Are you missing a call to unregisterReceiver()?
,07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.870  3405  3405 E ActivityThread: ,	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:674)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64),
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194),
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.870  3405  3405 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
,07-12 17:43:36.880  8336  8371 D HtcModeClient: start the htcmodeservice thread,
07-12 17:43:36.880  8336  8371 D HtcModeClient: initCanAgent
,07-12 17:43:36.880  8336  8371 I CANMesgAgentLocalSocket: CANAgent Id = 0,
,07-12 17:43:36.890  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@8a7c648 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@8a7c648 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: 	,at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
,07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:817)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.890  3405  3405 E ActivityThread: ,	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.890  3405  3405 E ActivityThread: ,	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:43:36.890  8336  8371 D HtcModeClient: sense info: version = none, id = 2
07-12 17:43:36.890  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@c6838c7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@c6838c7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:839)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.890  3405  3405 E ActivityThread: ,	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	,at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:43:36.890  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@e1a51a9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@e1a51a9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:153)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8371 D HtcModeClient: display info: width = 1080, height = 1776
07-12 17:43:36.890  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@e54d790 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedPro,vider$1@e54d790 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.feed.local.getstarted.GetStartedFeedProvider.onCreate(GetStartedFeedProvider.java:75)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.890  3405  3405 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.900  8336  8371 D HtcModeClient: display info: mode = 10
07-12 17:43:36.900  8336  8336 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
07-12 17:43:36.900  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@f30943a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@f30943a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:98)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: BT_TURNON_BYME = false
07-12 17:43:36.900  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@16f10130 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@16f10130 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:152)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: CONNECTION_READY = false
07-12 17:43:36.900  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@1783ba06 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@1783ba06 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:826)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-12 17:43:36.900  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@18b1161d that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@18b1161d that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:847)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.900  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-12 17:43:36.910  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@1c9d5f65 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@1c9d5f65 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:95)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: PHONE_PULGIN = false
07-12 17:43:36.910  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@277e7051 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@277e7051 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:617)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: Force_AWAKE = false
07-12 17:43:36.910  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@31898ce1 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@31898ce1 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:822)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: PHONE_PULGIN = true
07-12 17:43:36.910  3405  3405 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3a96fef4 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3a96fef4 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:843)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:36.910  3405  3405 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:36.900  8336  8336 D HtcModeClient: connectState: POWERCONNECTED_READY = true
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: startListening(),set useForground = true
07-12 17:43:36.910  8336  8373 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-12 17:43:36.910  8336  8373 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGE,T_ENABLED
07-12 17:43:36.920  3405  3405 I OrientationManager: [init] currentOrienation: 1
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-12 17:43:36.920  3405  3405 E ResourceType: Style contains key with bad entry: 0x01010504
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-12 17:43:36.920  3405  3405 W HtcWrapConfigurationActivity: no reset icon com.htc.launcher.Launcher@1512c09d, false
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-12 17:43:36.920  3405  3405 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@1f62a2e0 for type 0
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-12 17:43:36.920  3405  3405 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@1f62a2e0 for type 1
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-12 17:43:36.920  3405  3405 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@1f62a2e0 for type 3
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-12 17:43:36.920  3405  3405 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@1f62a2e0 for type 2
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-12 17:43:36.920   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-12 17:43:36.920   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=3 alpha=255 mask=-1 flags=0x220000 id=8
07-12 17:43:36.930  1130  3842 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-12 17:43:36.920   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 17:43:36.930  1130  3842 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-12 17:43:36.920   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 17:43:36.920   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
07-12 17:43:36.920   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 17:43:36.920   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 17:43:36.920   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
07-12 17:43:36.920   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 17:43:36.920   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 17:43:36.920   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-12 17:43:36.920   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 17:43:36.920   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 17:43:36.920   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 17:43:36.920   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 17:43:36.940  3405  3405 I ContextualWidget: onCreate
07-12 17:43:36.940  3405  8368 I ContextualWidget: handleMessage, what=1029 mode=GettingOut maxcount=8
07-12 17:43:36.940  3405  8368 I ContextualWidget: initialize()
07-12 17:43:36.940  3405  3405 W ResourceType: Invalid package identifier when getting bag for resource number 0x00000014
07-12 17:43:36.950  3405  3405 D AbsListView:  setHtcScrollEnabled item height = 190
,07-12 17:43:36.950  3405  3405 I FeedScrollGridView: velocity 0.850000
07-12 17:43:36.960  1130  1168 I ActivityManager: Start proc 8374:com.htc.widget.hmsproc2/u0a36 for broadcast com.htc.widget.weatherclock/.WeatherTransClock4x1
07-12 17:43:36.960  3287  3348 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_address
07-12 17:43:36.970  8374  8374 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 17:43:36.970  8374  8374 W HTCLOG  : mask=0x18
,07-12 17:43:36.990  3405  3405 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-12 17:43:36.990  3405  3405 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-12 17:43:36.990  3405  3405 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-12 17:43:36.990  3405  3405 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-12 17:43:36.990  3405  3405 D HtcFooter: layerDrawableIndex = 0
,07-12 17:43:37.000   589   589 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-12 17:43:37.000  3405  3405 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk is neither a directory nor file (type=1).
,07-12 17:43:37.000  3405  3405 D HtcThemeUtils: AssetMaanger addAssetPath WeatherClock fail!
,07-12 17:43:37.010  3405  3405 I FeedActionBar: updateLastUpdatedTime(in String) LAST UPDATED 1:00,
,07-12 17:43:37.030   550  8398 E MM_OSAL : FileSource::FileSource,
07-12 17:43:37.030   550  8398 E MM_OSAL : FileSource::FileSource m_bEveryThingOK 1
07-12 17:43:37.030   550  8398 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/mmosal_logmask.cfg , Mode 0
07-12 17:43:37.030   550  8398 E MM_OSAL : Open or read fail on /data/mmosal_logmask.cfg. Possible permission denied issue. Looking for /data/misc/media/mmosal_logmask.cfg
,07-12 17:43:37.030  3405  3405 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false,
07-12 17:43:37.030  3405  3405 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-12 17:43:37.040  3405  4141 I BlinkFeedStateMonitor: checkState, feed:true, subsribed:true, loc:false
,07-12 17:43:37.040  3405  3405 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-12 17:43:37.040  3405  3405 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-12 17:43:37.040  3405  3405 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20,
,07-12 17:43:37.070  3405  3405 I PagedView: IndicatorPagedView.nCapability with type count = 2 and capability = 20,
,07-12 17:43:37.080  3405  3405 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-12 17:43:37.080  3405  3405 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-12 17:43:37.090   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 17:43:37.090   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 17:43:37.090   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 17:43:37.090   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 17:43:37.090   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 17:43:37.090   498   498 E qdoverlay: MdpCtrl close error in unset
,07-12 17:43:37.090  3405  3405 D CoworkInterfaceListener: loadMethod() = true
,07-12 17:43:37.090  3405  3405 D CoworkInterfaceListener: IsSecure: 1
07-12 17:43:37.090  3405  3405 D CoworkInterfaceListener: IsDuggable: 0
07-12 17:43:37.090  3405  3405 D CoworkInterfaceListener: isTestable: false
07-12 17:43:37.090  3405  3405 D CoworkInterfaceListener: Enable CIListener: false
,07-12 17:43:37.110  3405  3405 I ContextualWidget: onResume
07-12 17:43:37.110  3405  3405 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-12 17:43:37.110  3405  3405 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-12 17:43:37.110  3405  3405 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-12 17:43:37.110  3405  3734 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-12 17:43:37.120  3405  3869 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-12 17:43:37.120  3405  3869 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1b0be533 +
07-12 17:43:37.120  3405  3869 I Prism.WidgetManager: onLoadItems() +

```
