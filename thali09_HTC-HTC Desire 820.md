#### Test 50388019b27d54e_thali09_HTC-HTC Desire 820 Logs


```--------- beginning of /dev/log/main
11-17 18:20:36.202  2729  2729 I htcbackup-core: ModelRegistry: Loading model meta data from resources...
11-17 18:20:36.222  2729  2743 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
--------- beginning of /dev/log/system
11-17 18:20:36.222  2729  2743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
11-17 18:20:36.242  2673  2684 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
11-17 18:20:36.242  2673  2684 I DeviceManagement: ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.location.fused, com.htc.feedback, com.android.settings, com.android.inputdevices, com.htc.mirrorlinkserver, com.htc.home.personalize, com.htc.backup, com.htc.checkinprovider, com.qualcomm.privinit, com.htc.htcpowermanager, com.android.providers.settings, com.android.keychain, com.htc.android.htcsetupwizard, com.htc.drive.activator, com.htc.backupreset, com.qualcomm.timeservice, android, com.android.CSDFunctionG, com.htc.autobot.cargps.provider, com.htc.cirmodule, com.htc.smartdim, com.htc.lockscreen, com.htc.guide, com.htc.usage, com.htc.android.htcloglevel]
11-17 18:20:36.242  2673  2747 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
11-17 18:20:36.252  2673  2673 I DeviceManagement: WorkflowService: Starting workflow service
11-17 18:20:36.252  2673  2748 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e751a8] args=[Bundle[mParcelledData.dataSize=144]]
11-17 18:20:36.252  2673  2748 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
11-17 18:20:36.252  2673  2748 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
11-17 18:20:36.252  2673  2748 I DeviceManagement: SessionStateController: Checking invariants...
11-17 18:20:36.282  2729  2729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
11-17 18:20:36.292  1525  1536 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
11-17 18:20:36.292  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.292   907  1252 I ActivityManager: Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
11-17 18:20:36.302  1112  1112 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41b9d400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:20:36.312  1112  1112 I RemoteViews.Performance: com.htc.backup 2 10 6 15
,11-17 18:20:36.312  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.322  2673  2748 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
11-17 18:20:36.322  1112  1112 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41bc7c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:20:36.322  2673  2748 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e751a8]
11-17 18:20:36.322  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.322  2673  2673 I DeviceManagement: WorkflowService: Stopping workflow service
11-17 18:20:36.322   907  1251 I ActivityManager: Resuming delayed broadcast
11-17 18:20:36.342  1112  1112 I RemoteViews.Performance: com.htc.backup 1 4 9 4
11-17 18:20:36.342  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.342  1112  1112 I RemoteViews.Performance: com.htc.backup 1 2 2 4
11-17 18:20:36.342  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.342  1112  1112 I RemoteViews.Performance: com.htc.backup 1 2 1 4
11-17 18:20:36.342   907  1251 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2754 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
11-17 18:20:36.352  1112  1112 I RemoteViews.Performance: com.htc.backup 2 9 26 21
11-17 18:20:36.552  2729  2752 I htcbackup-core: CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
11-17 18:20:36.562   907  1080 V AlarmManager: sending alarm PendingIntent{424d3e48: PendingIntentRecord{4257a2c0 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=12, w=1440901414353, Int=604800000
11-17 18:20:36.572  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.572  1525  1540 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
11-17 18:20:36.572  1112  1112 I RemoteViews.Performance: com.htc.backup 1 2 15
11-17 18:20:36.572  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.582  2729  2775 W dalvikvm: VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
11-17 18:20:36.582  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.582  1112  1112 I RemoteViews.Performance: com.htc.backup 2 1 1 4
11-17 18:20:36.582  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.582  1112  1112 I RemoteViews.Performance: com.htc.backup 1 3 0 4
11-17 18:20:36.592  1112  1112 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:20:36.592  1112  1112 I RemoteViews.Performance: com.htc.backup 1 2 0 4
11-17 18:20:36.592  1112  1112 I RemoteViews.Performance: com.htc.backup 1 15 21
11-17 18:20:36.592  2754  2768 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
11-17 18:20:36.592  2754  2768 W dalvikvm: VFY: unable to resolve instance field 46
11-17 18:20:36.602  2754  2768 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
11-17 18:20:36.602  2754  2780 I Babel   : MmsConfig: mnc/mcc: 0/0
11-17 18:20:36.602  2754  2780 I Babel   : MmsConfig.loadMmsSettings
11-17 18:20:36.622  2754  2768 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 18:20:36.632  2729  2775 D UPolicy : IUserBehaviorLoggingService reference is gotten !
11-17 18:20:36.632  2479  2489 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
11-17 18:20:36.652  2479  2490 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
11-17 18:20:36.652  2754  2780 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
11-17 18:20:36.652  2754  2780 I Babel   : MmsConfig.loadFromDatabase
11-17 18:20:36.672   907   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.682  2754  2780 E Babel   : canonicalizeMccMnc: invalid mccmnc 
11-17 18:20:36.682  2754  2780 I Babel   : MmsConfig.loadFromResources
11-17 18:20:36.682  2754  2754 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 18:20:36.682  2754  2780 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
11-17 18:20:36.682  2754  2780 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
11-17 18:20:36.682   907  1449 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.682   907  1244 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.692   907  1252 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.692   907   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.692   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.702   907  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.702   907   918 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.702   907  1448 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.702   907  1451 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.702  2766  2766 E cutils-trace: Error opening trace file: No such file or directory (2)
11-17 18:20:36.702   907  1424 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2754, uid=10111, userID:0
11-17 18:20:36.712  2754  2754 V Babel   : babel boot account: thalitester@gmail.com
11-17 18:20:36.712  2754  2754 V Babel   : babel boot account: SMS
11-17 18:20:36.722   907   917 D Process : killProcessQuiet, pid=2404
11-17 18:20:36.722   907   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:36.722   907   917 D Process : killProcessQuiet, pid=2381
11-17 18:20:36.722   907   917 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2791 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:20:36.722   907   917 I ActivityManager: Killing 2404:com.htc.video/u0a57 (adj 15): empty #17
11-17 18:20:36.722   907   917 I ActivityManager: Killing 2381:com.htc.htcpowermanager:remote/1000 (adj 15): empty #18
11-17 18:20:36.732   907   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:36.732  2754  2768 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:20:36.742   907  1080 V AlarmManager: sending alarm PendingIntent{42423d20: PendingIntentRecord{4247d138 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46782, Int=0
11-17 18:20:36.742   907   918 I ActivityManager: Recipient 2404
11-17 18:20:36.742   907  1451 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:36.852  2766  2766 D CustomizationManager: ====startRecUseTime====
11-17 18:20:36.852  2766  2766 D htc.customization.log.level:  is 
11-17 18:20:36.852  2766  2766 W CustomizationLogLevel: Level value is invalid, use default level 2
11-17 18:20:36.862   907  1450 I ActivityManager: Recipient 2381
11-17 18:20:36.862   907  1105 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:36.872   907  1080 V AlarmManager: sending alarm PendingIntent{424179f8: PendingIntentRecord{424495d0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46914, Int=0
11-17 18:20:36.912   907  1464 D Process : killProcessQuiet, pid=2421
11-17 18:20:36.912   907  1464 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:36.912   907  1464 I ActivityManager: Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2808 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
11-17 18:20:36.912   907  1464 I ActivityManager: Killing 2421:com.htc.lmw/u0a60 (adj 15): empty #17
11-17 18:20:36.922   907   918 I ActivityManager: Recipient 2421
11-17 18:20:36.922   907   918 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:36.962  2766  2766 D CustomizationManager:  Read ACC file spent 0.066 (s)
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:20:36.962  1223  1223 D ResetNotifyBootCompleteReceiver: Receive bootcomplete intent
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:20:36.962  1223  1223 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:20:36.962  2766  2766 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:20:36.962  2766  2766 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:20:36.962  2766  2766 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:20:36.962  2766  2766 D CustomizationManager:  Read CID file spent 0.114 (s)
11-17 18:20:36.962  2766  2766 D CustomizationManager:  All configurations done spent 0.115 (s)
11-17 18:20:36.972  2766  2766 W HtcNativeFlag: Fail to get flag string for type 'customer', use default value
11-17 18:20:36.972  2766  2766 W HtcNativeFlag: Fail to get flag for type 'customer', use default value: -1
11-17 18:20:36.972  2766  2766 W HtcNativeFlag: Fail to get flag string for type 'language', use default value
11-17 18:20:36.972  2766  2766 W HtcNativeFlag: Fail to get flag for type 'language', use default value: -1
11-17 18:20:36.972  2808  2820 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
11-17 18:20:36.982   907  1252 I ActivityManager: Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2823 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
11-17 18:20:36.992  2808  2820 D ActivityThread: Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
11-17 18:20:37.032   907  1241 W CpuWake : >>nativeAcquireCpuPerfWakeLock()
11-17 18:20:37.032   907  1241 W CpuWake : <<nativeAcquireCpuPerfWakeLock()
11-17 18:20:37.032   907  1241 W CpuWake : >>acquire mCpuPerf_cpu_count wakelock
11-17 18:20:37.032   907  1241 W CpuWake : <<acquire mCpuPerf_cpu_count wakelock
11-17 18:20:37.032   907  1241 W CpuWake : >>acquire mCpuPerf_Freq wakelock
11-17 18:20:37.032   907  1241 W CpuWake : <<acquire mCpuPerf_Freq wakelock
11-17 18:20:37.032   907  1241 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2766
11-17 18:20:37.042   907   952 D PMS     : acquireHCC(41e5e9e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
11-17 18:20:37.042   907  1241 W asset   : Copying FileAsset 0x633517f8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:20:37.042   907  1241 I Intent  : @test_code: getHtcIntentFlag: 0 obj: 1111826720
11-17 18:20:37.042   907   952 D PMS     : acquireHCC(41db0600): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
11-17 18:20:37.042   907  1241 D PMS     : acquireWL(41ca9cd0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
11-17 18:20:37.052  1253  1253 I FeedHostManager: [onPause]
11-17 18:20:37.052  1253  1253 I FeedProviderManager: onPause
11-17 18:20:37.052  1253  1753 I SocialFeedProvider: +onPause
11-17 18:20:37.052  1253  1753 I SocialFeedProvider: -onPause
11-17 18:20:37.052  1253  1253 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c34090
11-17 18:20:37.082   907  1424 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2837 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
11-17 18:20:37.092  2823  2823 D AppTag  : getInstance(Context context)
11-17 18:20:37.122  2837  2837 W asset   : Copying FileAsset 0x5c8cc428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:20:37.122  1253  1253 I TrimMemoryManager: [trimMemory] 20
11-17 18:20:37.132  2823  2823 D AppTag  : getInstance(Context context)
11-17 18:20:37.132  2823  2823 D AppTag  : onCreate()
11-17 18:20:37.132  2808  2820 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
11-17 18:20:37.142  1223  1223 D QXDM2SD:HtcNative: JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
11-17 18:20:37.142  2837  2837 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41b42138}
11-17 18:20:37.152  2837  2837 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:20:37.152  2837  2837 I chromium: [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:20:37.152  2837  2837 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:20:37.162   907  1241 D PMS     : acquireWL(427584e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
11-17 18:20:37.162   907  1106 D PMS     : acquireWL(42758658): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
11-17 18:20:37.162   907  1252 I ActivityManager: Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2852 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:20:37.162   907  1241 W System.err: java.lang.Throwable: stack dump
11-17 18:20:37.162   907   944 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
11-17 18:20:37.162   907  1241 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
11-17 18:20:37.162   907  1241 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
11-17 18:20:37.162   907  1241 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
11-17 18:20:37.162   907  1241 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:20:37.162   907  1241 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:20:37.162   907  1450 D Process : killProcessQuiet, pid=2527
11-17 18:20:37.162   907  1450 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:37.162   907   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421ed670:true
11-17 18:20:37.162  2837  2837 D BluetoothAdapter: 1102416968: getState() :  mService = null. Returning STATE_OFF
11-17 18:20:37.162   907  1105 D PMS     : releaseWL(42758658): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
11-17 18:20:37.162   907  1450 I ActivityManager: Killing 2527:com.htc.reportagent/u0a66 (adj 15): empty #17
11-17 18:20:37.172   907  1251 I ActivityManager: Recipient 2527
11-17 18:20:37.172   907  1105 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:37.312  2837  2837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
11-17 18:20:37.312  2837  2837 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.02.07
11-17 18:20:37.312  2837  2837 I Adreno-EGL: Build Date: 08/28/14 Thu
11-17 18:20:37.312  2837  2837 I Adreno-EGL: Local Branch: 
11-17 18:20:37.312  2837  2837 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
11-17 18:20:37.312  2837  2837 I Adreno-EGL: Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
11-17 18:20:37.312  2837  2837 I Adreno-EGL:                  aa63bbd948f41d15fc72f585e
11-17 18:20:37.322   907   907 I AlarmManager: [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
11-17 18:20:37.322   907   907 I AlarmManager: [AlarmQueuing] post alarm-list load task
11-17 18:20:37.322   907   907 I AlarmManager: [AlarmQueuing] init alarm queuing list
11-17 18:20:37.332   907   907 I ActivityManager: Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2873 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
11-17 18:20:37.332   907   917 D Process : killProcessQuiet, pid=2544
11-17 18:20:37.332   907   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:37.332  2852  2852 V Settings:HtcSettingsApplication: [2852/2852] onCreate()
11-17 18:20:37.332   907   917 I ActivityManager: Killing 2544:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
11-17 18:20:37.342  2852  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
11-17 18:20:37.342   907  1465 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.342   907  1464 I ActivityManager: Recipient 2544
11-17 18:20:37.352   907  1450 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2890 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:20:37.372  2837  2869 W chromium: [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
11-17 18:20:37.522  2837  2837 W dalvikvm: VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
11-17 18:20:37.522  2837  2837 W dalvikvm: VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
11-17 18:20:37.522  2837  2837 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:20:37.522  2837  2837 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:20:37.522   907   907 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42762818
11-17 18:20:37.532  2837  2837 W dalvikvm: VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
11-17 18:20:37.532  2837  2837 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
11-17 18:20:37.532  2837  2837 W dalvikvm: VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
11-17 18:20:37.532  2837  2837 W dalvikvm: VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
11-17 18:20:37.532  2837  2837 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
11-17 18:20:37.532  2890  2890 D HtcFingerPrintQuickLaunchProvider: -onCreate()
11-17 18:20:37.532   907   907 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42763738
11-17 18:20:37.542  2890  2890 V Settings:HtcSettingsApplication: [2890/2890] onCreate()
11-17 18:20:37.542   907   907 D Process : killProcessQuiet, pid=2556
11-17 18:20:37.542   907   907 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42765208
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.apps.maps
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.gsf
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.location
11-17 18:20:37.542  2890  2890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.katana
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: jp.naver.line.android
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.viber.voip
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.tencent.mm
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.android.mail
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.sina.weibo
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.orca
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
11-17 18:20:37.542   907   907 I AlarmManager: [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
11-17 18:20:37.542   907   907 I ActivityManager: Killing 2556:com.htc.showme/u0a83 (adj 15): empty #17
11-17 18:20:37.542   907  1252 I ActivityManager: Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
11-17 18:20:37.552   907  1252 D Process : killProcessQuiet, pid=2570
11-17 18:20:37.552   907  1252 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:37.552   907  1252 I ActivityManager: Killing 2570:com.htc.updater/u0a85 (adj 15): empty #17
11-17 18:20:37.552   907  1241 I ActivityManager: Recipient 2556
11-17 18:20:37.552   907  1448 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.552   907  1465 I ActivityManager: Resuming delayed broadcast
11-17 18:20:37.562  2890  2890 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:20:37.562  2890  2890 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:20:37.562  2890  2890 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:20:37.562  2890  2890 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:20:37.562  2890  2890 D         : Cust_ConnectToPC   : IPT>true
11-17 18:20:37.562  2890  2890 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:20:37.572  2890  2890 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:20:37.572  2890  2890 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:20:37.572  2890  2890 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:20:37.572  2890  2890 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:20:37.572  2890  2890 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:20:37.572  2890  2890 D         : Cust_ConnectToPC   : IPT>true
11-17 18:20:37.572  2890  2890 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:20:37.572  2890  2890 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:20:37.572  2890  2890 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:20:37.572  2890  2890 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
11-17 18:20:37.572  2890  2890 D SmartNS_NSReceiver: onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
11-17 18:20:37.572  2890  2890 I SmartNS_Utility: setISNotification
11-17 18:20:37.582  2890  2890 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:20:37.582  2890  2890 D SmartNS_Utility: usb_denied = 0
11-17 18:20:37.582  2890  2890 I SmartNS_PSService: usb notificaiton:true
11-17 18:20:37.582   907  1244 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:20:37.582   907  1244 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
11-17 18:20:37.582   907  1244 V Tethering: bSetPropertyMultiRAB:false
11-17 18:20:37.582   907  1244 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (2890/1000)
11-17 18:20:37.582  2890  2890 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:20:37.582  2890  2890 D SmartNS_Utility: usb_denied = 0
11-17 18:20:37.582  2890  2890 I SmartNS_PSService: usb notificaiton:true
11-17 18:20:37.592   907  1424 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:20:37.592   907  1424 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
11-17 18:20:37.592   907  1424 V Tethering: bSetPropertyMultiRAB:false
11-17 18:20:37.592  1525  1536 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:20:37.592   907  1424 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (2890/1000)
11-17 18:20:37.602   907  1248 D Process : killProcessQuiet, pid=2600
11-17 18:20:37.602   907  1248 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:20:37.602  1112  1112 I RemoteViews: com.android.settings (true,33751552)
11-17 18:20:37.602  1525  2450 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:20:37.602  1112  1112 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41ba0d58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:20:37.602   907  1248 I ActivityManager: Killing 2600:com.google.android.partnersetup/u0a32 (adj 15): empty #17
11-17 18:20:37.612  1112  1112 I RemoteViews.Performance: com.android.settings 2 8 0 10
11-17 18:20:37.612  1112  1112 I RemoteViews: com.android.settings (true,33751552)
11-17 18:20:37.612  1112  1112 I RemoteViews.Performance: com.android.settings 0 1 10
11-17 18:20:37.612   907   907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
11-17 18:20:37.612   907  1105 I ActivityManager: Recipient 2600
11-17 18:20:37.612   907  1465 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.622   907   907 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2918 uid=9987 gids={49987}
11-17 18:20:37.632   907  2930 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42597960, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
11-17 18:20:37.632   907  2930 W SensorService: Following SensorService logs are not warning, just make sure they are printed
11-17 18:20:37.632   907  2930 W SensorService: enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
11-17 18:20:37.632   907  2930 W SensorService: pid=907, uid=1000
11-17 18:20:37.632   907  2930 W SensorService: Active sensors: size = 2
11-17 18:20:37.632   907  2930 W SensorService: BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
11-17 18:20:37.632   907  2930 W SensorService: CM36282 Light sensor (handle=0x00000002, connections=1)
11-17 18:20:37.632   907  2930 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42597960, eanble = 1, strlen(mName) = 36
11-17 18:20:37.632   907  2930 W SensorService: Active Listeners: mActiveListeners.size() = 3
11-17 18:20:37.632   907  2930 W SensorService: Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4240a1b0
11-17 18:20:37.632   907  2930 W SensorService: Listener[1] = com.android.server.power.DisplayPowerController$10@4219dc08
11-17 18:20:37.632   907  2930 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@42597960
11-17 18:20:37.632   907  2930 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
11-17 18:20:37.632   907  2930 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42597960, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
11-17 18:20:37.632   907  2930 W SensorService: Following SensorService logs are not warning, just make sure they are printed
11-17 18:20:37.632   907  2930 W SensorService: enable: get sensor name = CM36282 Proximity sensor
11-17 18:20:37.632   907   937 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{4277c1f0 u0 ReceiverList{4277c190 907 system/1000/u0 local:4277bf10}}
11-17 18:20:37.642  2837  2837 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:20:37.652  2918  2918 D NfcUiccLockService: -- To check whether previous opened channel needed to be closed ...
11-17 18:20:37.662   907  1448 I ActivityManager: Recipient 2570
11-17 18:20:37.662   907  1465 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.662   907  1106 I InputMethodManagerService: Disable input method client, pid=1253
11-17 18:20:37.662   907  1106 I InputMethodManagerService: Enable input method client, pid=2837
11-17 18:20:37.672  2837  2837 W ResourceType: No package identifier when getting name for resource number 0x00000064
11-17 18:20:37.672  2837  2837 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b89fd0, mServedView=org.apache.cordova.engine.SystemWebView{41b4ff68 VFEDH.C. .F....I. 0,0-720,1134 #64}
11-17 18:20:37.672   907  1451 D Process : killProcessQuiet, pid=2626
11-17 18:20:37.672   907  1451 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:37.672   907   930 I ActivityManager: Displayed com.example.hello/.MainActivity: +607ms
11-17 18:20:37.672  2837  2837 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:20:37.672   907  1451 I ActivityManager: Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2933 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
11-17 18:20:37.672   907  1451 I ActivityManager: Killing 2626:com.htc.android.worldclock/u0a90 (adj 15): empty #17
11-17 18:20:37.682   907  2930 W SensorService: pid=907, uid=1000
11-17 18:20:37.682   907  2930 W SensorService: Active sensors: size = 3
11-17 18:20:37.682   907  2930 W SensorService: BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
11-17 18:20:37.682   907  2930 W SensorService: CM36282 Proximity sensor (handle=0x00000001, connections=1)
11-17 18:20:37.682   907  2930 W SensorService: CM36282 Light sensor (handle=0x00000002, connections=1)
11-17 18:20:37.682   907  2930 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42597960, eanble = 1, strlen(mName) = 36
11-17 18:20:37.682   907  2930 W SensorService: Active Listeners: mActiveListeners.size() = 3
11-17 18:20:37.682   907  2930 W SensorService: Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4240a1b0
11-17 18:20:37.682   907  2930 W SensorService: Listener[1] = com.android.server.power.DisplayPowerController$10@4219dc08
11-17 18:20:37.682   907  2930 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@42597960
11-17 18:20:37.682   907  2930 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
11-17 18:20:37.682  1189  1189 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
11-17 18:20:37.682  1189  1189 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
11-17 18:20:37.682  1189  1189 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
11-17 18:20:37.682  1189  1189 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
11-17 18:20:37.682   907  1424 D PMS     : releaseWL(41ca9cd0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
11-17 18:20:37.692   907  1248 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.692   907  1105 I ActivityManager: Recipient 2626
11-17 18:20:37.732   907  1448 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2947 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
11-17 18:20:37.732   907  1448 D Process : killProcessQuiet, pid=2646
11-17 18:20:37.732   907  1448 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:37.732   907  1448 I ActivityManager: Killing 2646:com.htc.mobiledata/u0a91 (adj 15): empty #17
11-17 18:20:37.742   907  1244 I ActivityManager: Recipient 2646
11-17 18:20:37.742   907  1106 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:37.882  2837  2837 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:20:37.882  2837  2964 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:20:37.932  2837  2837 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:20:38.032  2947  2947 E YouTube : apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
11-17 18:20:38.052  2837  2911 D jxcore_app_log: JniHelper::setJavaVM(0x4161c048), pthread_self() = 1658849528
11-17 18:20:38.052  2837  2911 D JX-Cordova: jxcore cordova android initializing
11-17 18:20:38.102  2947  2947 D libc    : [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,11-17 18:20:38.102  2947  2947 D libc    : [NET] getaddrinfo-, SUCCESS
,11-17 18:20:38.112  2947  2947 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:20:38.122  2837  2837 W jxcore-log: Initializing JXcore engine
,11-17 18:20:38.122  2837  2837 W jxcore-log: JXcore engine is ready
,11-17 18:20:38.132  2837  2837 W jxcore-log: Starting JXcore engine
,11-17 18:20:38.172   907  1464 D ConnectivityService: getActiveNetworkInfo called by com.google.android.youtube (2947/10168)
,11-17 18:20:38.192   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:20:38.192  2947  2947 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,11-17 18:20:38.192   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:20:38.202   907   907 I SensorManager: mEventCount = 300
,11-17 18:20:38.222  2947  2947 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:20:38.232  2947  2947 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:20:38.292  2947  2985 D YouTube : apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,11-17 18:20:38.312  2837  2837 W jxcore-log: Platform android
11-17 18:20:38.312  2837  2837 W jxcore-log: 
,11-17 18:20:38.312  2837  2837 W jxcore-log: Process ARCH arm
11-17 18:20:38.312  2837  2837 W jxcore-log: 
,11-17 18:20:38.332  2947  2947 D YouTube : apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,11-17 18:20:38.352  2837  2837 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:20:38.352  2837  2837 I jxcore-log: 
,11-17 18:20:38.352  2837  2837 W jxcore-log: JXcore engine is started
,11-17 18:20:38.352   907  1248 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:20:38.352   907  1248 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:20:38.352   907  1248 D WifiDisplayAdapter:     GroupId: 
11-17 18:20:38.352   907  1248 D WifiDisplayAdapter:     Passphrase: 
11-17 18:20:38.352   907  1248 D WifiDisplayAdapter:     SessionId: 0
11-17 18:20:38.352   907  1248 D WifiDisplayAdapter:     IP Address: }
,11-17 18:20:38.362   907  1451 D MediaRouterService: Client com.google.android.youtube (pid 2947): Registered
,11-17 18:20:38.362  2947  2947 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter:     GroupId: 
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter:     Passphrase: 
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter:     SessionId: 0
11-17 18:20:38.362   907  1465 D WifiDisplayAdapter:     IP Address: }
,11-17 18:20:38.372  2947  2947 D YouTube : apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,11-17 18:20:38.372  2947  2988 I GoogleConversionPing: Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1447780838&data=screen_name%3D%3CAndroid_YT_Open_App%3E
11-17 18:20:38.372   907  1105 D ConnectivityService: getNetworkInfo networkType=0 called by com.google.android.youtube (2947/10168)
,11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo-,err=8
11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo-, 1
,11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo_proxy+
,11-17 18:20:38.382   363  2998 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
11-17 18:20:38.382   363  2998 D libc    : [NET] get_iface_protocol fail: 
11-17 18:20:38.382   363  2998 D libc    : [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
11-17 18:20:38.382   363  2998 D libc    : [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
11-17 18:20:38.382   363  2998 D libc    : [NET] getaddrinfo-,err=7
11-17 18:20:38.382  2947  2988 D libc    : [NET] getaddrinfo_proxy-
,11-17 18:20:38.382  2947  2988 E GoogleConversionPing: Error sending ping
,11-17 18:20:38.392   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:20:38.402  2837  2837 E jxcore-log: >> HTC-HTC Desire 820
11-17 18:20:38.402  2837  2837 E jxcore-log: 
,11-17 18:20:38.402  2947  2947 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,11-17 18:20:38.402  2947  2947 D YouTube : apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,11-17 18:20:38.402  2837  2837 I jxcore-log: Total memory 1964650496
11-17 18:20:38.402  2837  2837 I jxcore-log: 
,11-17 18:20:38.402  2837  2837 I jxcore-log: Free memory 709242880
11-17 18:20:38.402  2837  2837 I jxcore-log: 
11-17 18:20:38.402  2837  2837 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:20:38.402  2837  2837 I jxcore-log: 
,11-17 18:20:38.402  2837  2837 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:20:38.402  2837  2837 I jxcore-log: 
,11-17 18:20:38.402  2947  2947 D MediaRouter: getSelectedRoute
,11-17 18:20:38.402   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:20:38.412  2837  2837 I jxcore-log: userPath [ 'www' ]
11-17 18:20:38.412  2837  2837 I jxcore-log: 
11-17 18:20:38.412  2837  2837 I jxcore-log: Size 720 1184
11-17 18:20:38.412  2837  2837 I jxcore-log: 
11-17 18:20:38.412  2947  2947 D YouTube : apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
11-17 18:20:38.412  2837  2837 I jxcore-log: Screen Brightness 142
11-17 18:20:38.412  2837  2837 I jxcore-log: 
,11-17 18:20:38.412  2837  2837 E jxcore-log: Dummy Error Log.
11-17 18:20:38.412  2837  2837 E jxcore-log: 
,11-17 18:20:38.412   907  1106 D ConnectivityService: getActiveNetworkInfo called by com.google.android.youtube (2947/10168)
11-17 18:20:38.422  2947  2994 D YouTube : apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,11-17 18:20:38.432   907  1465 I ActivityManager: Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,11-17 18:20:38.432   907   918 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:38.462  2947  2995 D YouTube : apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,11-17 18:20:38.462  2947  2966 D YouTube : apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
11-17 18:20:38.462  2947  2966 D YouTube : apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,11-17 18:20:38.662  1959  3002 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:20:38.692  1959  3002 D FileApkUtils: Spent 21ms computing apk sha1.
,11-17 18:20:38.692  1959  3002 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,11-17 18:20:38.702  1959  3002 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,11-17 18:20:38.702  1959  3002 D FileApkUtils: Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,11-17 18:20:38.712  1959  3002 D GmsModuleFndr: Beginning GMS chimera module scan
,11-17 18:20:38.712  1959  3002 W asset   : Copying FileAsset 0x652d7b80 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
11-17 18:20:38.712   907   918 I ActivityManager: Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,11-17 18:20:38.722  1959  3002 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:20:38.722  1959  3002 D ChimeraCfgMgr: Beginning module configuration check
,11-17 18:20:38.722  1959  3002 D ChimeraCfgMgr: Module APKs unchanged, check complete
,11-17 18:20:38.722   907  1248 I ActivityManager: Resuming delayed broadcast
11-17 18:20:38.732  1959  3008 E dalvikvm: Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,11-17 18:20:38.732  1959  3008 W dalvikvm: VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
11-17 18:20:38.732   907  1449 D PMS     : acquireWL(42756128): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1959 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.732   907  1449 I ActivityManager: Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
11-17 18:20:38.732   907  1252 D ConnectivityService: getActiveNetworkInfo called by com.google.android.gms (1959/10029)
,11-17 18:20:38.752  1959  1959 E dalvikvm: Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
11-17 18:20:38.752  1959  1959 W dalvikvm: VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,11-17 18:20:38.752  1959  1959 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,11-17 18:20:38.752  1959  1959 W dalvikvm: VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,11-17 18:20:38.752  1959  1959 W dalvikvm: VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:20:38.762   907  1465 D PMS     : acquireWL(4263dad8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1959 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:20:38.762   907   918 D PMS     : releaseWL(42756128): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:20:38.792  1959  1959 I CheckinService: Checkin interval check for package: unspecified last checkin: 1447758960449 min interval config: 0 actual interval: 21878348
,11-17 18:20:38.802  1959  3008 D GCM     : COMPAT: Multi user not supported
,11-17 18:20:38.802  1959  3012 I CheckinService: Disabling old GoogleServicesFramework version
,11-17 18:20:38.802  1959  1959 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:20:38.802   907  1424 D PMS     : acquireWL(425ea1b0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1959 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.802   907  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.802   907  1105 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.802   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.812  1959  1959 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:20:38.812  1336  3013 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,11-17 18:20:38.812  1959  1959 D SystemUpdateService: onCreate
11-17 18:20:38.812   907   918 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:20:38.832  1959  1959 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 18:20:38.832  1959  3008 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,11-17 18:20:38.832  1202  1202 I GCoreUlr: DispatchingService.onCreate()
,11-17 18:20:38.842  1959  1959 W dalvikvm: VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,11-17 18:20:38.842  1959  3021 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,11-17 18:20:38.852  1959  3019 I SystemUpdateService: cancelUpdate (empty URL)
,11-17 18:20:38.852  1959  3019 I SystemUpdateService: active receiver: disabled
11-17 18:20:38.852   907  1451 D PMS     : acquireWL(42493038): PARTIAL_WAKE_LOCK  Icing 0x1 1959 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.852   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.862  1959  3019 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:20:38.862  1959  3015 I CheckinService: Checking schedule, now: 1447780838873 next: 1447758990383
,11-17 18:20:38.862  1959  3015 I CheckinService: active receiver: enabled
11-17 18:20:38.862   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.872   907  1252 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.872   907  1424 D ConnectivityService: getActiveNetworkInfo called by com.google.android.gms (1959/10029)
11-17 18:20:38.872   907  1252 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.872   907  1241 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.882  1959  3021 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
11-17 18:20:38.892   907  1449 D PMS     : releaseWL(42493038): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.892   907  1465 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.892   907  1105 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.892   907  1241 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.892   907  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.892   907  1450 D PMS     : acquireWL(42792f40): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.892   907  1465 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.892   907  1106 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.902   907  1448 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.902   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.902   907  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.902   907  1251 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.902   907   918 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.912  1959  1959 D SystemUpdateService: onDestroy
11-17 18:20:38.912   907  1241 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.912   907  1448 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.912   907  1424 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.912   907  1251 D PMS     : releaseWL(425ea1b0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.912   907  1251 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.912   907   918 D PMS     : releaseWL(4263dad8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:38.912   907   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.922   907  1450 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:38.932   907  1248 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:38.942  1959  3021 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:20:38.942  1202  3023 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,11-17 18:20:38.952  1959  3021 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:20:38.952  1959  3021 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:20:38.952  1959  3021 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:20:38.952  2837  2837 I jxcore-log: getBuffer is called!!!!
11-17 18:20:38.952  2837  2837 I jxcore-log: 
,11-17 18:20:38.962  1959  3021 W dalvikvm: VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,11-17 18:20:38.992  1959  3021 W dalvikvm: VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,11-17 18:20:39.002  1959  3021 I AuthZen : Fetching signing key...
,11-17 18:20:39.022   907   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1202, uid=10029, userID:0
,11-17 18:20:39.022  1959  3021 I AuthZen : Signing key fetched successfully!
,11-17 18:20:39.032  1959  3021 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:20:39.032   907   937 W CpuWake : >>nativeReleaseCpuPerfWakeLock()
11-17 18:20:39.042   907   937 W CpuWake : <<nativeReleaseCpuPerfWakeLock()
11-17 18:20:39.042   907   937 W CpuWake : >>release mCpuPerf_cpu_count wakelock
11-17 18:20:39.042   907   937 W CpuWake : <<release mCpuPerf_cpu_count wakelock
11-17 18:20:39.042   907   937 W CpuWake : >>release mCpuPerf_Freq wakelock
11-17 18:20:39.042   907   937 W CpuWake : <<release mCpuPerf_Freq wakelock
11-17 18:20:39.042   907   952 D PMS     : releaseHCC(41e5e9e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
11-17 18:20:39.042   907   952 D PMS     : releaseHCC(41db0600): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,11-17 18:20:39.052  1959  3021 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,11-17 18:20:39.052  1959  3021 D AuthZenTransactionCache: Clearing transaction cache
,11-17 18:20:39.062  1202  3023 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
11-17 18:20:39.062   907  1449 I ActivityManager: Resuming delayed broadcast
11-17 18:20:39.062   907  1105 D PMS     : acquireWL(427a8530): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:20:39.072  1202  3023 I GCoreUlr: Unbound from all location providers
11-17 18:20:39.072   907  1450 D PMS     : releaseWL(427a8530): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:39.072   907  1251 D PMS     : releaseWL(42792f40): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,11-17 18:20:39.082   907  1105 D PMS     : acquireWL(427ae228): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1959 10029 null,
,11-17 18:20:39.092   907  1464 D PMS     : acquireWL(427aeb60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1959 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:20:39.092   907  1252 I ActivityManager: Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,11-17 18:20:39.102  1202  1202 I GCoreUlr: DispatchingService.onDestroy()
,11-17 18:20:39.102  1202  1202 I GCoreUlr: Stopping handler for UlrDispSvcFast
,11-17 18:20:39.112  1202  1202 I GCoreUlr: Unbound from all location providers
,11-17 18:20:39.112  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
11-17 18:20:39.112   907  1465 D PMS     : acquireWL(427b1718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:39.112   907  1106 D PMS     : releaseWL(427ae228): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
11-17 18:20:39.112   907  1105 D PMS     : releaseWL(427aeb60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:39.112   907  1449 D PMS     : releaseWL(427b1718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:39.112   907  1448 I ActivityManager: Resuming delayed broadcast
11-17 18:20:39.122  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:20:39.122  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:20:39.122   907  1105 I ActivityManager: Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,11-17 18:20:39.132   907  1241 I ActivityManager: Resuming delayed broadcast
11-17 18:20:39.142  1336  1336 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,11-17 18:20:39.142   907  1252 D PMS     : acquireWL(427b7520): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1336 10029 null
,11-17 18:20:39.152   907  1424 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,11-17 18:20:39.162  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,11-17 18:20:39.162  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:20:39.172  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,11-17 18:20:39.172  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:20:39.182   907  1244 D PMS     : releaseWL(427b7520): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,11-17 18:20:39.182   907  1448 I ActivityManager: Resuming delayed broadcast
11-17 18:20:39.192  1959  1959 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,11-17 18:20:39.202  1336  1336 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,11-17 18:20:39.222   907  1450 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3039 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,11-17 18:20:39.372   907   938 D ConnectivityService: getActiveNetworkInfo called by  (907/1000)
,11-17 18:20:39.372   907   938 D PMS     : acquireWL(427bdd50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,11-17 18:20:39.382   907   938 D PMS     : releaseWL(427bdd50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,11-17 18:20:39.382   907  1244 D Process : killProcessQuiet, pid=2658
,11-17 18:20:39.382   907  1244 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:39.382   907  1244 I ActivityManager: Killing 2658:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,11-17 18:20:39.392   907  1241 I ActivityManager: Recipient 2658
,11-17 18:20:39.392   907  1105 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:39.412  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,11-17 18:20:39.412   907  1449 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3039, uid=10074, userID:0
,11-17 18:20:39.442  3039  3039 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
11-17 18:20:39.442   907  1248 D ConnectivityService: getAllNetworkInfo called by com.android.vending (3039/10074)
,11-17 18:20:39.522  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,11-17 18:20:39.532  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,11-17 18:20:39.542   907  1448 D ConnectivityService: getAllNetworkInfo called by com.android.vending (3039/10074),
,11-17 18:20:39.552  3039  3039 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,11-17 18:20:39.552  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,11-17 18:20:39.562  1487  2125 I HtcModeClient: handler message = 4011
11-17 18:20:39.562  1487  2125 E HtcModeClient: Check connection and retry 4 times.
,11-17 18:20:39.562  3039  3039 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:20:39.562  3039  3039 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:20:39.582  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:20:39.582  2690  2706 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:20:39.592  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:20:39.592  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:20:39.622  3039  3039 W dalvikvm: VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
11-17 18:20:39.622   907  1449 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3039, uid=10074, userID:0
,11-17 18:20:39.632  1959  1959 I GAv4-SVC: Google Analytics 8.3.01 is starting up.
,11-17 18:20:39.652  3039  3056 D Volley  : [276] DiskBasedCache.clear: Cache cleared.
,11-17 18:20:39.652  3039  3063 D Volley  : [283] DiskBasedCache.clear: Cache cleared.
,11-17 18:20:39.652  3039  3076 D Ads     : Skipping gmscore version check
,11-17 18:20:39.672  3039  3039 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:20:39.672  3039  3039 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,11-17 18:20:39.672  3039  3039 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,11-17 18:20:39.682  1305  3077 D AutoSetting: receiver - intent: android.intent.action.USER_PRESENT
,11-17 18:20:39.682  1305  1305 D AutoSetting: service - onStartCommand() action: com.htc.app.autosetting.delayrequest
11-17 18:20:39.682   907  1448 I ActivityManager: Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
11-17 18:20:39.692  2890  2890 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:20:39.692  2890  2890 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:20:39.692  2890  2890 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:20:39.692  2890  2890 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:20:39.692  2890  2890 D         : Cust_ConnectToPC   : IPT>true
11-17 18:20:39.692  2890  2890 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:20:39.692  2890  2890 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:20:39.692  2890  2890 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:20:39.692  2890  2890 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,11-17 18:20:39.692  2890  2890 D SmartNS_NSReceiver: onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,11-17 18:20:39.692  3039  3039 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,11-17 18:20:39.692  2890  2890 I PSReceiver: onReceive:android.intent.action.USER_PRESENT
11-17 18:20:39.692   907   917 I ActivityManager: Resuming delayed broadcast
11-17 18:20:39.702  2890  2890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:20:39.702  2890  2890 I SmartNS_PSService: onReceive:android.intent.action.USER_PRESENT
11-17 18:20:39.702  2890  2890 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:20:39.702  2890  2890 I SmartNS_PSService:  defaultType:0
,11-17 18:20:39.712   907  1105 D Process : killProcessQuiet, pid=2466
,11-17 18:20:39.712   907  1105 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:39.712   907  1105 I ActivityManager: Killing 2466:com.android.defcontainer/u0a19 (adj 15): empty #17
,11-17 18:20:39.722   907  1449 I ActivityManager: Recipient 2466
,11-17 18:20:39.722   907  1252 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:39.752  1112  3082 W WeatherUtility: can't get weather sync account
,11-17 18:20:39.762   907  1252 I ActivityManager: Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3083 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,11-17 18:20:39.772  1112  3082 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:20:39.792  3083  3083 D browser : Browser versionCode = 760001523 versionName = 7.0.2512153020
,11-17 18:20:39.822  3083  3083 W SWE_UI  : SWE using SurfaceView - Multi-Process
,11-17 18:20:39.822  3083  3083 I LibraryLoader: Loading: swewebviewchromium
,11-17 18:20:39.862  3083  3083 I LibraryLoader: Time to load native libraries: 41 ms (timestamps 9828-9869)
,11-17 18:20:39.862  3083  3083 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:20:39.862  3083  3083 I BrowserStartupController: Initializing chromium process, renderers=9
11-17 18:20:39.862  3083  3083 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:20:39.862  3083  3083 I chromium: [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,11-17 18:20:40.132  3083  3101 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,11-17 18:20:40.142  3083  3083 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
11-17 18:20:40.142  3083  3083 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.02.07
11-17 18:20:40.142  3083  3083 I Adreno-EGL: Build Date: 08/28/14 Thu
11-17 18:20:40.142  3083  3083 I Adreno-EGL: Local Branch: 
11-17 18:20:40.142  3083  3083 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
11-17 18:20:40.142  3083  3083 I Adreno-EGL: Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
11-17 18:20:40.142  3083  3083 I Adreno-EGL:                  aa63bbd948f41d15fc72f585e
,11-17 18:20:40.162   907  1105 D PMS     : releaseWL(427584e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,11-17 18:20:40.182   907  1448 D Process : killProcessQuiet, pid=2690
,11-17 18:20:40.182   907  1448 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,11-17 18:20:40.182  1266  1266 V IccIntentReceiver: IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
11-17 18:20:40.182   907  1448 I ActivityManager: Killing 2690:com.google.android.gm/u0a107 (adj 15): empty #17
,11-17 18:20:40.192  1487  1487 I SIMStateChangeReceiver: SIM state: ABSENT
,11-17 18:20:40.192  1487  1487 I SIMStateChangeReceiver: phoneType = 0
,11-17 18:20:40.192  1487  1487 I SIMStateChangeReceiver: remove notification
,11-17 18:20:40.212   907   917 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3122 uid=10032 gids={50032, 3003, 5012}
,11-17 18:20:40.242   907   917 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.242   907  1241 I ActivityManager: Recipient 2690
,11-17 18:20:40.272   907   918 I ActivityManager: Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3134 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,11-17 18:20:40.272   907   918 D Process : killProcessQuiet, pid=2673
,11-17 18:20:40.272   907   918 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:40.272   907   918 I ActivityManager: Killing 2673:com.htc.cs.dm/u0a98 (adj 15): empty #17
,11-17 18:20:40.322  2479  2479 W SystemReader: Cannot find message_ambs_application_id, use default value instead
,11-17 18:20:40.322  2479  3148 D SmsReceiver: Don't handle ACTION_SIM_STATE_CHANGED not ready action 
11-17 18:20:40.322  2479  2479 D ExchangePolicystatus: onReceive()
11-17 18:20:40.322  2479  2479 D ExchangePolicystatus: onReceive(): ACTION_SIM_STATE_CHANGED
,11-17 18:20:40.322  2479  2479 D ExchangePolicystatus: onReceive(): else
,11-17 18:20:40.332   907  1424 D Process : killProcessQuiet, pid=2754
,11-17 18:20:40.332   907  1424 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,11-17 18:20:40.332  1223  1223 D HtcBroadcastReceiver: onReceive: android.intent.action.SIM_STATE_CHANGED
11-17 18:20:40.332   907  1424 I ActivityManager: Killing 2754:com.google.android.talk/u0a111 (adj 15): empty #17
,11-17 18:20:40.352   907  1248 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3149 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,11-17 18:20:40.362   907  1451 I ActivityManager: Recipient 2673
,11-17 18:20:40.362   907   918 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.382  3149  3149 D CalendarApplication: onCreate
,11-17 18:20:40.382  3134  3162 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:20:40.392  3149  3149 D ProviderChangeReceiver: ---------------------------------------------------
,11-17 18:20:40.392  3149  3149 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start to update notification!
,11-17 18:20:40.392  3149  3165 D AlertService: start to updateAlertNotification!
11-17 18:20:40.392  2852  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:20:40.412   907  1464 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3167 uid=10041 gids={50041}
,11-17 18:20:40.422  3149  3165 D AlertService: No fired or scheduled alerts
,11-17 18:20:40.422  3149  3165 D HtcAlertUtils: -- cancelReminderNotification --
,11-17 18:20:40.422  3149  3165 D HtcAlertUtils: broadcastExistReminder!
,11-17 18:20:40.422  1525  1525 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,11-17 18:20:40.422  3134  3162 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:20:40.422  3134  3162 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
11-17 18:20:40.432   907  1464 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:40.432   907  1449 I ActivityManager: Recipient 2754
,11-17 18:20:40.472  3134  3162 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:20:40.482  3134  3162 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,11-17 18:20:40.502   907  1451 D Process : killProcessQuiet, pid=2729
,11-17 18:20:40.502   907  1451 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:40.502   907  1451 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3180 uid=10078 gids={50078}
11-17 18:20:40.502   907  1451 I ActivityManager: Killing 2729:com.htc.backup/1000 (adj 15): empty #17
,11-17 18:20:40.502  3134  3162 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:20:40.502  3134  3162 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:20:40.522  3134  3162 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:20:40.542  3180  3180 D SMSBackup: Got a database change event
,11-17 18:20:40.552   907   917 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3192 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,11-17 18:20:40.552   907   917 D Process : killProcessQuiet, pid=2791
,11-17 18:20:40.552   907   917 I ActivityManager: Killing 2791:com.htc.backupreset/1000 (adj 15): empty #17
11-17 18:20:40.562   907   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,11-17 18:20:40.562   907   918 D Process : killProcessQuiet, pid=2808
,11-17 18:20:40.562   907   918 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:40.562   907   918 I ActivityManager: Killing 2808:com.htc.htccupd/u0a17 (adj 15): empty #17
,11-17 18:20:40.572   907  1450 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.572   907  1244 I ActivityManager: Recipient 2808
,11-17 18:20:40.602  3192  3205 W WeatherUtility: can't get weather sync account
11-17 18:20:40.602   907  1449 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3207 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,11-17 18:20:40.622   907  1450 I ActivityManager: Recipient 2729
,11-17 18:20:40.622   907  1241 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.632  3207  3207 I DemoRecovery.RestoreReceiver: onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,11-17 18:20:40.632  3207  3207 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,11-17 18:20:40.632  3192  3205 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:20:40.632  3192  3205 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:20:40.632   907   917 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,11-17 18:20:40.642  3207  3219 I RestoreService: onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
11-17 18:20:40.642   907  1106 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:40.652   907  1424 I ActivityManager: Recipient 2791
,11-17 18:20:40.652   907  1251 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.672   907  1449 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3222 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,11-17 18:20:40.672   907  1449 D Process : killProcessQuiet, pid=2823
,11-17 18:20:40.672   907  1449 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:40.672   907  1449 I ActivityManager: Killing 2823:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,11-17 18:20:40.682   907  1244 I ActivityManager: Recipient 2823
,11-17 18:20:40.682  1253  1253 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:20:40.682   907  1448 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:40.692  1253  1253 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
,11-17 18:20:40.692  1253  1253 I RemoteViews.Performance: com.htc.widget.weatherclock 2 10 17
,11-17 18:20:40.732   907  1252 D PMS     : acquireWL(425a4438): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3222 10071 null
,11-17 18:20:40.732   907  1424 D PMS     : acquireWL(42543480): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3222 10071 null
,11-17 18:20:40.742   907  1248 D PMS     : releaseWL(425a4438): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,11-17 18:20:40.742   907  1451 I ActivityManager: Delay finish: com.htc.task/.TodoReceiver
,11-17 18:20:40.752  3222  3236 D TodoTaskshortcut: update TASK shortcut>
,11-17 18:20:40.792  3222  3235 I TodoTaskNotifyService: Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,11-17 18:20:40.792  1525  1525 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,11-17 18:20:40.802   907  1448 D PMS     : releaseWL(42543480): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,11-17 18:20:40.802   907  1105 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:40.812  3222  3235 W NotifyReceiver: stopSelfResult true
,11-17 18:20:40.812   907  1241 D Process : killProcessQuiet, pid=2873
,11-17 18:20:40.812   907  1241 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:40.812   907  1105 I ActivityManager: Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3237 uid=10082 gids={50082, 3003, 5012}
11-17 18:20:40.812   907  1241 I ActivityManager: Killing 2873:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,11-17 18:20:40.832   907  1450 I ActivityManager: Recipient 2873
,11-17 18:20:40.832   907  1106 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.872   907   918 I ActivityManager: Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3249 uid=10082 gids={50082, 3003, 5012}
,11-17 18:20:40.972   907  1248 I ActivityManager: Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3261 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,11-17 18:20:40.972   907  1248 D Process : killProcessQuiet, pid=2933
,11-17 18:20:40.972   907  1248 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,11-17 18:20:40.972   907  1248 D Process : killProcessQuiet, pid=2918
,11-17 18:20:40.972   907  1248 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:40.972   907  1248 I ActivityManager: Killing 2933:com.android.smith/u0a163 (adj 15): empty #17
11-17 18:20:40.972   907  1248 I ActivityManager: Killing 2918:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
,11-17 18:20:40.982   907  1465 I ActivityManager: Recipient 2918
,11-17 18:20:40.982   907  1451 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:40.992   907  1448 I ActivityManager: Recipient 2933
,11-17 18:20:40.992   907  1105 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:41.042  3261  3261 I ImageRamCache: create image Cache, size: 31457280.
11-17 18:20:41.042  3261  3261 I ImageRamCache: [resize] ImageRamCache resized to: 12Mb.
,11-17 18:20:41.042  3261  3261 I ImageRamCache: create image Cache, size: 12582912.
,11-17 18:20:41.042  3261  3261 I FeedSettings: [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
11-17 18:20:41.042  3261  3261 I FeedSettings: GroupBudget 0.500000 0.380000
,11-17 18:20:41.042  3261  3261 I FeedSettings: GroupBudget 60 45 15
,11-17 18:20:41.052  3261  3261 I Prism.ExternalStringMa_: changeLocale(): en_GB
,11-17 18:20:41.062  3261  3261 I Prism.AllAppsOptionsMa_: loadSortType() with Custom
,11-17 18:20:41.062  3261  3261 I Prism.AllAppsOptionsMa_: loadGridSize() with Alternative
,11-17 18:20:41.062  3261  3261 D CustomHighlightReceiver: [custom highlight] onReceive
,11-17 18:20:41.072  3261  3275 D CustomHighlightService: [custom highlight] onHandleIntent
,11-17 18:20:41.072  3261  3275 D NewsDB  : set custom highlight []
11-17 18:20:41.072   907  1244 I ActivityManager: Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,11-17 18:20:41.092  3261  3275 D CustomHighlightService: [custom highlight] set tags 
11-17 18:20:41.092   907  1464 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.102  3180  3180 D SMSBackup: Got a database change event
,11-17 18:20:41.112  2479  2479 D MessagingShortcutReceiver: keep hiding shortcut bubble
,11-17 18:20:41.112  2479  2479 D MessagingShortcut: updateMsgShortcut, msg count> -1
11-17 18:20:41.112  2479  2479 D MessagingShortcut: After query: 0
,11-17 18:20:41.112  2479  2479 D MessagingShortcut: mPresentUnreadCount: -1
,11-17 18:20:41.112  2479  2479 D MessagingShortcut: setMsgShortcutDrawable> 0
,11-17 18:20:41.112  2479  2479 D MessagingShortcut: Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,11-17 18:20:41.122  1525  1525 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,11-17 18:20:41.122  1525  1525 D DotMatrix: [EventService] reorderNotification, total:0
,11-17 18:20:41.122  1525  1525 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,11-17 18:20:41.122  1525  1525 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,11-17 18:20:41.122  3222  3276 D TodoTaskshortcut: update TASK shortcut>
11-17 18:20:41.122   907  1449 I ActivityManager: Delay finish: com.htc.task/.TodoReceiver
,11-17 18:20:41.132  1223  1223 D HtcBroadcastReceiver: onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,11-17 18:20:41.132   907  1251 D Process : killProcessQuiet, pid=2947
,11-17 18:20:41.132   907  1251 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:41.132   907  1464 I ActivityManager: Resuming delayed broadcast
11-17 18:20:41.132   907  1251 I ActivityManager: Killing 2947:com.google.android.youtube/u0a168 (adj 15): empty #17
,11-17 18:20:41.152  2479  2505 D MessagingNotification: New incoming message, can't cancel notification now
,11-17 18:20:41.152  2479  2505 D MessagingNotification: newMsgCnt: 0, false
11-17 18:20:41.152   907  1251 I ActivityManager: Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3277 uid=10091 gids={50091, 3003, 5012}
,11-17 18:20:41.182   907  1244 I ActivityManager: Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,11-17 18:20:41.202   907   918 I ActivityManager: Recipient 2947
,11-17 18:20:41.202   907  1451 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:41.202   907  1241 D MediaRouterService: Client com.google.android.youtube (pid 2947): Died!
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023063
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023598
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023720
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023723
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023731
11-17 18:20:41.212   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360028035
11-17 18:20:41.212   907  1080 V AlarmManager: sending alarm PendingIntent{41fcf4e0: PendingIntentRecord{426338e0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20784, Int=1800000
11-17 18:20:41.212   907  1080 V AlarmManager: sending alarm PendingIntent{42434b20: PendingIntentRecord{42539de8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=46740, Int=259200000
11-17 18:20:41.212   907  1080 V AlarmManager: sending alarm PendingIntent{41e17648: PendingIntentRecord{42500100 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49876, Int=0
11-17 18:20:41.212   907  1080 V AlarmManager: sending alarm PendingIntent{423b9a98: PendingIntentRecord{425246b8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1447758000000, Int=86400000
11-17 18:20:41.232   907  1449 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3291 uid=10091 gids={50091, 3003, 5012}
,11-17 18:20:41.292  3277  3290 D MdScBoot: [188.1.] 30@-182013 -> 40@-182041
11-17 18:20:41.292   907  1450 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.302   907  1251 D Process : killProcessQuiet, pid=3039
,11-17 18:20:41.302   907  1251 I ActivityManager: Killing 3039:com.android.vending/u0a74 (adj 15): empty #17
,11-17 18:20:41.312   907  1251 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,11-17 18:20:41.312   907  1105 D Process : killProcessQuiet, pid=2890
,11-17 18:20:41.312   907  1105 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:20:41.312   907  1105 I ActivityManager: Killing 2890:com.android.settings/1000 (adj 15): empty #17
,11-17 18:20:41.322   907  1106 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:41.322   907  1449 I ActivityManager: Recipient 2890
,11-17 18:20:41.332   907  1424 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:41.332   907  1465 I ActivityManager: Recipient 3039
,11-17 18:20:41.332   907  1251 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:41.332   907  1251 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:41.332  1202  1202 D WearableService: callingUid 10029, callindPid: 1202
11-17 18:20:41.332   907  1106 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:41.342  1202  3303 E MDM     : [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,11-17 18:20:41.362   907  1448 I ActivityManager: Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,11-17 18:20:41.382  1959  3304 D LocationInitializer: Restart initialization of location
,11-17 18:20:41.402  1202  1502 W GCoreFlp: No location to return for getLastLocation()
,11-17 18:20:41.402  1336  3305 W FusedLocationProvider: location=null
11-17 18:20:41.402   907  1464 D PMS     : acquireWL(420d0a40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:41.402   907  1450 D PMS     : releaseWL(420d0a40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.412  1336  3306 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023063
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023598
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023720
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023723
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023731
11-17 18:20:41.412   907  1465 W AlarmManager: Converted elapesd time is over 1 year! when = 315360028035
11-17 18:20:41.412   907  1248 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.422  1336  1336 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:20:41.422  1336  1336 E AuthorizationBluetoothService: Proximity feature is not enabled.
11-17 18:20:41.422   907  1448 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:20:41.422   907  1464 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,11-17 18:20:41.432  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:20:41.432   907  1451 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.442  1959  1959 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:20:41.442   907  1241 I ActivityManager: Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
11-17 18:20:41.442   907  1248 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.482   907  1464 D PMS     : acquireWL(425ce3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.492   907  1450 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:20:41.502   907  1424 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:41.502   907  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1959, uid=10029, userID:0
,11-17 18:20:41.502  1202  3309 E MDM     : [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
11-17 18:20:41.502   907  1244 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1959, uid=10029, userID:0
11-17 18:20:41.502   907  1241 D PMS     : releaseWL(425ce3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.522   907  1448 I ActivityManager: Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
11-17 18:20:41.532  1959  3310 D LocationInitializer: Restart initialization of location
,11-17 18:20:41.542  1202  1502 W GCoreFlp: No location to return for getLastLocation()
,11-17 18:20:41.542  1336  3311 W FusedLocationProvider: location=null
11-17 18:20:41.542   907  1424 D PMS     : acquireWL(426ef2f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:41.542   907  1451 D PMS     : releaseWL(426ef2f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023063
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023598
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023720
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023723
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023731
11-17 18:20:41.552   907  1241 W AlarmManager: Converted elapesd time is over 1 year! when = 315360028035
11-17 18:20:41.552   907   918 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.562  1336  3312 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,11-17 18:20:41.562  1336  1336 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:20:41.562  1336  1336 E AuthorizationBluetoothService: Proximity feature is not enabled.
11-17 18:20:41.562   907  1251 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:20:41.562   907  1451 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,11-17 18:20:41.572  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:20:41.572   907  1449 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:41.582  1959  1959 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:20:41.582   907  1106 I ActivityManager: Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
11-17 18:20:41.582   907  1450 I ActivityManager: Resuming delayed broadcast
11-17 18:20:41.592   907  1451 D PMS     : acquireWL(42658c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:41.592   907  1106 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023063
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023598
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023720
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023723
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023731
11-17 18:20:41.592   907   917 W AlarmManager: Converted elapesd time is over 1 year! when = 315360028035
11-17 18:20:41.602   907  1244 D PMS     : releaseWL(42658c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.632   907  1450 D PMS     : acquireWL(42951a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.632  2167  2167 D MtpReceiver: [MTP][MtpReceiver][onReceive]+
11-17 18:20:41.632  2167  2167 D MtpReceiver: [MTP][MtpReceiver][onReceive]1-
,11-17 18:20:41.632  2167  3315 D MtpReceiver: [MTP][handleMessage][startService]
11-17 18:20:41.632  2167  3315 D MtpReceiver: [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,11-17 18:20:41.632  2167  3315 D MtpReceiver: [MTP][handleMessage]-
11-17 18:20:41.632   907  1448 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
11-17 18:20:41.632   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023063
11-17 18:20:41.632   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023598
11-17 18:20:41.632   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023720
11-17 18:20:41.632   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023723
11-17 18:20:41.632   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023731
11-17 18:20:41.642   907  1464 W AlarmManager: Converted elapesd time is over 1 year! when = 315360028035
,11-17 18:20:41.642   907  1248 D PMS     : releaseWL(42951a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:20:41.642   907  1105 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3316 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
11-17 18:20:41.652  2167  2167 D MtpService: [MTP] startForeground
11-17 18:20:41.652  1112  1112 I RemoteViews: com.android.providers.media (false,0)
11-17 18:20:41.652  1112  1112 I RemoteViews.Performance: com.android.providers.media 1 1 10
11-17 18:20:41.652  1525  1540 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
11-17 18:20:41.652  1112  1112 I RemoteViews: com.android.providers.media (false,0)
11-17 18:20:41.652  2167  2167 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
11-17 18:20:41.652  2167  2167 D MtpDatabase: TotalSize=1918604,MediaCacheLimit=6000
,11-17 18:20:41.652  1112  1112 I RemoteViews.Performance: com.android.providers.media 1 1 15
,11-17 18:20:41.662  2167  2167 D MtpService: [isMtpConnected] connected: true
11-17 18:20:41.662   907  1105 D PMS     : acquireWL(4241f108): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1959 10029 null
,11-17 18:20:41.722  3316  3316 D SyncApplication: Loading default preferences
,11-17 18:20:41.722  1959  3327 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 60 ms
,11-17 18:20:41.722   907  1244 D PMS     : releaseWL(4241f108): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
11-17 18:20:41.732  3316  3316 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,11-17 18:20:41.752   907  1093 D WifiService: New client listening to asynchronous messages
,11-17 18:20:41.762  3316  3316 D SyncApplication: Overriding preferences with custom values
,11-17 18:20:41.772  3316  3316 D SyncApplication: Updating preferences succeeded
,11-17 18:20:41.772  3316  3316 E SyncApplication: Application created.
,11-17 18:20:41.782  3316  3333 D VolumeInfo: check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
11-17 18:20:41.782  3316  3333 D VolumeInfo: The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
11-17 18:20:41.782  3316  3333 V VolumeInfo: Found 0 mount point(s)
,11-17 18:20:41.782  3316  3333 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,11-17 18:20:41.782  3316  3333 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,11-17 18:20:41.792  3316  3333 D VolumeInfo: Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,11-17 18:20:41.792  3316  3333 W VolumeInfo: Can not create volume ID for unmounted volume null
,11-17 18:20:41.792  3316  3316 I CalendarDefines: getNewCalendarAuthority()...
11-17 18:20:41.792   907  1424 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3316, uid=10008, userID:0
,11-17 18:20:41.792   907  1424 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
11-17 18:20:41.792   907  1449 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3316, uid=10008, userID:0
,11-17 18:20:41.802  3316  3316 D SyncApplication: enableAppOperation()+
,11-17 18:20:41.802  3316  3316 D SyncApplication: enableAppOperation()-
,11-17 18:20:41.802  3316  3316 D HTCUtilities: isNeorSinged() + 
11-17 18:20:41.802   907  1449 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,11-17 18:20:41.832  3316  3316 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,11-17 18:20:41.842  3316  3316 D HTCUtilities: isNeorSinged() return false
,11-17 18:20:41.842  3316  3316 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,11-17 18:20:41.842  3316  3316 D CDMountReceiver: USB connected to PC
,11-17 18:20:41.852  3316  3316 D FOTAReceiver: onReceive() enter 
,11-17 18:20:41.852  3316  3316 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,11-17 18:20:41.872   907  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3336 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,11-17 18:20:41.872   907  1105 D Process : killProcessQuiet, pid=3083
,11-17 18:20:41.872   907  1105 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:20:41.872   907  1105 I ActivityManager: Killing 3083:com.htc.sense.browser/u0a12 (adj 15): empty #17
,11-17 18:20:41.892   907  1450 I ActivityManager: Recipient 3083
,11-17 18:20:41.892   907  1451 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:42.072  3336  3336 D HtcFingerPrintQuickLaunchProvider: -onCreate()
,11-17 18:20:42.082  3336  3336 V Settings:HtcSettingsApplication: [3336/3336] onCreate()
,11-17 18:20:42.102  3336  3336 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:20:42.102  3336  3336 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:20:42.102  3336  3336 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:20:42.102  3336  3336 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:20:42.102  3336  3336 D         : Cust_ConnectToPC   : IPT>true
,11-17 18:20:42.102  3336  3336 D         : Cust_ConnectToPC   : Singel_USB>false
,11-17 18:20:42.102  3336  3336 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:20:42.112  3336  3336 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:20:42.112  3336  3336 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:20:42.112  3336  3336 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:20:42.112  3336  3336 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:20:42.112  3336  3336 D         : Cust_ConnectToPC   : IPT>true
11-17 18:20:42.112  3336  3336 D         : Cust_ConnectToPC   : Singel_USB>false
,11-17 18:20:42.112  3336  3336 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:20:42.112  3336  3336 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:20:42.112  3336  3336 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
11-17 18:20:42.112  3336  3336 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,11-17 18:20:42.112  3336  3336 D SmartNS_Utility: usb_cable_connect = 1
,11-17 18:20:42.112  3336  3336 D SmartNS_Utility: usb_denied = 0
,11-17 18:20:42.122  3336  3336 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
,11-17 18:20:42.122  3336  3336 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
,11-17 18:20:42.132  3336  3336 I PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC
11-17 18:20:42.132  3336  3336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:20:42.132  3336  3336 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC
11-17 18:20:42.132  3336  3336 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:20:42.132  3336  3336 I SmartNS_PSService:  defaultType:0
,11-17 18:20:42.142  3336  3336 I SmartNS_PSService: fail notificaiton:false
,11-17 18:20:42.142  3336  3336 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:20:42.142  3336  3336 D SmartNS_Utility: usb_denied = 0
,11-17 18:20:42.142  3336  3336 I SmartNS_PSService: usb notificaiton:true
,11-17 18:20:42.142   907  1105 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
,11-17 18:20:42.142   907  1105 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,11-17 18:20:42.142   907  1105 V Tethering: bSetPropertyMultiRAB:false
11-17 18:20:42.142   907  1241 I ActivityManager: Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
11-17 18:20:42.142   907  1105 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (3336/1000)
11-17 18:20:42.142   907  1448 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:42.152  3336  3336 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:20:42.152  3336  3336 D SmartNS_Utility: usb_denied = 0
,11-17 18:20:42.152  3336  3336 I SmartNS_PSService: usb notificaiton:true
,11-17 18:20:42.152   907   917 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:20:42.152   907  1464 I ActivityManager: Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,11-17 18:20:42.162   907   917 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,11-17 18:20:42.162   907   917 V Tethering: bSetPropertyMultiRAB:false
,11-17 18:20:42.162  1112  1112 I RemoteViews: com.android.settings (true,33751552)
,11-17 18:20:42.162  1112  1112 I RemoteViews.Performance: com.android.settings 3 1 10
,11-17 18:20:42.162  3192  3352 W WeatherUtility: can't get weather sync account
,11-17 18:20:42.162  3336  3336 D SmartNS_Utility: usb_cable_connect = 1
,11-17 18:20:42.162   907   917 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (3336/1000)
11-17 18:20:42.172  1525  1536 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:20:42.172  3336  3336 D SmartNS_Utility: usb_denied = 0
11-17 18:20:42.172  1525  1540 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:20:42.172  1112  1112 I RemoteViews: com.android.settings (true,33751552)
11-17 18:20:42.172  1112  1112 I RemoteViews.Performance: com.android.settings 1 0 10
11-17 18:20:42.172  3336  3336 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false
,11-17 18:20:42.172  3336  3336 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
11-17 18:20:42.172   907   918 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:42.192  3192  3352 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:20:42.192  3192  3352 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:20:42.192  1253  1253 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,11-17 18:20:42.192  1253  1253 I RemoteViews: com.google.android.googlequicksearchbox (false,0)
,11-17 18:20:42.192  1253  1253 I RemoteViews.Performance: com.google.android.googlequicksearchbox 0 1 5
,11-17 18:20:42.202  1253  1253 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:20:42.202  1253  1253 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
,11-17 18:20:42.202  1253  1253 I RemoteViews.Performance: com.htc.widget.weatherclock 1 6 17
11-17 18:20:42.212   907   917 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3353 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,11-17 18:20:42.362  3353  3353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:20:42.372  3353  3365 D PowerUsageService: call getInstance()
,11-17 18:20:42.372   907  1244 I ActivityManager: Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,11-17 18:20:42.382  3353  3365 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,11-17 18:20:42.412   907   917 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:20:42.542   907   917 I dalvikvm-heap: Grow heap (frag case) to 17.461MB for 142960-byte allocation
,11-17 18:20:42.632   907  1465 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:20:42.732  1223  1321 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,11-17 18:20:42.732  1223  1321 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,11-17 18:20:42.792   907  1251 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:20:43.022   907  1244 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:43.032   907  1448 D PMS     : acquireWL(428bb558): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3353 1000 null
,11-17 18:20:43.032   907  1251 D Process : killProcessQuiet, pid=3122
,11-17 18:20:43.032   907  1251 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:20:43.032   907  1251 I ActivityManager: Killing 3122:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,11-17 18:20:43.042   907  1248 I ActivityManager: Recipient 3122
,11-17 18:20:43.042  1112  3368 W WeatherUtility: can't get weather sync account
11-17 18:20:43.042   907  1450 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:43.052  1305  3369 D WeatherUtility: Weather sync is On
,11-17 18:20:43.052  1305  3369 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
,11-17 18:20:43.062   907  1244 D PMS     : releaseWL(428bb558): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,11-17 18:20:43.062   907  1248 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3370 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
11-17 18:20:43.072  3192  3374 W WeatherUtility: can't get weather sync account
,11-17 18:20:43.142  3192  3374 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:20:43.142  3192  3374 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:20:43.152  1253  1253 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:20:43.152  1253  1253 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
,11-17 18:20:43.162  1253  1253 I RemoteViews.Performance: com.htc.widget.weatherclock 0 6 17
,11-17 18:20:43.282   907  1424 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,11-17 18:20:43.422   907  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:20:43.422   907  1106 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:20:43.422   907  1106 W HtcDLNAServiceManager: Settings:AgentMONITOR_LOG
,11-17 18:20:43.422   907  1106 W HtcDLNAServiceManager: Settings:Agentname: bluetooth_on
,11-17 18:20:43.422   907  1106 W HtcDLNAServiceManager: Settings:Agentvalue: 0
,11-17 18:20:43.422   907  1106 W Settings:Agent: >> traceCallingStack()
,11-17 18:20:43.432   907  1106 W Settings:Agent: Process.myPid(): 907
,11-17 18:20:43.432   907  1106 W Settings:Agent: Process.myTid(): 1106
,11-17 18:20:43.432   907  1106 W Settings:Agent: Process.myUid(): 1000
,11-17 18:20:43.432   907  1106 W Settings:Agent: 
,11-17 18:20:43.432   907  1106 W Settings:Agent: 
,11-17 18:20:43.432   907  1106 W System.err: java.lang.Throwable: stack dump
,11-17 18:20:43.432   907  1106 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
,11-17 18:20:43.432   907  1106 W System.err: 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,11-17 18:20:43.432   907  1106 W System.err: 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,11-17 18:20:43.442   907  1106 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,11-17 18:20:43.442   907  1106 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:6170)
,11-17 18:20:43.442   907  1106 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,11-17 18:20:43.442   907  1106 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,11-17 18:20:43.442   907  1106 W System.err: 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,11-17 18:20:43.442   907  1106 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,11-17 18:20:43.442   907  1106 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
,11-17 18:20:43.442   907  1106 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
,11-17 18:20:43.442   907  1106 W Settings:Agent: 
,11-17 18:20:43.442   907  1106 W Settings:Agent: << traceCallingStack(): 19(ms)
,11-17 18:20:43.452   907   944 D BluetoothManagerService: Message: MESSAGE_DISABLE
,11-17 18:20:43.452  2837  2837 D WifiManager: setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,11-17 18:20:43.462   907  1241 W HtcDLNAServiceManager: Settings:AgentMONITOR_LOG
,11-17 18:20:43.462   907  1241 W HtcDLNAServiceManager: Settings:Agentname: wifi_on
11-17 18:20:43.462   907  1241 W HtcDLNAServiceManager: Settings:Agentvalue: 0
11-17 18:20:43.462   907  1241 W Settings:Agent: >> traceCallingStack()
,11-17 18:20:43.462   907  1241 W Settings:Agent: Process.myPid(): 907
11-17 18:20:43.462   907  1241 W Settings:Agent: Process.myTid(): 1241
11-17 18:20:43.462   907  1241 W Settings:Agent: Process.myUid(): 1000
,11-17 18:20:43.462   907  1241 W Settings:Agent: 
11-17 18:20:43.462   907  1241 W Settings:Agent: 
,11-17 18:20:43.462   907  1241 W System.err: java.lang.Throwable: stack dump
,11-17 18:20:43.462   907  1241 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
,11-17 18:20:43.462   907  1241 W System.err: 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,11-17 18:20:43.462   907  1241 W System.err: 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
11-17 18:20:43.462   907  1241 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,11-17 18:20:43.462   907  1241 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:6170)
,11-17 18:20:43.462   907  1241 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:6264)
11-17 18:20:43.462   907  1093 D WifiService: New client listening to asynchronous messages
11-17 18:20:43.462   907  1241 D WifiService: setWifiEnabled: false pid=2837, uid=10396
11-17 18:20:43.462   907  1241 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:20:43.462   907  1241 I WifiService: isSprintWifiRestricted(): false
11-17 18:20:43.462   907  1241 I WifiService: isMdmWifiRestricted(): false
,11-17 18:20:43.462   907  1241 D WifiSettingsStore: [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
11-17 18:20:43.472   907  1241 W System.err: 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
11-17 18:20:43.472   907  1241 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
11-17 18:20:43.472   907  1241 W System.err: 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
11-17 18:20:43.472   907  1241 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
11-17 18:20:43.472   907  1241 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
,11-17 18:20:43.472   907  1241 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:20:43.472   907  1241 W Settings:Agent: 
11-17 18:20:43.472   907  1241 W Settings:Agent: << traceCallingStack(): 7(ms)
11-17 18:20:43.472  2837  2837 I jxcore-log: ****TEST TOOK:  5078  ms ****
11-17 18:20:43.472  2837  2837 I jxcore-log: 
11-17 18:20:43.472  2837  2837 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:20:43.472  2837  2837 I jxcore-log: 
,11-17 18:20:43.822   907  1451 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:43.842   907  1451 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3391 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,11-17 18:20:43.842   907   917 D Process : killProcessQuiet, pid=3134
,11-17 18:20:43.842   907   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,11-17 18:20:43.842  3389  3389 E cutils-trace: Error opening trace file: No such file or directory (2)
11-17 18:20:43.842   907   917 I ActivityManager: Killing 3134:com.htc.contacts/u0a44 (adj 15): empty #17
,11-17 18:20:43.942   907  1465 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:43.942   907  1241 I ActivityManager: Recipient 3134
,11-17 18:20:43.952  3391  3391 I MusicStore: Database version: 95
,11-17 18:20:43.962  3391  3391 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,11-17 18:20:43.982  3389  3389 D CustomizationManager: ====startRecUseTime====
11-17 18:20:43.982  3389  3389 D htc.customization.log.level:  is 
,11-17 18:20:43.982  3389  3389 W CustomizationLogLevel: Level value is invalid, use default level 2
,11-17 18:20:43.982  3391  3391 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,11-17 18:20:44.002   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:20:44.002  3391  3391 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
11-17 18:20:44.002   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:20:44.042   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:20:44.042  3391  3391 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,11-17 18:20:44.042   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system,
11-17 18:20:44.042   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:20:44.052  3391  3391 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
11-17 18:20:44.052   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:20:44.052   907  1080 V AlarmManager: sending alarm PendingIntent{423bc798: PendingIntentRecord{426c7678 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1447780844058, Int=0
,11-17 18:20:44.062   907  1252 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3391, uid=10154, userID:0
,11-17 18:20:44.082   907  1448 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:20:44.082   907  1448 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:20:44.082   907  1448 D WifiDisplayAdapter:     GroupId: 
11-17 18:20:44.082   907  1448 D WifiDisplayAdapter:     Passphrase: 
11-17 18:20:44.082   907  1448 D WifiDisplayAdapter:     SessionId: 0
11-17 18:20:44.082   907  1448 D WifiDisplayAdapter:     IP Address: }
,11-17 18:20:44.082   907  1451 D MediaRouterService: Client com.google.android.music (pid 3391): Registered
,11-17 18:20:44.082   907   917 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:20:44.082   907   917 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:20:44.082   907   917 D WifiDisplayAdapter:     GroupId: 
11-17 18:20:44.082   907   917 D WifiDisplayAdapter:     Passphrase: 
11-17 18:20:44.082   907   917 D WifiDisplayAdapter:     SessionId: 0
11-17 18:20:44.082   907   917 D WifiDisplayAdapter:     IP Address: }
11-17 18:20:44.092  3389  3389 D CustomizationManager:  Read ACC file spent 0.060 (s)
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:20:44.092  3391  3391 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:20:44.092  3389  3389 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:20:44.092  3389  3389 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:20:44.092  3389  3389 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:20:44.102  3389  3389 D CustomizationManager:  Read CID file spent 0.117 (s)
,11-17 18:20:44.102  3389  3389 D CustomizationManager:  All configurations done spent 0.118 (s)
11-17 18:20:44.102  3389  3389 W HtcNativeFlag: Fail to get flag string for type 'customer', use default value
11-17 18:20:44.102  3389  3389 W HtcNativeFlag: Fail to get flag for type 'customer', use default value: -1
11-17 18:20:44.102  3389  3389 W HtcNativeFlag: Fail to get flag string for type 'language', use default value
,11-17 18:20:44.102  3389  3389 W HtcNativeFlag: Fail to get flag for type 'language', use default value: -1,
11-17 18:20:44.102   907  1252 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
11-17 18:20:44.102   907   917 D ConnectivityService: getActiveNetworkInfo called by com.google.android.music (3391/10154)
,11-17 18:20:44.112  3391  3391 D MediaRouter: getSelectedRoute
,11-17 18:20:44.122  3207  3207 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
11-17 18:20:44.122   907  1105 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3391, uid=10154, userID:0
11-17 18:20:44.122   907   938 D ConnectivityService: getActiveNetworkInfo called by  (907/1000)
11-17 18:20:44.122   907   938 D PMS     : acquireWL(41f38668): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
11-17 18:20:44.122   907  1464 I ActivityManager: Resuming delayed broadcast
11-17 18:20:44.122   907   938 D PMS     : releaseWL(41f38668): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
11-17 18:20:44.132  3207  3418 I DFPI.ApkInstallService: onHandleIntent
,11-17 18:20:44.132  3207  3418 I DFPI.ApkInstallService: Media Scan Finished Case 
11-17 18:20:44.132  3207  3418 D DFPI.ApkInstallService: check CID = HTC__032
,11-17 18:20:44.132  3207  3418 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
11-17 18:20:44.132   907  1451 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
11-17 18:20:44.132   907   917 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:44.142   907  1449 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,11-17 18:20:44.152   907   918 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:44.162   907   918 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3423 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,11-17 18:20:44.162   907  1465 D Process : killProcessQuiet, pid=3149
,11-17 18:20:44.162   907  1465 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:20:44.162   907  1465 I ActivityManager: Killing 3149:com.htc.calendar/u0a13 (adj 15): empty #17
11-17 18:20:44.162   907  1106 D PackageManager: deletePackageAsUser: pkg=com.example.hello, pid=3389, uid=2000 user=0
,11-17 18:20:44.182   907  1251 I ActivityManager: Recipient 3149
,11-17 18:20:44.182   907  1451 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:44.192   907   937 I ActivityManager: Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,11-17 18:20:44.192   907   937 D Process : killProcessQuiet, pid=2837
,11-17 18:20:44.192   907   955 W asset   : Copying FileAsset 0x652242e0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,11-17 18:20:44.192   907   937 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
11-17 18:20:44.192   907   937 I ActivityManager: Killing 2837:com.example.hello/u0a396 (adj 0): stop com.example.hello
11-17 18:20:44.192   907   937 W ActivityManager: Force removing ActivityRecord{42440c30 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,11-17 18:20:44.212   907   937 W ActivityManager: handleTopAppChanged(): The previous AP is died unexpectedly.
,11-17 18:20:44.252   907   955 W PackageSettings: Skipping PackageSetting{422d6238 com.test.thalitest/10389} due to missing metadata
,11-17 18:20:44.262   907  1251 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:20:44.262   907  1093 D WifiService: Client connection lost with reason: 4
,11-17 18:20:44.262   907  1450 I WindowState: WIN DEATH: Window{425d8b10 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:20:44.272   907   955 I ActivityManager: Force stopping com.example.hello appid=10396 user=0: pkg removed
,11-17 18:20:44.382   907  1105 I ActivityManager: Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,11-17 18:20:44.392  1112  1112 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
11-17 18:20:44.392  1112  1112 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver packageName:com.example.hello
11-17 18:20:44.392  1112  1112 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver replacing:false
11-17 18:20:44.392  1525  1525 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
11-17 18:20:44.392  1525  1525 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
11-17 18:20:44.392  1525  1525 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
11-17 18:20:44.392  1253  1253 I FeedHostManager: [onResume]
11-17 18:20:44.392  1253  1253 I FeedProviderManager: onResume
11-17 18:20:44.392  1253  1753 I SocialFeedProvider: +onResume
11-17 18:20:44.392  1253  1753 I SocialFeedProvider: updateAccounts - Accounts is no change
,11-17 18:20:44.392  1253  1753 I SocialFeedProvider: -onResume
,11-17 18:20:44.402  1253  1253 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,11-17 18:20:44.402  1202  1530 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:20:44.402  1235  1235 W SystemReader: Cannot find nfc_is_upgrade_to_ar890, use default value instead
,11-17 18:20:44.402  1325  1446 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:20:44.402   907   917 D PMS     : acquireWL(429474d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
11-17 18:20:44.402   907  1106 D ConnectivityService: getActiveNetworkInfo called by com.htc.launcher (1253/10076)
,11-17 18:20:44.402   907  1251 D PMS     : releaseWL(429474d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:20:44.412  3261  3438 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:20:44.412  3261  3438 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,11-17 18:20:44.412   907   917 D ConnectivityService: getActiveNetworkInfo called by com.htc.musicenhancer (3423/10053)
11-17 18:20:44.422   907  1241 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:20:44.422   907  1241 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.422   907  1241 I PackageManager:   Scheme: "sms"
,11-17 18:20:44.422  1253  1458 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,11-17 18:20:44.422  1253  1458 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:20:44.422   907  1241 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.442   907  1106 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:20:44.442   907  1106 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.442   907  1106 I PackageManager:   Scheme: "smsto"
11-17 18:20:44.442   907  1106 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.452   353   757 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:20:44.452  3423  3440 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
11-17 18:20:44.452  1325  1446 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:20:44.452  1325  1446 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
11-17 18:20:44.452   353   757 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:20:44.472   907  1248 I PackageManager:   Action: "android.intent.action.SENDTO"
,11-17 18:20:44.472   907  1248 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.472   907  1248 I PackageManager:   Scheme: "mms"
11-17 18:20:44.472   907  1248 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.502   907  1450 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:20:44.502   907  1450 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.502   907  1450 I PackageManager:   Scheme: "mmsto"
,11-17 18:20:44.502   907  1450 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
11-17 18:20:44.512  1325  1446 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:20:44.522   907   918 I PackageManager:   Action: "android.intent.action.SENDTO"
,11-17 18:20:44.522   907   918 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.522   907   918 I PackageManager:   Scheme: "sms"
11-17 18:20:44.522   907   918 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.542   907   938 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
11-17 18:20:44.542   907  1241 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:20:44.542   907  1241 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.542   907  1241 I PackageManager:   Scheme: "smsto"
11-17 18:20:44.542   907  1241 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
11-17 18:20:44.542   907  1251 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 2837 uid 10396
,11-17 18:20:44.552  1189  1199 W Binder  : Caught a RuntimeException from the binder stub implementation.
11-17 18:20:44.552  1189  1199 W Binder  : java.lang.NullPointerException
11-17 18:20:44.552  1189  1199 W Binder  : 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
11-17 18:20:44.552  1189  1199 W Binder  : 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
11-17 18:20:44.552  1189  1199 W Binder  : 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:20:44.552  1189  1199 W Binder  : 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:20:44.552   907  1251 I InputMethodManagerService: Enable input method client, pid=1253
,11-17 18:20:44.562   907  1465 I PackageManager:   Action: "android.intent.action.SENDTO"
,11-17 18:20:44.562   907  1465 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.562   907  1465 I PackageManager:   Scheme: "mms"
11-17 18:20:44.562   907  1465 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.572   907   918 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:20:44.572   907   918 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:20:44.572   907   918 I PackageManager:   Scheme: "mmsto"
11-17 18:20:44.572   907   918 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,11-17 18:20:44.582  1223  1223 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,11-17 18:20:44.592  1487  2125 I HtcModeClient: handler message = 4011
,11-17 18:20:44.592  1487  2125 E HtcModeClient: Check connection and retry 5 times.
,11-17 18:20:44.742   907   907 W PackageManager: Unable to load service info ResolveInfo{4298e070 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:20:44.742   907   907 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:20:44.742   907   907 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:733)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:20:44.742   907   907 W PackageManager: 	at android.os.Looper.loop(Looper.java:157)
11-17 18:20:44.742   907   907 W PackageManager: 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
11-17 18:20:44.742   907   907 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:1591)
11-17 18:20:44.742   907   907 W PackageManager: 	at java.lang.reflect.Method.invokeNative(Native Method)
11-17 18:20:44.742   907   907 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:515)
11-17 18:20:44.742   907   907 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
11-17 18:20:44.742   907   907 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
11-17 18:20:44.742   907   907 W PackageManager: 	at dalvik.system.NativeStart.main(Native Method)
,11-17 18:20:44.962   907   907 D RemoteDisplayProvider: Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,11-17 18:20:44.962   907   938 W AtomicFile: Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
11-17 18:20:44.962   907   907 D RemoteDisplayProvider: start
11-17 18:20:44.962   907   938 W AppWidgetServiceImpl: Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,11-17 18:20:45.182   907  1248 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:45.202   907  1248 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3445 uid=10081 gids={50081, 5001, 1028, 1015}
,11-17 18:20:45.202   907  1464 I ActivityManager: Killing 2852:com.android.settings:remote/1000 (adj 15): empty #17
11-17 18:20:45.212   907  1464 D Process : killProcessQuiet, pid=2852
11-17 18:20:45.212   907  1464 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,11-17 18:20:45.222   907   918 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:20:45.222   907  1450 I ActivityManager: Recipient 2852
,11-17 18:20:45.242  3445  3445 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,11-17 18:20:45.242  3445  3445 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,11-17 18:20:45.242  3445  3445 I SoundPicker: SoundPickerReceiver [onReceive] startService
,11-17 18:20:45.242   907  1448 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
11-17 18:20:45.252  3445  3457 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
11-17 18:20:45.252  3445  3457 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
11-17 18:20:45.252  3445  3457 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,11-17 18:20:45.252  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,11-17 18:20:45.252  3445  3457 D RingtoneManager: MODE_GSM access default DB
11-17 18:20:45.252  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,11-17 18:20:45.252  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
11-17 18:20:45.252  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
11-17 18:20:45.262  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
11-17 18:20:45.262  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 2),
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
11-17 18:20:45.262  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5,
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
,11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244,
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
11-17 18:20:45.262  3445  3457 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
11-17 18:20:45.262  3445  3457 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
11-17 18:20:45.262  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm),
11-17 18:20:45.262  3445  3457 D RingtoneManager: MODE_GSM access default DB
11-17 18:20:45.262  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,11-17 18:20:45.262  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,11-17 18:20:45.322  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,11-17 18:20:45.322  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.322  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,11-17 18:20:45.322  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
11-17 18:20:45.322  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,11-17 18:20:45.322  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,11-17 18:20:45.332  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.332  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.332  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.332  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,11-17 18:20:45.332  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,11-17 18:20:45.332  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,11-17 18:20:45.332  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,11-17 18:20:45.332  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.342  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
11-17 18:20:45.342  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
11-17 18:20:45.342  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,11-17 18:20:45.342  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,11-17 18:20:45.342  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,11-17 18:20:45.342  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
11-17 18:20:45.342  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
11-17 18:20:45.342  3445  3457 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
11-17 18:20:45.342  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,11-17 18:20:45.342  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,11-17 18:20:45.352  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,11-17 18:20:45.352  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
11-17 18:20:45.352  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
11-17 18:20:45.352  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,11-17 18:20:45.352  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,11-17 18:20:45.352  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,11-17 18:20:45.362  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,11-17 18:20:45.362  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
11-17 18:20:45.362  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,11-17 18:20:45.362  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,11-17 18:20:45.362  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
11-17 18:20:45.372  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,11-17 18:20:45.372  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
11-17 18:20:45.372  3445  3457 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,11-17 18:20:45.372  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,11-17 18:20:45.382  3445  3457 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
11-17 18:20:45.382  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,11-17 18:20:45.382  3445  3457 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,11-17 18:20:45.392   907  1252 I ActivityManager: Resuming delayed broadcast
,11-17 18:20:45.402   907  1450 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
```
