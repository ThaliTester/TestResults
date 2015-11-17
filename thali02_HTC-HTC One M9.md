#### Test 503880190437b9b_thali02_HTC-HTC One M9 Logs


```--------- beginning of system
11-17 18:00:58.720  1078  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2349, uid=10020, userID:0
11-17 18:00:58.720  1078  1607 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2349, uid=10020, userID:0
11-17 18:00:58.720  1078  1927 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2349, uid=10020, userID:0
11-17 18:00:58.720  1078  1836 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2349, uid=10020, userID:0
--------- beginning of main
11-17 18:00:58.890  1980  2317 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
11-17 18:00:58.900  1078  1331 W SystemReader: Cannot find grip_rejection_width, use default value instead
11-17 18:00:58.900  1078  1836 D PMS     : acquireWL(c800e20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4986 10102 null
11-17 18:00:58.910  1980  2317 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:00:58.910  1818  2054 W Launcher.IconCache: error loading icon ActivityInfo{30db4e13 com.google.android.gms.app.settings.GoogleSettingsActivity}
11-17 18:00:58.920  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
11-17 18:00:58.920  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:00:58.920  1078  1110 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
11-17 18:00:58.920  1818  1818 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
11-17 18:00:58.930  1608  5339 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
11-17 18:00:58.930  1608  5339 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
11-17 18:00:58.930  1818  1818 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
11-17 18:00:58.940  1980  2317 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
11-17 18:00:58.950  1774  1774 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
11-17 18:00:58.950  1078  1718 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
11-17 18:00:58.950  3800  5341 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
11-17 18:00:58.950  1078  1836 D PMS     : releaseWL(c800e20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
11-17 18:00:58.960  1078  1097 D Process : killProcessQuiet, pid=4652
11-17 18:00:58.960  1078  1927 I ActivityManager: Resuming delayed broadcast
11-17 18:00:58.960  1078  1097 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:00:58.960  1078  1097 I ActivityManager: Killing 4652:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
11-17 18:00:58.970  1818  1818 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
11-17 18:00:58.980  1774  1946 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
11-17 18:00:58.980  1774  1946 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
11-17 18:00:58.980  1980  2317 E ExternalAccountType: Unsupported attribute readOnly
11-17 18:00:59.040  1078  1607 I ActivityManager: Recipient 4652
11-17 18:00:59.050  1078  1078 W PackageManager: Unable to load service info ResolveInfo{4c452b9 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:00:59.050  1078  1078 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:00:59.050  1078  1078 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
11-17 18:00:59.070  1078  1607 D Process : killProcessQuiet, pid=4652
11-17 18:00:59.070  1078  1607 W libprocessgroup: failed to open /acct/uid_1000/pid_4652/cgroup.procs: No such file or directory
11-17 18:00:59.070  1078  1607 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:00:59.070  1078  1614 D PMS     : acquireWL(18d77ac8): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.080  1078  1721 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
11-17 18:00:59.140  1078  1078 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
11-17 18:00:59.170  2091  2091 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
11-17 18:00:59.190  1078  1110 D LocationProviderProxy: applying state to connected service
11-17 18:00:59.190  1818  1818 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
11-17 18:00:59.230  1078  1913 I art     : Explicit concurrent mark sweep GC freed 23075(1108KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.917ms total 134.075ms
11-17 18:00:59.230  1078  1913 D PMS     : acquireWL(d4491b): PARTIAL_WAKE_LOCK  AsyncService 0x1 5195 10126 null
11-17 18:00:59.230  1078  1721 D PMS     : releaseWL(18d77ac8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.230  1078  1830 D PMS     : releaseWL(d4491b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
11-17 18:00:59.230  1078  2135 D PMS     : acquireWL(2e8b8ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 2091 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.230  1078  1614 I ActivityManager: Resuming delayed broadcast
11-17 18:00:59.240  1078  1718 D PMS     : releaseWL(2e8b8ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.240  1078  1141 D PMS     : acquireWL(14faabf6): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.260  2349  5345 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
11-17 18:00:59.260  2349  5345 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
11-17 18:00:59.270  2349  4027 I Icing   : updateResources: need to parse f{com.google.android.gms}
11-17 18:00:59.290  2091  2091 I art     : Explicit concurrent mark sweep GC freed 16836(1102KB) AllocSpace objects, 14(280KB) LOS objects, 43% free, 5MB/9MB, paused 1.413ms total 49.893ms
11-17 18:00:59.290  1078  1110 D LocationProviderProxy: applying state to connected service
11-17 18:00:59.290  2091  2091 V GmsNetworkLocationProvi: DISABLE
11-17 18:00:59.300  1078  1927 D PMS     : acquireWL(9a664cd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2091 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.300  1078  1110 D PMS     : acquireWL(121d9182): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 2091 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.300  1078  1912 D PMS     : releaseWL(9a664cd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.300  1078  1721 D PMS     : releaseWL(121d9182): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.300  1078  1078 D PMS     : acquireWL(578c093): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2091 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.300  1078  1097 D PMS     : releaseWL(578c093): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.310  1078  1721 D PMS     : releaseWL(14faabf6): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.310  1078  1927 D PMS     : acquireWL(394180c9): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.320  1078  1836 D PMS     : releaseWL(394180c9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.320  1078  1607 D PMS     : acquireWL(864d2ef): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.330  1078  1614 D PMS     : releaseWL(864d2ef): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.340  1078  1912 D PMS     : acquireWL(5586085): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.360  1078  1836 D PMS     : releaseWL(5586085): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.370  1078  1927 D PMS     : acquireWL(d55af0b): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.370  1078  1912 D PMS     : releaseWL(d55af0b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.380  1078  1098 D PMS     : acquireWL(32438001): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.380  1078  1830 D PMS     : releaseWL(32438001): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.380  1078  1911 D PMS     : acquireWL(f2e30e7): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.390  1078  1721 D PMS     : releaseWL(f2e30e7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.390  1078  1836 D PMS     : acquireWL(17671b3d): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.400  1078  1607 D PMS     : releaseWL(17671b3d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.400  1078  1097 D PMS     : acquireWL(2a22f483): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.410  1078  1718 D PMS     : releaseWL(2a22f483): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:00:59.440  3800  5341 I ApplicationLogger: canRun() : Opted Out
11-17 18:00:59.440  3800  5341 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 491 ms] updated apps [took 491 ms] 
11-17 18:00:59.500  1818  1818 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8
,11-17 18:01:00.000  1078  1328 D PMS     : acquireWL(37b43600): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1078 1000 WorkSource{1000}
11-17 18:01:00.000  1078  1328 V AlarmManager: sending alarm PendingIntent{242f2e39: PendingIntentRecord{1423c7e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=49098, Int=0
11-17 18:01:00.020  1078  1078 D PMS     : releaseWL(37b43600): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
11-17 18:01:00.030  1431  2232 I ClockController: schedule update now=1447779660031 next=59969
11-17 18:01:00.030  1431  1431 I Clock   : updateClock:18:01 Europe/Brussels
11-17 18:01:00.030  1431  1431 I Clock   : updateClock:18:01 Europe/Brussels
11-17 18:01:00.030  1431  1431 I Clock   : updateClock:18:01 Europe/Brussels
11-17 18:01:00.050  1431  2742 D WeatherUtility: Weather sync is On
11-17 18:01:00.050  1431  2742 W WeatherTimeKeeper: [refreshWeatherData] no weather data
11-17 18:01:00.070  4891  5327 I HtcModeClient: handler message = 4011
11-17 18:01:00.070  4891  5327 D HtcModeClient: getConnectionCheckCount first 0
11-17 18:01:00.070  4891  5327 D HtcModeClient: getConnectionCheckCount count = 2
11-17 18:01:00.070  4891  5327 E HtcModeClient: Check connection and retry 3 times.
11-17 18:01:00.070  4891  5327 D HtcModeClient: setConnectionCheckCount count = 3
11-17 18:01:00.070  4891  5327 D HtcModeClient: setupRestart delayedTime = 3000
11-17 18:01:00.070  4891  4891 D HtcModeClient: setBtPriority priority = on
11-17 18:01:00.070  4891  4891 D HtcModeClient: unbindBlueToothService
11-17 18:01:00.070  4891  4891 D HtcModeClient: Don't start project servcice
11-17 18:01:00.070  4891  4891 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
11-17 18:01:00.070  4891  4891 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:01:00.070  4891  4891 D SilentMusic: call stop
11-17 18:01:00.070  4891  4891 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
11-17 18:01:00.070  4891  5328 W CANMesgAgentLocalSocket: read the terminate packet, so break
11-17 18:01:00.080  4891  4891 D HtcModeClient: onDestroy
11-17 18:01:00.100  1078  1607 D Process : killProcessQuiet, pid=4697
11-17 18:01:00.100  1078  1607 I ActivityManager: Killing 4697:com.htc.themepicker/u0a59 (adj 15): empty #17
11-17 18:01:00.100  1078  1607 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:01:00.250  1078  1097 I ActivityManager: Recipient 4697
11-17 18:01:00.310  1078  1097 D Process : killProcessQuiet, pid=4697
11-17 18:01:00.310  1078  1097 W libprocessgroup: failed to open /acct/uid_10059/pid_4697/cgroup.procs: No such file or directory
11-17 18:01:00.310  1078  1097 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:00.370  5347  5350 E cutils-trace: Error opening trace file: Permission denied (13)
11-17 18:01:00.420  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
11-17 18:01:00.420  1818  2054 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@30f87b90 +
11-17 18:01:00.420  1818  2054 I Prism.WidgetManager: onLoadItems() +
11-17 18:01:00.450  1818  2054 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
11-17 18:01:00.450  5347  5347 D CustomizationManager: ====startRecUseTime====
11-17 18:01:00.450  5347  5347 D htc.customization.log.level:  is 
11-17 18:01:00.450  5347  5347 W CustomizationLogLevel: Level value is invalid, use default level 2
11-17 18:01:00.510  5347  5347 D CustomizationManager:  Read ACC file spent 0.042 (s)
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:01:00.520  5347  5347 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:01:00.520  5347  5347 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 42507
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 21902
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23420
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 22299
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 24002
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23210
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23205
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23806
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23430
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23408
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 27205
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23210:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:01:00.520  5347  5347 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:01:00.520  5347  5347 D CustomizationManager:  Read CID file spent 0.076 (s)
11-17 18:01:00.520  5347  5347 D CustomizationManager:  All configurations done spent 0.076 (s)
11-17 18:01:00.560  1078  1913 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5347 on display 0
11-17 18:01:00.570  1078  1149 D PMS     : acquireHCC(3f1655df): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1078 1000 null
11-17 18:01:00.570  1078  1913 W asset   : Copying FileAsset 0x55adc13c20 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:01:00.570  1078  1149 D PMS     : acquireHCC(3426b22c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1078 1000 null
11-17 18:01:00.570  1078  1136 I AnimationUtil: isHTCRecent(HelloWorld/Recent screens.)/0
11-17 18:01:00.580  1078  1913 D PMS     : acquireWL(1462c518): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1078 1000 null
11-17 18:01:00.580  1818  1818 I FeedHostManager: [onPause]
11-17 18:01:00.580  1818  1818 I FeedProviderManager: onPause
11-17 18:01:00.580  1818  1818 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1f54617a
11-17 18:01:00.580  1818  2855 I SocialFeedProvider: +onPause
11-17 18:01:00.580  1818  2855 I SocialFeedProvider: -onPause
11-17 18:01:00.580  1078  1883 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
11-17 18:01:00.600  1078  1836 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5365 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:01:00.600  1818  2054 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:01:00.640  5365  5365 W asset   : Copying FileAsset 0xabe721d0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:01:00.650  1078  1134 D StatusBarManagerService: setSystemUiVisibility(0x0)
11-17 18:01:00.650  1078  1134 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:00.650  1078  1134 D StatusBarManagerService: hiding MENU key
11-17 18:01:00.650  1431  1431 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
11-17 18:01:00.660  1818  1818 I TrimMemoryManager: [trimMemory] 20
11-17 18:01:00.700  5365  5365 I WebViewFactory: Loading com.google.android.webview version 37 (1602158-arm) (code 111201)
11-17 18:01:00.710  5365  5365 I LibraryLoader: Loading: webviewchromium
11-17 18:01:00.730  1078  1328 I ActivityManager: Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5386 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a
11-17 18:01:00.730  1078  1328 D PMS     : acquireWL(5411f30): PARTIAL_WAKE_LOCK  *alarm* 0x1 1078 1000 WorkSource{10039}
11-17 18:01:00.730  1078  1328 V AlarmManager: sending alarm PendingIntent{235b17a9: PendingIntentRecord{4b4c12e com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=49820, Int=0
11-17 18:01:00.730  1078  1078 D PMS     : releaseWL(5411f30): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10039}
11-17 18:01:00.750  1818  2054 W asset   : Copying FileAsset 0xac3db950 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
11-17 18:01:00.760  5365  5365 I LibraryLoader: Time to load native libraries: 47 ms (timestamps 9817-9864)
11-17 18:01:00.760  5365  5365 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:00.780  5365  5365 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37747936}
11-17 18:01:00.780  1078  1614 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5410 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a
11-17 18:01:00.780  5365  5365 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:00.780  5365  5365 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:01:00.790  5365  5365 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:01:00.790  5365  5365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:00.800  5365  5431 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,11-17 18:01:00.800  1818  2054 E Prism.WidgetManager: The same lists. No need to update. skip it.,
11-17 18:01:00.800  1818  2054 I Prism.WidgetManager: onLoadItems() -
11-17 18:01:00.800  1818  2054 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@30f87b90 -
,11-17 18:01:00.810  5365  5365 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,11-17 18:01:00.810  5365  5365 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46784 len=2953
,11-17 18:01:00.810  5365  5365 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229540 len:643667
,11-17 18:01:00.810  5365  5435 D BluetoothAdapter: 62409124: getState() :  mService = null. Returning STATE_OFF,
,11-17 18:01:00.830  5365  5365 I Adreno  : EGLInit: QTI Build: 02/02/15, 7356efb, I9716ce229b,
,11-17 18:01:00.830  5386  5409 D MdScBoot: [95b.1.] 30@-170030 -> 40,
,11-17 18:01:00.840  5386  5409 D MdScBootUi: [95b.1.2.] boot 118
,11-17 18:01:00.840  5386  5409 D MdScSimSt: [95b.1.2.] qry 118: 0+1 running 0
,11-17 18:01:00.870  5365  5441 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,11-17 18:01:00.870  5365  5365 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,11-17 18:01:00.880  5365  5365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:01:00.880  5365  5365 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 18:01:00.890  5365  5365 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,11-17 18:01:00.900  5365  5365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:00.900  5365  5365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:01:00.920  1078  1097 D Process : killProcessQuiet, pid=4841
11-17 18:01:00.920  1078  1097 I ActivityManager: Killing 4841:com.htc.updater/u0a68 (adj 15): empty #17
11-17 18:01:00.920  1078  1097 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.removeContentProvider:10132 
,11-17 18:01:00.960  1774  2323 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,11-17 18:01:00.960  1774  2323 D PhoneApp: -- N1 =0
11-17 18:01:00.960  1774  2323 D PhoneApp: -- N2 =0
11-17 18:01:00.960  1774  2323 D PhoneApp: -- N3 =0
,11-17 18:01:00.990  1078  1836 I ActivityManager: Recipient 4841
,11-17 18:01:01.030  1078  1836 D Process : killProcessQuiet, pid=4841
,11-17 18:01:01.030  1078  1836 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:01.030  1078  1836 W libprocessgroup: failed to open /acct/uid_10068/pid_4841/cgroup.procs: No such file or directory
,11-17 18:01:01.030  1078  1141 I ActivityManager: Killing 4865:com.htc.bgp/u0a8 (adj 15): empty #17
11-17 18:01:01.040  1078  1141 D Process : killProcessQuiet, pid=4865
11-17 18:01:01.040  1078  1141 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:01:01.060  5365  5365 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,11-17 18:01:01.090  5365  5365 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1f24497d, mServedView=org.apache.cordova.engine.SystemWebView{24859072 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@290d6cc3
,11-17 18:01:01.110  1078  1913 I InputMethodManagerService: Disable input method client, pid=1818
,11-17 18:01:01.110  1078  1913 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:01:01.110  1078  1913 I InputMethodManagerService: Enable input method client, pid=5365
11-17 18:01:01.110  1431  1431 I PhoneStatusBar: setImeWindowStatus(false,false)
,11-17 18:01:01.140  5365  5365 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:01:01.140  5365  5463 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:01:01.170  5365  5365 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:01:01.190  5365  5454 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
11-17 18:01:01.190  5365  5454 I chromium: 
,11-17 18:01:01.200  5365  5454 I chromium: [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Regular.ttf, skipping the second occurrence
,11-17 18:01:01.200  5365  5454 I chromium: [INFO:SkFontConfigInterface_android.cpp(227)] ---- system font and fallback font files specify a duplicate font /system/fonts/XinGothic-HTC-Bold.ttf, skipping the second occurrence
,11-17 18:01:01.220  5365  5365 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:01:01.220  5365  5365 I chromium: 
,11-17 18:01:01.230  1078  1097 I ActivityManager: Recipient 4865
,11-17 18:01:01.240  1078  1141 D PMS     : releaseWL(1462c518): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,11-17 18:01:01.240  1078  1097 D Process : killProcessQuiet, pid=4865
11-17 18:01:01.240  1078  1097 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:01:01.240  1078  1097 W libprocessgroup: failed to open /acct/uid_10008/pid_4865/cgroup.procs: No such file or directory
11-17 18:01:01.250  1078  1136 I ActivityManager: Displayed com.example.hello/.MainActivity: +666ms
,11-17 18:01:01.260  5365  5464 D jxcore_app_log: JniHelper::setJavaVM(0xab0ad9d0), pthread_self() = -1407669872
,11-17 18:01:01.260  5365  5464 D JX-Cordova: jxcore cordova android initializing
,11-17 18:01:01.300  5365  5365 W jxcore-log: Initializing JXcore engine,
11-17 18:01:01.300  5365  5365 W jxcore-log: JXcore engine is ready
,11-17 18:01:01.300  5365  5365 W jxcore-log: Starting JXcore engine
,11-17 18:01:01.330  5138  5187 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:01:01.430  5365  5365 W jxcore-log: Platform android,
11-17 18:01:01.430  5365  5365 W jxcore-log: 
11-17 18:01:01.430  5365  5365 W jxcore-log: Process ARCH arm
11-17 18:01:01.430  5365  5365 W jxcore-log: ,
,11-17 18:01:01.460  5365  5365 I jxcore-log: JXcore Cordova bridge is ready!,
11-17 18:01:01.460  5365  5365 I jxcore-log: 
11-17 18:01:01.460  5365  5365 W jxcore-log: JXcore engine is started
,11-17 18:01:01.530  5365  5365 E jxcore-log: >> HTC-HTC One M9,
11-17 18:01:01.530  5365  5365 E jxcore-log: 
,11-17 18:01:01.530  5365  5365 I jxcore-log: Total memory 2860257280
11-17 18:01:01.530  5365  5365 I jxcore-log: ,
11-17 18:01:01.530  5365  5365 I jxcore-log: Free memory 177401856
11-17 18:01:01.530  5365  5365 I jxcore-log: 
11-17 18:01:01.530  5365  5365 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:01:01.530  5365  5365 I jxcore-log: 
11-17 18:01:01.530  5365  5365 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:01:01.530  5365  5365 I jxcore-log: 
,11-17 18:01:01.540  5365  5365 I jxcore-log: userPath [ 'www' ],
11-17 18:01:01.540  5365  5365 I jxcore-log: 
,11-17 18:01:01.540  5365  5365 I jxcore-log: Size 1080 1776
11-17 18:01:01.540  5365  5365 I jxcore-log: 
,11-17 18:01:01.540  5365  5365 I jxcore-log: Screen Brightness 142,
11-17 18:01:01.540  5365  5365 I jxcore-log: 
11-17 18:01:01.540  5365  5365 E jxcore-log: Dummy Error Log.
11-17 18:01:01.540  5365  5365 E jxcore-log: 
,11-17 18:01:01.560  1078  1149 D PMS     : releaseHCC(3f1655df): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
11-17 18:01:01.570  1078  1149 D PMS     : releaseHCC(3426b22c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,11-17 18:01:01.790  5195  5223 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:01:02.070  5365  5365 I jxcore-log: getBuffer is called!!!!
11-17 18:01:02.070  5365  5365 I jxcore-log: 
,11-17 18:01:02.270  1078  1913 D Process : killProcessQuiet, pid=5016
,11-17 18:01:02.270  1078  1913 I ActivityManager: Killing 5016:com.htc.sense.mms/u0a54 (adj 15): empty #17
11-17 18:01:02.270  1078  1913 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:01:02.360  1078  1830 I ActivityManager: Recipient 5016
,11-17 18:01:02.370  5233  5248 E AndroidHttpClient: Leak found,
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	,at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:340)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
,11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:01:02.370  5233  5248 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,11-17 18:01:02.380  1078  1830 D Process : killProcessQuiet, pid=5016
,11-17 18:01:02.380  1078  1830 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:02.380  1078  1830 W libprocessgroup: failed to open /acct/uid_10054/pid_5016/cgroup.procs: No such file or directory
,11-17 18:01:03.070  1078  1328 D PMS     : acquireWL(11e0e6a8): PARTIAL_WAKE_LOCK  *alarm* 0x1 1078 1000 WorkSource{10027}
11-17 18:01:03.070  1078  1328 V AlarmManager: sending alarm PendingIntent{30f995c1: PendingIntentRecord{3a2bc166 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=52171, Int=0
,11-17 18:01:03.080  4891  4891 D AlarmReceiver: ACTION_RESTART_INTENT
,11-17 18:01:03.090  4891  4891 D LocalBluetoothProfile: getPriorityOnValue = 100,
11-17 18:01:03.090  1078  1078 D PMS     : releaseWL(11e0e6a8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
11-17 18:01:03.090  4891  4891 D LocalBluetoothProfile: getPriorityOffValue = 0
,11-17 18:01:03.090  4891  4891 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
11-17 18:01:03.090  4891  4891 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,11-17 18:01:03.130  4891  5471 D HtcModeClient: start the htcmodeservice thread
11-17 18:01:03.130  4891  5471 D HtcModeClient: initCanAgent
,11-17 18:01:03.130  4891  5471 I CANMesgAgentLocalSocket: CANAgent Id = 0
11-17 18:01:03.130  4891  5471 D HtcModeClient: sense info: version = none, id = 2
,11-17 18:01:03.130  4891  5471 D HtcModeClient: display info: width = 1080, height = 1776
11-17 18:01:03.130  4891  5471 D HtcModeClient: display info: mode = 10
,11-17 18:01:03.130  4891  4891 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: BT_TURNON_BYME = false
,11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: PHONE_PULGIN = false
11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: Force_AWAKE = false
11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: PHONE_PULGIN = true
11-17 18:01:03.140  4891  4891 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,11-17 18:01:03.430  1078  1145 D AutomaticBrightnessController: setAmbientLux to brighter = 0.6,
,11-17 18:01:04.190  1078  1111 I ActivityManager: Waited long enough for: ServiceRecord{3813ba7c u0 com.htc.club/com.mcrm.autonotification.NotificationService},
,11-17 18:01:04.760  1078  1111 I ActivityManager: Waited long enough for: ServiceRecord{1103316b u0 com.nero.android.htc.sync/.PowerDisconService}
,11-17 18:01:05.150  4891  5471 I HtcModeClient: handler message = 4011
,11-17 18:01:05.150  4891  5471 D HtcModeClient: getConnectionCheckCount first 0
11-17 18:01:05.150  4891  5471 D HtcModeClient: getConnectionCheckCount count = 3
11-17 18:01:05.150  4891  5471 E HtcModeClient: Check connection and retry 4 times.
11-17 18:01:05.150  4891  5471 D HtcModeClient: setConnectionCheckCount count = 4
11-17 18:01:05.150  4891  5471 D HtcModeClient: setupRestart delayedTime = 3000
,11-17 18:01:05.160  4891  4891 D HtcModeClient: setBtPriority priority = on
11-17 18:01:05.160  4891  4891 D HtcModeClient: unbindBlueToothService
11-17 18:01:05.160  4891  4891 D HtcModeClient: Don't start project servcice
11-17 18:01:05.160  4891  4891 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,11-17 18:01:05.160  4891  4891 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:01:05.160  4891  4891 D SilentMusic: call stop
11-17 18:01:05.160  4891  4891 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,11-17 18:01:05.160  4891  5472 W CANMesgAgentLocalSocket: read the terminate packet, so break
11-17 18:01:05.160  4891  4891 D HtcModeClient: onDestroy
,11-17 18:01:05.710  1078  1328 I ActivityManager: Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5473 uid=10059 gids={50059, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
11-17 18:01:05.710  1078  1328 D PMS     : acquireWL(b84799f): PARTIAL_WAKE_LOCK  *alarm* 0x1 1078 1000 WorkSource{10042}
,11-17 18:01:05.710  1078  1328 V AlarmManager: sending alarm PendingIntent{34706aec: PendingIntentRecord{32f99eb5 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1447779665703, Int=0
11-17 18:01:05.710  1078  1078 D PMS     : releaseWL(b84799f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10042}
,11-17 18:01:05.730   537   537 I art     : Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 217us total 17.660ms,
,11-17 18:01:05.730  1818  3146 I SocialFeedProvider: +disConnect socialManager,
11-17 18:01:05.730  1818  3146 I SocialFeedProvider: disconnect socialManager
,11-17 18:01:05.740  1818  3146 I SocialFeedProvider: -disConnect socialManager,
,11-17 18:01:05.740   537   537 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 207us total 13.293ms
,11-17 18:01:05.760   537   537 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 141KB/4MB, paused 227us total 14.357ms
,11-17 18:01:05.810  5473  5473 I ConfigManager: [DM]ConfigManager: ConfigManager init().,
,11-17 18:01:05.820  5473  5501 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
,11-17 18:01:05.820  5473  5501 I SocialManager[SocialBiLogHelper]: last commit ulog time 1447741041110
11-17 18:01:05.820  5473  5501 I SocialManager[SocialBiLogHelper]: skip commit this time
11-17 18:01:05.820  1078  1607 D Process : killProcessQuiet, pid=5061
11-17 18:01:05.820  1078  1607 I ActivityManager: Killing 5061:com.google.android.setupwizard/u0a62 (adj 15): empty #17
11-17 18:01:05.820  1078  1607 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:01:05.850  5473  5500 I ConfigManager: [DM]ConfigManager: init() => DM GetConfig state is GET_CONFIG_INIT trigger getAppConfig process.
,11-17 18:01:05.850  5473  5499 I ConfigManager: [DM]ConfigManager: init() => DM PutProfile state is PUT_PROFILE_INIT trigger putProfile process.
11-17 18:01:05.860  5473  5500 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779665866
11-17 18:01:05.870  5473  5500 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:01:05.870  5473  5500 E ConfigManager: [DM]ConfigManager: Error in init ConfigManager. com.htc.lib1.dm.exception.DMNoConfigException: Cannot load Config from server and has no local cache.
11-17 18:01:05.870  5473  5500 W System.err: com.htc.lib1.dm.exception.DMNoConfigException: Cannot load Config from server and has no local cache.
11-17 18:01:05.870  5473  5500 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager.getAppConfig(ConfigManager.java:365)
11-17 18:01:05.870  5473  5500 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager.access$500(ConfigManager.java:23)
11-17 18:01:05.870  5473  5500 W System.err: 	at com.htc.lib1.dm.solo.ConfigManager$2.run(ConfigManager.java:96)
11-17 18:01:05.870  5473  5500 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:05.870  5473  5500 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:05.870  5473  5500 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:01:05.890  5473  5499 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,11-17 18:01:05.920  1078  1097 I ActivityManager: Recipient 5061
,11-17 18:01:05.930  1078  1097 D Process : killProcessQuiet, pid=5061,
11-17 18:01:05.930  1078  1097 W libprocessgroup: failed to open /acct/uid_10062/pid_5061/cgroup.procs: No such file or directory
11-17 18:01:05.930  1078  1097 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
,11-17 18:01:06.540  1078  1111 I ActivityManager: Waited long enough for: ServiceRecord{260150b5 u0 com.htc.music/com.htc.musicenhancer.EnhancerService}
,11-17 18:01:06.550  1078  1098 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:01:06.550  1078  1098 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:01:06.550  1078  1098 W Settings:Agent: MONITOR_LOG
11-17 18:01:06.550  1078  1098 W Settings:Agent: name: bluetooth_on
11-17 18:01:06.550  1078  1098 W Settings:Agent: value: 0,
11-17 18:01:06.550  1078  1098 W Settings:Agent: >> traceCallingStack()
11-17 18:01:06.550  1078  1098 W Settings:Agent: Process.myPid(): 1078,
11-17 18:01:06.550  1078  1098 W Settings:Agent: Process.myTid(): 1098,
11-17 18:01:06.550  1078  1098 W Settings:Agent: Process.myUid(): 1000
,11-17 18:01:06.550  1078  1098 W Settings:Agent: 
11-17 18:01:06.550  1078  1098 W Settings:Agent: 
11-17 18:01:06.550  1078  1098 W System.err: java.lang.Throwable: stack dump
11-17 18:01:06.560  1078  1098 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:01:06.560  1078  1098 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:360)
11-17 18:01:06.560  1078  1098 W System.err: 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:644)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
11-17 18:01:06.560  1078  1098 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:01:06.560  1078  1098 W Settings:Agent: 
11-17 18:01:06.560  1078  1098 W Settings:Agent: << traceCallingStack(): 10(ms)
11-17 18:01:06.560  1078  1135 D BluetoothManagerService: Message: 2
,11-17 18:01:06.570  5365  5365 D WifiManager: setWifiEnabled: Base Package Name=com.example.hello, uid=10193
,11-17 18:01:06.570  1078  1340 D WifiService: New client listening to asynchronous messages
11-17 18:01:06.570  1078  1078 E WifiTrafficPoller: ADD_CLIENT: 9
11-17 18:01:06.570  1078  1718 D WifiService: setWifiEnabled: false pid=5365, uid=10193
11-17 18:01:06.570  1078  1718 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:01:06.570  1078  1718 I WifiService: isSprintWifiRestricted(): false
11-17 18:01:06.570  1078  1718 I WifiService: isMdmWifiRestricted(): false
11-17 18:01:06.570  1078  1718 W Settings:Agent: MONITOR_LOG
11-17 18:01:06.570  1078  1718 W Settings:Agent: name: wifi_on
11-17 18:01:06.570  1078  1718 W Settings:Agent: value: 0
11-17 18:01:06.570  1078  1718 W Settings:Agent: >> traceCallingStack()
,11-17 18:01:06.580  1078  1718 W Settings:Agent: Process.myPid(): 1078
11-17 18:01:06.580  1078  1718 W Settings:Agent: Process.myTid(): 1718
11-17 18:01:06.580  1078  1718 W Settings:Agent: Process.myUid(): 1000
11-17 18:01:06.580  1078  1718 W Settings:Agent: 
11-17 18:01:06.580  1078  1718 W Settings:Agent: 
11-17 18:01:06.580  1078  1718 W System.err: java.lang.Throwable: stack dump
11-17 18:01:06.580  1078  1718 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:01:06.580  1078  1718 W System.err: 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
11-17 18:01:06.580  1078  1718 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
11-17 18:01:06.580  1078  1718 W System.err: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1170)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
11-17 18:01:06.580  1078  1718 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:01:06.580  1078  1718 W Settings:Agent: 
11-17 18:01:06.580  1078  1718 W Settings:Agent: << traceCallingStack(): 3(ms)
11-17 18:01:06.580  1078  1340 D WifiController: handleMessage: E msg.what=155656
11-17 18:01:06.580  1078  1340 D WifiController: processMsg: ApStaDisabledState
11-17 18:01:06.580  1078  1340 D WifiController: handleMessage: X
11-17 18:01:06.580  5365  5365 I jxcore-log: ****TEST TOOK:  5050  ms ****
11-17 18:01:06.580  5365  5365 I jxcore-log: 
11-17 18:01:06.580  5365  5365 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:01:06.580  5365  5365 I jxcore-log: 
,11-17 18:01:06.620  4676  5503 W MediaManager: [DualLensScanUtil],	mmpCursor count is 0
,11-17 18:01:06.620  1078  1830 I ActivityManager: Killing 5087:com.google.android.partnersetup/u0a23 (adj 15): empty #17
,11-17 18:01:06.620  1078  1830 D Process : killProcessQuiet, pid=5087
11-17 18:01:06.620  1078  1830 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
,11-17 18:01:06.720  1078  1614 I ActivityManager: Recipient 5087
,11-17 18:01:06.730  1078  1614 D Process : killProcessQuiet, pid=5087
11-17 18:01:06.730  1078  1614 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:06.730  1078  1614 W libprocessgroup: failed to open /acct/uid_10023/pid_5087/cgroup.procs: No such file or directory
,11-17 18:01:06.900  5505  5508 E cutils-trace: Error opening trace file: Permission denied (13)
,11-17 18:01:06.980  5505  5505 D CustomizationManager: ====startRecUseTime====,
11-17 18:01:06.980  5505  5505 D htc.customization.log.level:  is 
,11-17 18:01:06.980  5505  5505 W CustomizationLogLevel: Level value is invalid, use default level 2
,11-17 18:01:07.060  5505  5505 D CustomizationManager:  Read ACC file spent 0.047 (s),
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__A07
,11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:01:07.060  5505  5505 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:01:07.060  5505  5505 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 42507
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 21902
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23420
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 22299
,11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 24002
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23210
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23205
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23806,
,11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23430,
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23408
,11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 27205,
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23210:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,11-17 18:01:07.060  5505  5505 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:01:07.060  5505  5505 D CustomizationManager:  Read CID file spent 0.080 (s)
11-17 18:01:07.060  5505  5505 D CustomizationManager:  All configurations done spent 0.081 (s)
,11-17 18:01:07.110  1078  1927 D PackageManager: deletePackageAsUser: pkg=com.example.hello, pid=5505, uid=2000 userid=0,
,11-17 18:01:07.110  1078  1111 D Process : killProcessQuiet, pid=5365
11-17 18:01:07.110  1078  1111 I ActivityManager: Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
11-17 18:01:07.110  1078  1111 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6354 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6152 
11-17 18:01:07.110  1078  1111 I ActivityManager: Killing 5365:com.example.hello/u0a193 (adj 0): stop com.example.hello
,11-17 18:01:07.150  1078  1155 W PackageSettings: Skipping PackageSetting{2968d44a com.test.thalitest/10192} due to missing metadata,
,11-17 18:01:07.220  1078  1912 I ActivityManager: Recipient 5365
,11-17 18:01:07.220  1078  1614 I WindowState: WIN DEATH: Window{225257b7 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:01:07.220  1078  1340 D WifiService: Client connection lost with reason: 4
11-17 18:01:07.230  1559  1559 E InputEventReceiver: Looper::removeFd(34) is failed, result(0), input channel 'ClientState{2534b24 uid 10193 pid 5365} (c)'
,11-17 18:01:07.320  1078  1111 W ActivityManager: Force removing ActivityRecord{38cb74f5 u0 com.example.hello/.MainActivity t67}: app died, no saved state
,11-17 18:01:07.350  1078  1155 I ActivityManager: Force stopping com.example.hello appid=10193 user=0: pkg removed,
,11-17 18:01:07.370  1500  1500 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,11-17 18:01:07.380  1078  1141 D PMS     : acquireWL(6f49d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2091 10020 WorkSource{10020 com.google.android.gms}
11-17 18:01:07.380  1500  1500 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
11-17 18:01:07.380  1078  1912 W ActivityManager: Spurious death for ProcessRecord{cf27131 5365:com.example.hello/u0a193}, curProc for 5365: null
11-17 18:01:07.380  1500  1500 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,11-17 18:01:07.390  2695  2695 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
11-17 18:01:07.390  2695  2695 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
11-17 18:01:07.390  1078  1912 D PMS     : releaseWL(6f49d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:01:07.390  2695  2695 D [MirrorLinkServer]MirrorLinkServer: Counter : 1,
11-17 18:01:07.390  2091  2405 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:01:07.390  2695  2695 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,11-17 18:01:07.400  1958  5524 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
,11-17 18:01:07.400  1078  1913 I ActivityManager: Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver: pid=5525 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a,
11-17 18:01:07.410  3800  3800 I art     : Explicit concurrent mark sweep GC freed 580(38KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 3MB/5MB, paused 405us total 43.357ms,
,11-17 18:01:07.410  1980  2317 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
11-17 18:01:07.410  1818  1818 I FeedHostManager: [onResume]
,11-17 18:01:07.420  1078  1134 D StatusBarManagerService: setSystemUiVisibility(0x700)
11-17 18:01:07.410  1818  1818 I FeedProviderManager: onResume
11-17 18:01:07.420  1078  1134 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:07.410  1818  2855 I SocialFeedProvider: +onResume
,11-17 18:01:07.420  1078  1134 D StatusBarManagerService: hiding MENU key
11-17 18:01:07.410  1818  2855 I SocialFeedProvider: updateAccounts - Accounts is no change
11-17 18:01:07.410  1818  2855 I SocialFeedProvider: -onResume
11-17 18:01:07.410  1078  1331 W SystemReader: Cannot find grip_rejection_width, use default value instead
11-17 18:01:07.410  2695  2695 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
11-17 18:01:07.410  2695  2695 D [MirrorLinkServer]MirrorLinkServer: Application Removed
11-17 18:01:07.410  2695  2695 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.example.hello
11-17 18:01:07.410  2695  2695 D [MirrorLinkServer]d: onApplicationRemoved
11-17 18:01:07.410  2695  2695 I [MirrorLinkServer]d: Package name found : com.example.hello
11-17 18:01:07.410  1818  1818 I ConnectivityHelper: [getCurrentConnectionType] no network connection
11-17 18:01:07.420  2695  5538 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
11-17 18:01:07.420  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
11-17 18:01:07.420  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:01:07.420   536   536 I art     : Explicit concurrent mark sweep GC freed 8621(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 157us total 17.821ms
11-17 18:01:07.430  2695  2695 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
11-17 18:01:07.440  1078  1110 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
11-17 18:01:07.430  2695  2695 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
11-17 18:01:07.430  2695  2695 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
11-17 18:01:07.430  2695  2695 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
11-17 18:01:07.430  2695  2695 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
11-17 18:01:07.440  1818  1818 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
11-17 18:01:07.440   536   536 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 130us total 16.588ms
,11-17 18:01:07.450  1818  1818 I ThreadedRenderer: Defer allocateBuffers to drawing time
11-17 18:01:07.450   536   536 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 155KB/4MB, paused 80us total 13.969ms
11-17 18:01:07.450  1078  1110 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
11-17 18:01:07.460  1980  2317 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:01:07.470  1078  1927 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5365 uid 10193
,11-17 18:01:07.470  1078  1927 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:01:07.470  1774  1774 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
11-17 18:01:07.470  1078  1927 I InputMethodManagerService: Enable input method client, pid=1818
,11-17 18:01:07.490  1980  2317 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:01:07.500  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667504
,11-17 18:01:07.510  1078  1141 D Process : killProcessQuiet, pid=5114
,11-17 18:01:07.510  1078  1141 I ActivityManager: Killing 5114:com.htc.cs.dm/u0a88 (adj 15): empty #17
11-17 18:01:07.510  1078  1141 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,11-17 18:01:07.520  1078  1078 I art     : Explicit concurrent mark sweep GC freed 26711(1886KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.354ms total 151.670ms
,11-17 18:01:07.520  1078  1155 I art     : WaitForGcToComplete blocked for 150.785ms for cause Explicit
,11-17 18:01:07.540  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:01:07.540  1980  2317 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:01:07.550  1078  1134 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
11-17 18:01:07.550  1078  1134 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:07.550  1078  1134 D StatusBarManagerService: hiding MENU key
,11-17 18:01:07.570  1078  1145 D AutomaticBrightnessController: setAmbientLux to brighter = 1.0
,11-17 18:01:07.580  1818  2021 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.590  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667592
,11-17 18:01:07.600  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,11-17 18:01:07.620  1078  1097 I ActivityManager: Recipient 5114
,11-17 18:01:07.620  1078  1097 D Process : killProcessQuiet, pid=5114,
11-17 18:01:07.620  1078  1097 W libprocessgroup: failed to open /acct/uid_10088/pid_5114/cgroup.procs: No such file or directory
11-17 18:01:07.620  1078  1097 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:07.620  1078  1078 W PackageManager: Unable to load service info ResolveInfo{3180e3ac com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:01:07.620  1078  1078 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331),
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169),
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739),
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:01:07.620  1078  1078 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
11-17 18:01:07.630  1818  1818 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
11-17 18:01:07.630  1608  5548 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
11-17 18:01:07.630  1818  2020 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.640  1608  5548 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,11-17 18:01:07.650  1078  1155 I art     : Explicit concurrent mark sweep GC freed 7727(504KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.751ms total 126.247ms
,11-17 18:01:07.650  3800  5550 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:01:07.650  1078  1155 W asset   : Copying FileAsset 0x55ae14b180 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,11-17 18:01:07.660  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667666
,11-17 18:01:07.690  1078  1912 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5551 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a,
11-17 18:01:07.690  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:01:07.730  1818  2021 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.730  1078  1078 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:01:07.730  1431  1431 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
11-17 18:01:07.730  1078  1386 D TaskPersister: removeObsoleteFile: deleting file=67_task.xml
11-17 18:01:07.730  1431  1431 I PhoneStatusBar: setImeWindowStatus(false,false)
11-17 18:01:07.740  1431  1431 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
,11-17 18:01:07.740  5551  5551 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,11-17 18:01:07.750  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667752
,11-17 18:01:07.760  1078  2135 D PMS     : acquireWL(10a09358): PARTIAL_WAKE_LOCK  Icing 0x1 2349 10020 WorkSource{10020 com.google.android.gms},
,11-17 18:01:07.770  1078  1830 D PMS     : acquireWL(f53bcb1): PARTIAL_WAKE_LOCK  AsyncService 0x1 5195 10126 null
,11-17 18:01:07.770  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:01:07.770  1078  1912 D PMS     : releaseWL(f53bcb1): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,11-17 18:01:07.790  1078  2135 I ActivityManager: Killing 4762:com.htc.demoflopackageinstaller/u0a12 (adj 15): empty #17,
11-17 18:01:07.800  1078  2135 D Process : killProcessQuiet, pid=4762
11-17 18:01:07.800  1078  2135 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,11-17 18:01:07.810  1818  2021 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.820  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667823
,11-17 18:01:07.830  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:01:07.850  1818  2020 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.,
,11-17 18:01:07.860  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667868,
,11-17 18:01:07.870  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:01:07.890  1078  1836 I ActivityManager: Recipient 4762,
,11-17 18:01:07.900  1818  2021 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.910  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779667911
,11-17 18:01:07.910  1078  1836 D Process : killProcessQuiet, pid=4762
11-17 18:01:07.910  1078  1836 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:01:07.910  1078  1836 W libprocessgroup: failed to open /acct/uid_10012/pid_4762/cgroup.procs: No such file or directory
,11-17 18:01:07.920  2349  5576 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
11-17 18:01:07.920  2349  5576 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:01:07.920  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:01:07.930  3800  5550 I ApplicationLogger: canRun() : Opted Out
11-17 18:01:07.930  2349  2349 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.gms
11-17 18:01:07.930  3800  5550 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 279 ms] updated apps [took 279 ms] 
,11-17 18:01:07.940  2349  5576 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello,
11-17 18:01:07.940  2071  2071 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 18:01:07.940  2071  2071 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-17 18:01:07.940  1078  1141 D PMS     : acquireWL(3c1450e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2071 10020 WorkSource{10020 com.google.android.gms}
,11-17 18:01:07.970  1818  2020 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:07.970  1078  2135 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5582 uid=10088 gids={50088, 9997, 3003} abi=arm64-v8a
11-17 18:01:07.970  2349  5580 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
11-17 18:01:07.970  1078  1912 D PMS     : releaseWL(3c1450e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
11-17 18:01:07.970  2349  5580 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
11-17 18:01:07.970  2349  5580 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:01:07.970  2349  5580 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:01:07.980  2349  5580 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-17 18:01:07.990  2349  5580 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:01:07.990  2349  5580 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:01:07.990  2349  5580 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,11-17 18:01:08.000  1818  2318 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,11-17 18:01:08.010  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779668012,
,11-17 18:01:08.030  2349  5602 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:01:08.030  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,11-17 18:01:08.040  5582  5582 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=5582 dbg=false s=true
11-17 18:01:08.040  2349  5602 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:08.040  5582  5582 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.example.hello]
11-17 18:01:08.040  5582  5582 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
,11-17 18:01:08.050  5582  5582 I DeviceManagement: WorkflowService: Starting workflow service
,11-17 18:01:08.050  5582  5608 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@1886f2c2] args=[Bundle[mParcelledData.dataSize=108]]
11-17 18:01:08.050  5582  5608 I DeviceManagement: PackageUpdateWorkflow: ==================================================
11-17 18:01:08.050  5582  5608 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
11-17 18:01:08.050  5582  5608 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,11-17 18:01:08.060  2349  5602 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
,11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:01:08.060  2349  5602 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: Runtime exception while performing operation
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:01:08.060  2349  5602 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:01:08.070  1078  1927 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5610 uid=10089 gids={50089, 9997, 3003} abi=arm64-v8a
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteC,onnection.open(SQLiteConnection.java:219)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:01:08.060  2349  5602 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:01:08.060  5582  5608 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
11-17 18:01:08.070  1818  2020 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: Can't write: system_app_wtf
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.080  1078  5618 E DropBoxManagerService: 	... 5 more
11-17 18:01:08.080  5582  5608 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.example.hello
11-17 18:01:08.090  5582  5626 I DeviceManagement: SessionStateController: Checking invariants...
11-17 18:01:08.090  1818  2217 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_INIT ts:1447779668097
,11-17 18:01:08.120  1818  2217 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.120  2349  5633 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: FATAL EXCEPTION: Open database in background
11-17 18:01:08.130  2349  5633 E AndroidRuntime: Process: com.google.android.gms, PID: 2349
11-17 18:01:08.130  2349  5633 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.130  2349  5633 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
11-17 18:01:08.130  1818  1818 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 4064f7a2-be32-45ea-8c96-1bb14c6d0a60, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null))]
11-17 18:01:08.130  2349  5634 I GMPM-SVC: App measurement is starting up
11-17 18:01:08.140  1078  1912 E ActivityManager: App crashed! Process: com.google.android.gms
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12649)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.140  1078  5637 E DropBoxManagerService: 	... 5 more
11-17 18:01:08.140  2349  5635 I PeopleContactsSync: CP2 sync disabled
11-17 18:01:08.140  2349  4027 I Icing   : doRemovePackageData com.example.hello
11-17 18:01:08.140  1078  2135 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2349, uid=10020, userID:0
,11-17 18:01:08.170  1078  1134 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
11-17 18:01:08.170  1078  1134 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:08.170  1078  1134 D StatusBarManagerService: hiding MENU key
11-17 18:01:08.170  1431  1431 I PhoneStatusBar: setSystemUiNavVisibility(false,false,false)
11-17 18:01:08.170  1078  1328 D PMS     : acquireWL(3dd56bd0): PARTIAL_WAKE_LOCK  *alarm* 0x1 1078 1000 WorkSource{10027}
11-17 18:01:08.180  1078  1328 V AlarmManager: sending alarm PendingIntent{d9877c9: PendingIntentRecord{3a2bc166 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=57254, Int=0
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1062)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:01:08.180  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
11-17 18:01:08.180  1818  2021 I ConfigManager: [DM]ConfigManager: checkAndPutProfile but no Network connected -> Ignore.
,11-17 18:01:08.200  5610  5610 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1393)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:01:08.200  5610  5610 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
11-17 18:01:08.200  1078  1913 D Process : killProcessQuiet, pid=4812,
11-17 18:01:08.200  1078  1913 I ActivityManager: Killing 4812:com.htc.sdm/u0a64 (adj 15): empty #17
11-17 18:01:08.200  1078  1913 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
11-17 18:01:08.200  5610  5610 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:01:08.200  5610  5610 E AndroidRuntime: Process: com.android.documentsui, PID: 5610
11-17 18:01:08.200  5610  5610 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,11-17 18:01:08.200  5610  5610 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: ,	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1393)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
11-17 18:01:08.200  5610  5610 E AndroidRuntime: 	... 9 more
11-17 18:01:08.200  2349  5634 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:01:08.200  2349  5634 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aj.run(SourceFil,e:272)
11-17 18:01:08.200  2349  5634 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
11-17 18:01:08.200  2349  5634 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
11-17 18:01:08.200  2349  5634 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
11-17 18:01:08.200  2349  5634 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
11-17 18:01:08.200  2349  5634 E GMPM-SVC: Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
,11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
,11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
11-17 18:01:08.210  2349  4473 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml
,11-17 18:01:08.250  5582  5626 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc,.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
11-17 18:01:08.250  ,5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.250  5582  5626 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:01:08.270  2349  5579 I art     : Explicit concurrent mark sweep GC freed 34915(2MB) AllocSpace objects, 19(380KB) LOS objects, 24% free, 6MB/8MB, paused 711us total 83.184ms
,11-17 18:01:08.270  1078  1141 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-17 18:01:08.370  1078  1927 I ActivityManager: Recipient 4812
,11-17 18:01:08.410  1078  1836 E ActivityManager: App crashed! Process: com.android.documentsui
11-17 18:01:08.410  1078  1927 W libprocessgroup: failed to open /acct/uid_10064/pid_4812/cgroup.procs: No such file or directory
11-17 18:01:08.410  5582  5626 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.410  1078  1927 D Process : killProcessQuiet, pid=4812
11-17 18:01:08.410  5582  5608 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.410  5582  5608 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.example.hello
11-17 18:01:08.410  1078  1927 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:01:08.420  1078  1836 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
,11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62),
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowServi,ce.java:295)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:08.430  5582  5608 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:08.430  5582  5608 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@1886f2c2]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235),
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:08.430  5582  5608 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:08.440  1078  1607 I ActivityManager: Killing 5300:com.htc.calendar/u0a7 (adj 15): empty #17
11-17 18:01:08.430  1078  1883 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
11-17 18:01:08.430  1078  1883 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:08.430  1078  1883 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,11-17 18:01:08.430  1078  1883 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:01:08.430  1078  1883 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
,11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
11-17 18:01:08.430  1078  1883 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
11-17 18:01:08.430  1078  1883 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:08.430  1078  1883 W System.err: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:01:08.430  1078  1883 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:08.430  1078  1883 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,11-17 18:01:08.430  1078  1883 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.430  1078  1883 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:08.430  1078  1883 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.430  1078  1883 W System.err: 	... 12 more
11-17 18:01:08.430  1078  1836 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
11-17 18:01:08.440  1078  1836 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,11-17 18:01:08.440  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:08.440  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:01:08.440  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:01:08.440  5582  5582 I DeviceManagement: WorkflowService: Stopping workflow service
,11-17 18:01:08.440  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12569)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12233)
11-17 18:01:08.440  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12205)
11-17 18:01:08.440  1078  1836 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:01:08.440  1078  1836 W System.err: 	,at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2566)
11-17 18:01:08.440  1078  1836 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:01:08.440  1078  1836 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:08.440  1078  1836 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.440  1078  1836 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:08.440  1078  1836 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.440  1078  1836 W System.err: 	... 14 more,
11-17 18:01:08.440  1078  1607 D Process : killProcessQuiet, pid=5300
11-17 18:01:08.440  1078  1607 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18848 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18691 
11-17 18:01:08.450  1078  1836 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
11-17 18:01:08.450  1078  1836 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:08.450  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:08.450  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,11-17 18:01:08.450  1078  1836 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12569)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12233),
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12205)
11-17 18:01:08.450  1078  1836 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:01:08.450  1078  1836 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2566)
11-17 18:01:08.450  1078  1836 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:01:08.450  1078  1836 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:08.450  1078  1836 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.450  1078  1836 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,11-17 18:01:08.450  1078  1836 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.450  1078  1836 W System.err: 	... 14 more
,11-17 18:01:08.610  1078  1098 I ActivityManager: Recipient 5300
,11-17 18:01:08.660  4891  4891 D AlarmReceiver: ACTION_RESTART_INTENT
,11-17 18:01:08.690  1078  2135 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5643 uid=10016 gids={50016, 9997, 1028, 1015, 1023} abi=arm64-v8a
,11-17 18:01:08.690  1078  1098 D Process : killProcessQuiet, pid=5300
11-17 18:01:08.690  1078  1098 W libprocessgroup: failed to open /acct/uid_10007/pid_5300/cgroup.procs: No such file or directory
11-17 18:01:08.690  1078  1098 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5093 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:01:08.710  1078  5657 E ErrorReport: HtcErrorReportManager.Error in dumping error information
11-17 18:01:08.710  1078  5657 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1447779668713.dbox_tmp: open failed: EROFS (Read-only file system)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:01:08.710  1078  5657 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:08.710  1078  5657 E ErrorReport: 	... 4 more
11-17 18:01:08.710  4891  4891 D LocalBluetoothProfile: getPriorityOnValue = 100
11-17 18:01:08.710  1078  1078 D PMS     : releaseWL(3dd56bd0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
11-17 18:01:08.710  4891  4891 D LocalBluetoothProfile: getPriorityOffValue = 0
11-17 18:01:08.710  4891  4891 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
11-17 18:01:08.710  4891  4891 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,11-17 18:01:08.720  2349  4483 I CheckinService: Done disabling old GoogleServicesFramework version
11-17 18:01:08.720  1078  1111 W ActivityManager: Can't addPackageDependency on system process
11-17 18:01:08.720  1078  1911 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2349, uid=10020, userID:0
,11-17 18:01:08.720  1078  1830 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2349, uid=10020, userID:0
11-17 18:01:08.720  1078  1098 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2349, uid=10020, userID:0
,11-17 18:01:08.750  4891  5666 D HtcModeClient: start the htcmodeservice thread,
11-17 18:01:08.750  4891  5666 D HtcModeClient: initCanAgent
,11-17 18:01:08.750  4891  5666 I CANMesgAgentLocalSocket: CANAgent Id = 0
11-17 18:01:08.750  4891  5666 D HtcModeClient: sense info: version = none, id = 2
11-17 18:01:08.750  4891  5666 D HtcModeClient: display info: width = 1080, height = 1776
,11-17 18:01:08.750  4891  5666 D HtcModeClient: display info: mode = 10
,11-17 18:01:08.760  4891  4891 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,11-17 18:01:08.760  4891  4891 D HtcModeClient: connectState: BT_TURNON_BYME = false
,11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: CONNECTION_READY = false
11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: PHONE_PULGIN = false
11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: Force_AWAKE = false
11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: PHONE_PULGIN = true
11-17 18:01:08.770  4891  4891 D HtcModeClient: connectState: POWERCONNECTED_READY = true
11-17 18:01:08.770  4891  4923 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
11-17 18:01:08.770  4891  4923 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,11-17 18:01:08.770  5643  5643 D ExternalStorage: After updating volumes, found 1 active roots
,11-17 18:01:08.840  5610  5638 D Documents: Update found 7 roots in 656ms
,11-17 18:01:08.840  2349  5579 W DriveInitializer: Awaiting to be initialized
11-17 18:01:08.840  2349  5669 W DriveInitializer: Background init thread started
,11-17 18:01:08.840  2349  5669 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
11-17 18:01:08.840  2349  5669 E SQLiteDatabase: 	at com.google.android.gms.drive.s.run(SourceFile:62)
,11-17 18:01:08.840  2349  5669 E DocListDatabase: Failed to delete from ContentFileDeletionLock154 table
11-17 18:01:08.840  2349  5669 E DocListDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
11-17 18:01:08.840  2349  5669 E DocListDatabase: 	at com.google.android.gms.drive.s.run(SourceFile:62)
,11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: crash in the same process: Background initialization thread
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
11-17 18:01:08.840  2349  5669 E AndroidRuntime_2_crash: 	at com.google.android.gms.drive.s.run(SourceFile:62)
,11-17 18:01:08.840  2349  5669 W DriveInitializer: Background init thread ended
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:01:08.840  2349  5579 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:01:08.850  2349  5579 E DriveAsyncService: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.850  2349  5579 E DriveAsyncService: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(SourceFile:178)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
11-17 18:01:08.850  2349  5579 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:01:08.920  1818  2054 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,11-17 18:01:08.920  1818  2054 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@30f87b90 +
11-17 18:01:08.920  1818  2054 I Prism.WidgetManager: onLoadItems() +
,11-17 18:01:08.930  2349  4027 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox
,11-17 18:01:08.950  1818  2054 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:01:08.960  2349  4027 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
11-17 18:01:08.960  2349  4027 E Icing   : Could not init tag ds.tag.deleted,
,11-17 18:01:08.990  2349  4027 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
,11-17 18:01:08.990  1078  1927 D PMS     : releaseWL(10a09358): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,11-17 18:01:09.060  1818  2054 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,11-17 18:01:09.190   486   486 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
11-17 18:01:09.190   486   486 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:01:09.190   486   486 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:01:09.190   486   486 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:01:09.190   486   486 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:01:09.190   486   486 E qdoverlay: MdpCtrl close error in unset
,11-17 18:01:09.330   486  1034 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted,
,11-17 18:01:09.330   486  1034 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted,
```
