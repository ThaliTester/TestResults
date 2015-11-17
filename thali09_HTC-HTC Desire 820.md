#### Test 503880196ac79ce_thali09_HTC-HTC Desire 820 Logs


```--------- beginning of /dev/log/system
11-17 18:30:17.922   906  1320 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:17.932   906   917 I ActivityManager: Delay finish: com.google.android.gm/.MailIntentReceiver
11-17 18:30:17.972   906  1104 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2685, uid=10107, userID:0
11-17 18:30:17.972   906  1353 I ActivityManager: Resuming delayed broadcast
11-17 18:30:17.992   906   917 I ActivityManager: Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2731 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
--------- beginning of /dev/log/main
11-17 18:30:18.202  2731  2731 I htcbackup-core: ModelRegistry: Loading model meta data from resources...
11-17 18:30:18.212  2731  2745 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
11-17 18:30:18.212  2731  2745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
11-17 18:30:18.222  2668  2678 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
11-17 18:30:18.232  2668  2678 I DeviceManagement: ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.qualcomm.privinit, com.htc.android.htcsetupwizard, com.htc.mirrorlinkserver, com.android.settings, com.htc.android.htcloglevel, com.htc.cirmodule, com.htc.feedback, com.htc.smartdim, com.htc.htcpowermanager, com.android.CSDFunctionG, android, com.htc.guide, com.htc.usage, com.htc.lockscreen, com.htc.backupreset, com.qualcomm.timeservice, com.htc.home.personalize, com.android.providers.settings, com.htc.backup, com.android.location.fused, com.android.inputdevices, com.htc.checkinprovider, com.htc.drive.activator, com.htc.autobot.cargps.provider, com.android.keychain]
11-17 18:30:18.232  2668  2749 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
11-17 18:30:18.232  2668  2668 I DeviceManagement: WorkflowService: Starting workflow service
11-17 18:30:18.242  2668  2750 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e6e1d8] args=[Bundle[mParcelledData.dataSize=144]]
11-17 18:30:18.242  2668  2750 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
11-17 18:30:18.242  2668  2750 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
11-17 18:30:18.242  2668  2750 I DeviceManagement: SessionStateController: Checking invariants...
11-17 18:30:18.252  2731  2731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:18.252   906  1102 I ActivityManager: Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
11-17 18:30:18.262  1532  1542 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
11-17 18:30:18.272  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.282  1111  1111 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41bc0c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:30:18.282  2668  2750 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
11-17 18:30:18.292  1111  1111 I RemoteViews.Performance: com.htc.backup 1 8 5 15
11-17 18:30:18.292  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.292  2668  2750 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e6e1d8]
11-17 18:30:18.292  2668  2668 I DeviceManagement: WorkflowService: Stopping workflow service
11-17 18:30:18.292  1111  1111 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41bc45a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:30:18.292   906  1102 I ActivityManager: Resuming delayed broadcast
11-17 18:30:18.302  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.302   906  1102 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2756 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
11-17 18:30:18.312  1111  1111 I RemoteViews.Performance: com.htc.backup 1 4 6 4
11-17 18:30:18.312  2741  2741 E cutils-trace: Error opening trace file: No such file or directory (2)
11-17 18:30:18.312  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.312  1111  1111 I RemoteViews.Performance: com.htc.backup 1 1 1 4
11-17 18:30:18.312  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.312  1111  1111 I RemoteViews.Performance: com.htc.backup 1 1 1 4
11-17 18:30:18.312  1111  1111 I RemoteViews.Performance: com.htc.backup 0 8 20 21
11-17 18:30:18.462  2741  2741 D CustomizationManager: ====startRecUseTime====
11-17 18:30:18.462  2741  2741 D htc.customization.log.level:  is 
11-17 18:30:18.462  2741  2741 W CustomizationLogLevel: Level value is invalid, use default level 2
11-17 18:30:18.522  2756  2775 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
11-17 18:30:18.522  2756  2775 W dalvikvm: VFY: unable to resolve instance field 46
11-17 18:30:18.532  2756  2775 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
11-17 18:30:18.532  2731  2752 I htcbackup-core: CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
11-17 18:30:18.532  2756  2775 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 18:30:18.532   906  1077 V AlarmManager: sending alarm PendingIntent{4264eb40: PendingIntentRecord{4266dbd8 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=12, w=1440901414353, Int=604800000
11-17 18:30:18.552  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.552  1111  1111 I RemoteViews.Performance: com.htc.backup 2 1 15
11-17 18:30:18.552  2731  2752 W dalvikvm: VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
11-17 18:30:18.552  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.562  2756  2786 I Babel   : MmsConfig: mnc/mcc: 0/0
11-17 18:30:18.562  2756  2786 I Babel   : MmsConfig.loadMmsSettings
11-17 18:30:18.562  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.562  1111  1111 I RemoteViews.Performance: com.htc.backup 1 1 0 4
11-17 18:30:18.562  1532  2753 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
11-17 18:30:18.562  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.562  1111  1111 I RemoteViews.Performance: com.htc.backup 1 2 0 4
11-17 18:30:18.562  1111  1111 I RemoteViews: com.htc.backup (true,33751552)
11-17 18:30:18.572  1111  1111 I RemoteViews.Performance: com.htc.backup 1 1 0 4
11-17 18:30:18.572  1111  1111 I RemoteViews.Performance: com.htc.backup 3 13 21
11-17 18:30:18.572  2741  2741 D CustomizationManager:  Read ACC file spent 0.066 (s)
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:30:18.572  2741  2741 D CIDMapFileReader: Parsing tag item name = HTC__031
11-17 18:30:18.572  2741  2741 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:30:18.572  2741  2741 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:30:18.572  2741  2741 D CustomizationManager:  Read CID file spent 0.114 (s)
11-17 18:30:18.572  2741  2741 D CustomizationManager:  All configurations done spent 0.114 (s)
11-17 18:30:18.582  2741  2741 W HtcNativeFlag: Fail to get flag string for type 'customer', use default value
11-17 18:30:18.582  2741  2741 W HtcNativeFlag: Fail to get flag for type 'customer', use default value: -1
11-17 18:30:18.582  2741  2741 W HtcNativeFlag: Fail to get flag string for type 'language', use default value
11-17 18:30:18.582  2741  2741 W HtcNativeFlag: Fail to get flag for type 'language', use default value: -1
11-17 18:30:18.582  2472  2483 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
11-17 18:30:18.602  2472  2482 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
11-17 18:30:18.602  2756  2786 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
11-17 18:30:18.602  2756  2786 I Babel   : MmsConfig.loadFromDatabase
11-17 18:30:18.622  2731  2752 D UPolicy : IUserBehaviorLoggingService reference is gotten !
11-17 18:30:18.642   906  1247 W CpuWake : >>nativeAcquireCpuPerfWakeLock()
11-17 18:30:18.642   906  1247 W CpuWake : <<nativeAcquireCpuPerfWakeLock()
11-17 18:30:18.642   906  1247 W CpuWake : >>acquire mCpuPerf_cpu_count wakelock
11-17 18:30:18.642   906  1247 W CpuWake : <<acquire mCpuPerf_cpu_count wakelock
11-17 18:30:18.642   906  1247 W CpuWake : >>acquire mCpuPerf_Freq wakelock
11-17 18:30:18.642   906  1247 W CpuWake : <<acquire mCpuPerf_Freq wakelock
11-17 18:30:18.642   906  1247 W asset   : Copying FileAsset 0x63eadf70 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:18.642   906  1247 I Intent  : @test_code: getHtcIntentFlag: 0 obj: 1112842840
11-17 18:30:18.642   906  1247 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2741
11-17 18:30:18.652   906   951 D PMS     : acquireHCC(425e4818): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
11-17 18:30:18.652   906   951 D PMS     : acquireHCC(424fded0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
11-17 18:30:18.652  2756  2786 E Babel   : canonicalizeMccMnc: invalid mccmnc 
11-17 18:30:18.652  2756  2786 I Babel   : MmsConfig.loadFromResources
11-17 18:30:18.652  2756  2786 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
11-17 18:30:18.652   906  1247 D PMS     : acquireWL(424b1da0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
11-17 18:30:18.662  2756  2786 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
11-17 18:30:18.662  1249  1249 I FeedHostManager: [onPause]
11-17 18:30:18.662  1249  1249 I FeedProviderManager: onPause
11-17 18:30:18.662  1249  1249 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cfbb68
11-17 18:30:18.662  1249  1750 I SocialFeedProvider: +onPause
11-17 18:30:18.662  1249  1750 I SocialFeedProvider: -onPause
11-17 18:30:18.662  2756  2775 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:30:18.662   906  1316 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.692  2756  2756 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 18:30:18.692   906  1317 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2790 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
11-17 18:30:18.712   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.712   906  1104 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.712   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.722  2790  2790 W asset   : Copying FileAsset 0x5c88a428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:18.722   906   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.722   906  1317 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.722  1249  1249 I TrimMemoryManager: [trimMemory] 20
11-17 18:30:18.732   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.732   906  1316 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.732   906  1353 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.732   906   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.732   906   916 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2756, uid=10111, userID:0
11-17 18:30:18.742  2756  2756 V Babel   : babel boot account: thalitester@gmail.com
11-17 18:30:18.742  2756  2756 V Babel   : babel boot account: SMS
11-17 18:30:18.742  2790  2790 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41b43e00}
11-17 18:30:18.742  2790  2790 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:18.742  2790  2790 I chromium: [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:18.742  2790  2790 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:30:18.752   906  1104 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2806 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:30:18.752   906  1104 D Process : killProcessQuiet, pid=2401
11-17 18:30:18.752   906  1104 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:18.752   906  1104 D Process : killProcessQuiet, pid=2378
11-17 18:30:18.752   906  1104 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:18.752   906  1104 I ActivityManager: Killing 2401:com.htc.video/u0a57 (adj 15): empty #17
11-17 18:30:18.752   906  1104 I ActivityManager: Killing 2378:com.htc.htcpowermanager:remote/1000 (adj 15): empty #18
11-17 18:30:18.752   906  1350 D PMS     : acquireWL(42486f70): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
11-17 18:30:18.762   906  1102 W System.err: java.lang.Throwable: stack dump
11-17 18:30:18.762   906   944 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
11-17 18:30:18.762   906   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42874008:true
11-17 18:30:18.762   906  1102 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
11-17 18:30:18.762   906  1102 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
11-17 18:30:18.762   906  1102 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
11-17 18:30:18.762   906  1102 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:30:18.762   906  1102 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:30:18.762  2790  2790 D BluetoothAdapter: 1102419960: getState() :  mService = null. Returning STATE_OFF
11-17 18:30:18.762   906  1319 D PMS     : acquireWL(41d9db10): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
11-17 18:30:18.762   906  1316 D PMS     : releaseWL(42486f70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
11-17 18:30:18.762   906  1077 V AlarmManager: sending alarm PendingIntent{42656c48: PendingIntentRecord{424cedb8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46080, Int=0
11-17 18:30:18.762   906  1077 V AlarmManager: sending alarm PendingIntent{4261ce08: PendingIntentRecord{426b0ba8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46086, Int=0
11-17 18:30:18.772   906   916 I ActivityManager: Recipient 2378
11-17 18:30:18.772   906  1316 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:18.832   906  1316 I ActivityManager: Recipient 2401
11-17 18:30:18.832  2790  2790 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
11-17 18:30:18.832  2790  2790 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.02.07
11-17 18:30:18.832  2790  2790 I Adreno-EGL: Build Date: 08/28/14 Thu
11-17 18:30:18.832  2790  2790 I Adreno-EGL: Local Branch: 
11-17 18:30:18.832  2790  2790 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
11-17 18:30:18.832  2790  2790 I Adreno-EGL: Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
11-17 18:30:18.832  2790  2790 I Adreno-EGL:                  aa63bbd948f41d15fc72f585e
11-17 18:30:18.832   906  1317 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:18.872   906  1102 I ActivityManager: Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2835 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
11-17 18:30:18.872   906  1102 D Process : killProcessQuiet, pid=2419
11-17 18:30:18.872   906  1102 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:18.872   906  1102 I ActivityManager: Killing 2419:com.htc.lmw/u0a60 (adj 15): empty #17
,11-17 18:30:18.882  2790  2827 W chromium: [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
11-17 18:30:18.882   906   917 I ActivityManager: Recipient 2419
11-17 18:30:18.882   906  1352 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
11-17 18:30:18.902  2790  2790 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
11-17 18:30:18.912  2790  2790 W dalvikvm: VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
11-17 18:30:18.912  2790  2790 W dalvikvm: VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
11-17 18:30:18.912  2790  2790 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
11-17 18:30:18.922  1222  1222 D ResetNotifyBootCompleteReceiver: Receive bootcomplete intent
11-17 18:30:18.922  1222  1222 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
11-17 18:30:18.932  2835  2850 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
11-17 18:30:18.942   906  1348 I ActivityManager: Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2856 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
11-17 18:30:18.942  2835  2850 D ActivityThread: Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
11-17 18:30:19.032  2856  2856 D AppTag  : getInstance(Context context)
11-17 18:30:19.042  2856  2856 D AppTag  : getInstance(Context context)
11-17 18:30:19.042  2856  2856 D AppTag  : onCreate()
11-17 18:30:19.052  1222  1222 D QXDM2SD:HtcNative: JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
11-17 18:30:19.062   906  1348 I ActivityManager: Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2878 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:30:19.072   906  1348 D Process : killProcessQuiet, pid=2522
11-17 18:30:19.072   906  1348 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:19.072   906  1348 I ActivityManager: Killing 2522:com.htc.reportagent/u0a66 (adj 15): empty #17
11-17 18:30:19.072   906  1316 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.072   906   916 I ActivityManager: Recipient 2522
11-17 18:30:19.092  2835  2850 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
11-17 18:30:19.212  2878  2878 V Settings:HtcSettingsApplication: [2878/2878] onCreate()
11-17 18:30:19.212  2878  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:19.212   906   917 I ActivityManager: Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
11-17 18:30:19.222   906   906 I AlarmManager: [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
11-17 18:30:19.222   906   906 I AlarmManager: [AlarmQueuing] post alarm-list load task
11-17 18:30:19.222   906   906 I AlarmManager: [AlarmQueuing] init alarm queuing list
11-17 18:30:19.232  2790  2790 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:30:19.232   906   906 I ActivityManager: Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2893 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
11-17 18:30:19.232   906  1351 I ActivityManager: Resuming delayed broadcast
11-17 18:30:19.242   906  1351 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2903 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
11-17 18:30:19.252   906  1352 D Process : killProcessQuiet, pid=2540
11-17 18:30:19.252   906  1352 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:19.252  2790  2790 W ResourceType: No package identifier when getting name for resource number 0x00000064
11-17 18:30:19.252  2790  2790 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b8ab80, mServedView=org.apache.cordova.engine.SystemWebView{41b50b18 VFEDH.C. .F....I. 0,0-720,1134 #64}
11-17 18:30:19.252  1188  1188 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
11-17 18:30:19.252  1188  1188 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
11-17 18:30:19.252  1188  1188 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
11-17 18:30:19.252  1188  1188 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
11-17 18:30:19.252   906  1352 I ActivityManager: Killing 2540:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
11-17 18:30:19.252   906  1319 I InputMethodManagerService: Disable input method client, pid=1249
11-17 18:30:19.252   906  1319 I InputMethodManagerService: Enable input method client, pid=2790
11-17 18:30:19.262  2790  2790 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:30:19.262   906   928 I ActivityManager: Displayed com.example.hello/.MainActivity: +582ms
11-17 18:30:19.332   906  1104 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.332   906   917 I ActivityManager: Recipient 2540
11-17 18:30:19.342   906  1352 D PMS     : releaseWL(424b1da0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
11-17 18:30:19.352  2903  2903 D HtcFingerPrintQuickLaunchProvider: -onCreate()
11-17 18:30:19.382  2790  2831 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:30:19.392  2790  2790 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:30:19.432  2790  2790 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:30:19.462  2903  2903 V Settings:HtcSettingsApplication: [2903/2903] onCreate()
11-17 18:30:19.462   906  1102 D Process : killProcessQuiet, pid=2552
11-17 18:30:19.462   906   906 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4276fc70
11-17 18:30:19.462  2903  2903 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:19.462   906  1102 I ActivityManager: Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
11-17 18:30:19.462   906  1102 I ActivityManager: Killing 2552:com.htc.showme/u0a83 (adj 15): empty #17
11-17 18:30:19.472   906  1102 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:19.472   906   906 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@425f3cd8
11-17 18:30:19.472   906   906 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4257dab8
11-17 18:30:19.472   906  1316 I ActivityManager: Resuming delayed broadcast
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.apps.maps
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.gsf
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.location
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.katana
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: jp.naver.line.android
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.viber.voip
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.tencent.mm
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.android.mail
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.sina.weibo
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.orca
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
11-17 18:30:19.482   906   906 I AlarmManager: [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
11-17 18:30:19.482   906  1352 D Process : killProcessQuiet, pid=2566
11-17 18:30:19.482   906  1352 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:19.482   906  1352 I ActivityManager: Killing 2566:com.htc.updater/u0a85 (adj 15): empty #17
11-17 18:30:19.492  2903  2903 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:30:19.492  2903  2903 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:30:19.492  2903  2903 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:30:19.492  2903  2903 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:30:19.492  2903  2903 D         : Cust_ConnectToPC   : IPT>true
11-17 18:30:19.492  2903  2903 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:30:19.492  2903  2903 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:19.492   906  1348 I ActivityManager: Recipient 2566
11-17 18:30:19.492   906  1320 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.502  2903  2903 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:30:19.502  2903  2903 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:30:19.502  2903  2903 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:30:19.502  2903  2903 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:30:19.502  2903  2903 D         : Cust_ConnectToPC   : IPT>true
11-17 18:30:19.502  2903  2903 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:30:19.502  2903  2903 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:19.502  2903  2903 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:30:19.502  2903  2903 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
11-17 18:30:19.502  2903  2903 D SmartNS_NSReceiver: onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
11-17 18:30:19.502  2903  2903 I SmartNS_Utility: setISNotification
11-17 18:30:19.502  2903  2903 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:30:19.502  2903  2903 D SmartNS_Utility: usb_denied = 0
11-17 18:30:19.502  2903  2903 I SmartNS_PSService: usb notificaiton:true
11-17 18:30:19.502   906  1247 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:30:19.502   906  1247 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
11-17 18:30:19.502   906  1247 V Tethering: bSetPropertyMultiRAB:false
11-17 18:30:19.502   906  1247 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (2903/1000)
11-17 18:30:19.512  2903  2903 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:30:19.512  2903  2903 D SmartNS_Utility: usb_denied = 0
11-17 18:30:19.512  2903  2903 I SmartNS_PSService: usb notificaiton:true
11-17 18:30:19.512   906  1317 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:30:19.512  1532  1544 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:30:19.512   906  1317 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
11-17 18:30:19.512   906  1317 V Tethering: bSetPropertyMultiRAB:false
11-17 18:30:19.512   906  1317 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (2903/1000)
11-17 18:30:19.522  1532  2753 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:30:19.522   906  1320 D Process : killProcessQuiet, pid=2595
11-17 18:30:19.522   906  1320 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:30:19.522   906  1320 I ActivityManager: Killing 2595:com.google.android.partnersetup/u0a32 (adj 15): empty #17
11-17 18:30:19.532  1111  1111 I RemoteViews: com.android.settings (true,33751552)
11-17 18:30:19.532  2790  2861 D jxcore_app_log: JniHelper::setJavaVM(0x41615048), pthread_self() = 1658590968
11-17 18:30:19.532  2790  2861 D JX-Cordova: jxcore cordova android initializing
11-17 18:30:19.532  1111  1111 D OnDemandProgressBar: release indeterminate drawable android.widget.OnDemandProgressBar{41b97648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
11-17 18:30:19.532  1111  1111 I RemoteViews.Performance: com.android.settings 1 7 0 10
11-17 18:30:19.532   906   906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:19.542  1111  1111 I RemoteViews: com.android.settings (true,33751552)
11-17 18:30:19.542  1111  1111 I RemoteViews.Performance: com.android.settings 1 1 10
11-17 18:30:19.542   906  1104 I ActivityManager: Recipient 2595
11-17 18:30:19.542   906  1102 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.542   906   906 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2925 uid=9987 gids={49987}
11-17 18:30:19.552   906  2936 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@423bbce0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
11-17 18:30:19.552   906  2936 W SensorService: Following SensorService logs are not warning, just make sure they are printed
11-17 18:30:19.552   906  2936 W SensorService: enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
11-17 18:30:19.552   906  2936 W SensorService: pid=906, uid=1000
11-17 18:30:19.552   906  2936 W SensorService: Active sensors: size = 2
11-17 18:30:19.552   906  2936 W SensorService: BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
11-17 18:30:19.552   906  2936 W SensorService: CM36282 Light sensor (handle=0x00000002, connections=1)
11-17 18:30:19.552   906  2936 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423bbce0, eanble = 1, strlen(mName) = 36
11-17 18:30:19.552   906  2936 W SensorService: Active Listeners: mActiveListeners.size() = 3
11-17 18:30:19.552   906  2936 W SensorService: Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4210f860
11-17 18:30:19.552   906  2936 W SensorService: Listener[1] = com.android.server.power.DisplayPowerController$10@421f7a40
11-17 18:30:19.552   906  2936 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@423bbce0
11-17 18:30:19.552   906  2936 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
11-17 18:30:19.552   906  2936 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@423bbce0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
11-17 18:30:19.552   906  2936 W SensorService: Following SensorService logs are not warning, just make sure they are printed
11-17 18:30:19.552   906  2936 W SensorService: enable: get sensor name = CM36282 Proximity sensor
11-17 18:30:19.552   906  1103 I ActivityManager: Recipient 2552
11-17 18:30:19.552   906  1350 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.552   906   933 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42564250 u0 ReceiverList{4247ae18 906 system/1000/u0 local:41f68240}}
11-17 18:30:19.572  2925  2925 D NfcUiccLockService: -- To check whether previous opened channel needed to be closed ...
11-17 18:30:19.582   906  1103 I ActivityManager: Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2939 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
11-17 18:30:19.592   906  1103 D Process : killProcessQuiet, pid=2621
11-17 18:30:19.592   906  1103 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:19.592   906  1103 I ActivityManager: Killing 2621:com.htc.android.worldclock/u0a90 (adj 15): empty #17
11-17 18:30:19.602   906  2936 W SensorService: pid=906, uid=1000
11-17 18:30:19.602   906  2936 W SensorService: Active sensors: size = 3
11-17 18:30:19.602   906  2936 W SensorService: BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
11-17 18:30:19.602   906  2936 W SensorService: CM36282 Proximity sensor (handle=0x00000001, connections=1)
11-17 18:30:19.602   906  2936 W SensorService: CM36282 Light sensor (handle=0x00000002, connections=1)
11-17 18:30:19.602   906  2936 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423bbce0, eanble = 1, strlen(mName) = 36
11-17 18:30:19.602   906  2936 W SensorService: Active Listeners: mActiveListeners.size() = 3
11-17 18:30:19.602   906  2936 W SensorService: Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4210f860
11-17 18:30:19.602   906  2936 W SensorService: Listener[1] = com.android.server.power.DisplayPowerController$10@421f7a40
11-17 18:30:19.602   906  2936 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@423bbce0
11-17 18:30:19.602   906  2936 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
11-17 18:30:19.622  2790  2790 W jxcore-log: Initializing JXcore engine
11-17 18:30:19.622  2790  2790 W jxcore-log: JXcore engine is ready
11-17 18:30:19.632  2790  2790 W jxcore-log: Starting JXcore engine
11-17 18:30:19.642   906  1103 I ActivityManager: Recipient 2621
11-17 18:30:19.642   906  1316 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:19.642   906   916 D Process : killProcessQuiet, pid=2641
11-17 18:30:19.642   906   916 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:19.642   906   916 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2951 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
11-17 18:30:19.642   906   916 I ActivityManager: Killing 2641:com.htc.mobiledata/u0a91 (adj 15): empty #17
11-17 18:30:19.652   906  1353 I ActivityManager: Recipient 2641
11-17 18:30:19.652   906  1352 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:19.812  2790  2790 W jxcore-log: Platform android
11-17 18:30:19.812  2790  2790 W jxcore-log: 
,11-17 18:30:19.812  2790  2790 W jxcore-log: Process ARCH arm
11-17 18:30:19.812  2790  2790 W jxcore-log: 
,11-17 18:30:19.822  2951  2951 E YouTube : apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-17 18:30:19.852  2790  2790 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:30:19.852  2790  2790 I jxcore-log: 
,11-17 18:30:19.852  2790  2790 W jxcore-log: JXcore engine is started
,11-17 18:30:19.882  2951  2951 D libc    : [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,11-17 18:30:19.882  2951  2951 D libc    : [NET] getaddrinfo-, SUCCESS
,11-17 18:30:19.902  2951  2951 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:30:19.902  2790  2790 E jxcore-log: >> HTC-HTC Desire 820
11-17 18:30:19.902  2790  2790 E jxcore-log: 
,11-17 18:30:19.902  2790  2790 I jxcore-log: Total memory 1964650496
11-17 18:30:19.902  2790  2790 I jxcore-log: 
11-17 18:30:19.902  2790  2790 I jxcore-log: Free memory 715370496
11-17 18:30:19.902  2790  2790 I jxcore-log: 
11-17 18:30:19.902  2790  2790 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:19.902  2790  2790 I jxcore-log: 
,11-17 18:30:19.902  2790  2790 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:19.902  2790  2790 I jxcore-log: 
,11-17 18:30:19.912  2790  2790 I jxcore-log: userPath [ 'www' ]
11-17 18:30:19.912  2790  2790 I jxcore-log: 
,11-17 18:30:19.912  2790  2790 I jxcore-log: Size 720 1184
11-17 18:30:19.912  2790  2790 I jxcore-log: 
,11-17 18:30:19.912  2790  2790 I jxcore-log: Screen Brightness 142
11-17 18:30:19.912  2790  2790 I jxcore-log: 
,11-17 18:30:19.912  2790  2790 E jxcore-log: Dummy Error Log.
11-17 18:30:19.912  2790  2790 E jxcore-log: 
,11-17 18:30:19.962   906  1103 D ConnectivityService: getActiveNetworkInfo called by com.google.android.youtube (2951/10168)
,11-17 18:30:19.972   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:30:19.972  2951  2951 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
11-17 18:30:19.972   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:30:20.002  2951  2951 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:30:20.012  2951  2951 D YouTube : apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,11-17 18:30:20.062  2951  2983 D YouTube : apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,11-17 18:30:20.102  2951  2951 D YouTube : apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,11-17 18:30:20.112   906  1320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:30:20.112   906  1320 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:30:20.112   906  1320 D WifiDisplayAdapter:     GroupId: 
11-17 18:30:20.112   906  1320 D WifiDisplayAdapter:     Passphrase: 
11-17 18:30:20.112   906  1320 D WifiDisplayAdapter:     SessionId: 0
11-17 18:30:20.112   906  1320 D WifiDisplayAdapter:     IP Address: }
,11-17 18:30:20.122   906  1317 D MediaRouterService: Client com.google.android.youtube (pid 2951): Registered
,11-17 18:30:20.122  2951  2951 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter:     GroupId: 
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter:     Passphrase: 
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter:     SessionId: 0
11-17 18:30:20.122   906  1104 D WifiDisplayAdapter:     IP Address: }
,11-17 18:30:20.132  2951  2951 D YouTube : apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,11-17 18:30:20.132  2951  2986 I GoogleConversionPing: Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1447781420&data=screen_name%3D%3CAndroid_YT_Open_App%3E
11-17 18:30:20.132  2951  2986 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
11-17 18:30:20.132  2951  2986 D libc    : [NET] getaddrinfo-,err=8
11-17 18:30:20.132  2951  2986 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
11-17 18:30:20.132  2951  2986 D libc    : [NET] getaddrinfo-, 1
11-17 18:30:20.132  2951  2986 D libc    : [NET] getaddrinfo_proxy+
11-17 18:30:20.132   365  2996 D libc    : [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
11-17 18:30:20.132   906  1320 D ConnectivityService: getNetworkInfo networkType=0 called by com.google.android.youtube (2951/10168)
11-17 18:30:20.142   365  2996 D libc    : [NET] get_iface_protocol fail: 
11-17 18:30:20.142   365  2996 D libc    : [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
11-17 18:30:20.142   365  2996 D libc    : [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
11-17 18:30:20.142   365  2996 D libc    : [NET] getaddrinfo-,err=7
11-17 18:30:20.142  2951  2986 D libc    : [NET] getaddrinfo_proxy-
11-17 18:30:20.142  2951  2986 E GoogleConversionPing: Error sending ping
11-17 18:30:20.142   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
11-17 18:30:20.142  2951  2951 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
11-17 18:30:20.142   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:30:20.152  2951  2951 D YouTube : apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
11-17 18:30:20.152  2951  2951 D MediaRouter: getSelectedRoute
11-17 18:30:20.152  2951  2951 D YouTube : apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,11-17 18:30:20.162  2951  2992 D YouTube : apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
11-17 18:30:20.162   906  1320 D ConnectivityService: getActiveNetworkInfo called by com.google.android.youtube (2951/10168)
,11-17 18:30:20.172   906  1317 I ActivityManager: Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,11-17 18:30:20.172   906  1316 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.182  2951  2993 D YouTube : apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,11-17 18:30:20.192  2951  2966 D YouTube : apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,11-17 18:30:20.192  2951  2966 D YouTube : apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,11-17 18:30:20.402  1957  3000 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:30:20.422  1957  3000 D FileApkUtils: Spent 20ms computing apk sha1.
,11-17 18:30:20.422  1957  3000 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,11-17 18:30:20.432  1957  3000 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,11-17 18:30:20.432  1957  3000 D FileApkUtils: Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,11-17 18:30:20.442  1957  3000 D GmsModuleFndr: Beginning GMS chimera module scan
,11-17 18:30:20.442  1957  3000 W asset   : Copying FileAsset 0x652bf298 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,11-17 18:30:20.452  2790  2790 I jxcore-log: getBuffer is called!!!!
11-17 18:30:20.452  2790  2790 I jxcore-log: 
,11-17 18:30:20.452  1957  3000 W dalvikvm: VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:30:20.452  1957  3000 D ChimeraCfgMgr: Beginning module configuration check
,11-17 18:30:20.452  1957  3000 D ChimeraCfgMgr: Module APKs unchanged, check complete
11-17 18:30:20.452   906  1247 I ActivityManager: Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
11-17 18:30:20.462   906  1352 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.472   906  1317 I ActivityManager: Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,11-17 18:30:20.502  1957  3006 E dalvikvm: Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,11-17 18:30:20.502  1957  3006 W dalvikvm: VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
11-17 18:30:20.502   906  1353 D ConnectivityService: getActiveNetworkInfo called by com.google.android.gms (1957/10029)
11-17 18:30:20.512   906  1353 D PMS     : acquireWL(4261a260): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1957 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.512  1957  1957 E dalvikvm: Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,11-17 18:30:20.512  1957  1957 W dalvikvm: VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,11-17 18:30:20.522  1957  1957 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
11-17 18:30:20.522  1957  1957 W dalvikvm: VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,11-17 18:30:20.522  1957  1957 W dalvikvm: VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,11-17 18:30:20.532   906  1317 D PMS     : acquireWL(425c85a8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1957 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.532   906  1103 D PMS     : acquireWL(426a7518): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1957 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.532  1957  3006 D GCM     : COMPAT: Multi user not supported
,11-17 18:30:20.532  1336  3010 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
11-17 18:30:20.532   906  1247 D PMS     : releaseWL(4261a260): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.532   906  1320 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:30:20.542  1957  1957 I CheckinService: Checkin interval check for package: unspecified last checkin: 1447758960449 min interval config: 0 actual interval: 22460101
,11-17 18:30:20.552  1957  3006 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,11-17 18:30:20.552  1957  3013 I CheckinService: Disabling old GoogleServicesFramework version
,11-17 18:30:20.552  1201  1201 I GCoreUlr: DispatchingService.onCreate()
11-17 18:30:20.552   906  1352 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.552   906  1104 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.562  1957  1957 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:30:20.562  1957  1957 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:30:20.562  1957  1957 D SystemUpdateService: onCreate
11-17 18:30:20.562   906  1247 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.572  1957  1957 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 18:30:20.582  1957  1957 W dalvikvm: VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
11-17 18:30:20.582   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.582   906  1104 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.582   906  1320 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.582  1957  3019 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,11-17 18:30:20.592  1957  3018 I SystemUpdateService: cancelUpdate (empty URL)
,11-17 18:30:20.592  1957  3018 I SystemUpdateService: active receiver: disabled
,11-17 18:30:20.602  1957  3019 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,11-17 18:30:20.612   906  1317 D PMS     : acquireWL(424be618): PARTIAL_WAKE_LOCK  Icing 0x1 1957 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.612   906  1316 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.612   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1319 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1350 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1317 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1104 D PMS     : acquireWL(427bae88): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.622   906   916 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1320 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.622   906  1353 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.632   906  1352 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.632  1957  3018 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:30:20.632   906  1350 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.632   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.632   906  1104 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.632   906   917 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.632   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.642  1957  3015 I CheckinService: Checking schedule, now: 1447781420651 next: 1447758990383
,11-17 18:30:20.642  1957  3015 I CheckinService: active receiver: enabled
11-17 18:30:20.642   906   916 D PMS     : releaseWL(424be618): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.642   906  1103 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:20.642   906   933 W CpuWake : >>nativeReleaseCpuPerfWakeLock()
11-17 18:30:20.642   906   933 W CpuWake : <<nativeReleaseCpuPerfWakeLock()
11-17 18:30:20.642   906   933 W CpuWake : >>release mCpuPerf_cpu_count wakelock
11-17 18:30:20.642   906   933 W CpuWake : <<release mCpuPerf_cpu_count wakelock
11-17 18:30:20.642   906   933 W CpuWake : >>release mCpuPerf_Freq wakelock
11-17 18:30:20.642   906   933 W CpuWake : <<release mCpuPerf_Freq wakelock
11-17 18:30:20.642   906   951 D PMS     : releaseHCC(425e4818): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
11-17 18:30:20.642   906   951 D PMS     : releaseHCC(424fded0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
11-17 18:30:20.652   906   916 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.662   906  1352 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:20.662  1201  3020 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,11-17 18:30:20.662  1957  3019 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:20.662   906  1351 D ConnectivityService: getActiveNetworkInfo called by com.google.android.gms (1957/10029)
,11-17 18:30:20.662   906  1247 D PMS     : releaseWL(425c85a8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.672  1957  1957 D SystemUpdateService: onDestroy
,11-17 18:30:20.672  1957  3019 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:30:20.672  1957  3019 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:30:20.672  1957  3019 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
,11-17 18:30:20.672   906  1353 D PMS     : releaseWL(426a7518): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.682  1957  3019 W dalvikvm: VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,11-17 18:30:20.702  1957  3019 W dalvikvm: VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,11-17 18:30:20.732  1957  3019 I AuthZen : Fetching signing key...
,11-17 18:30:20.732   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1201, uid=10029, userID:0
,11-17 18:30:20.742  1957  3019 I AuthZen : Signing key fetched successfully!
,11-17 18:30:20.752  1957  3019 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:20.772  1957  3019 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,11-17 18:30:20.772  1957  3019 D AuthZenTransactionCache: Clearing transaction cache
,11-17 18:30:20.772  1201  3020 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,11-17 18:30:20.782   906  1104 D PMS     : acquireWL(427b35c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.792  1201  3020 I GCoreUlr: Unbound from all location providers
11-17 18:30:20.792   906  1351 D PMS     : releaseWL(427b35c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.792   906  1102 D PMS     : releaseWL(427bae88): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
11-17 18:30:20.792   906  1350 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.812   906  1320 D PMS     : acquireWL(427663e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1957 10029 null
,11-17 18:30:20.822   906  1320 D PMS     : acquireWL(4271ca60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1957 10029 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.832  1201  1201 I GCoreUlr: DispatchingService.onDestroy()
,11-17 18:30:20.832  1201  1201 I GCoreUlr: Stopping handler for UlrDispSvcFast
,11-17 18:30:20.832  1201  1201 I GCoreUlr: Unbound from all location providers
11-17 18:30:20.832   906  1103 D PMS     : acquireWL(426a66a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.832   906  1320 I ActivityManager: Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
11-17 18:30:20.832   906  1316 D PMS     : releaseWL(426a66a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:30:20.842  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
11-17 18:30:20.842   906  1103 D PMS     : releaseWL(427663e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
11-17 18:30:20.842   906  1316 D PMS     : releaseWL(4271ca60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:20.842   906  1102 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.852  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:30:20.852  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:20.862   906  1350 I ActivityManager: Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,11-17 18:30:20.862   906  1353 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.872  1336  1336 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,11-17 18:30:20.872  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:20.872   906  1103 D PMS     : acquireWL(428643b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1336 10029 null
11-17 18:30:20.872   906  1316 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,11-17 18:30:20.882   906  1320 D PMS     : releaseWL(428643b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,11-17 18:30:20.882   906  1351 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:20.902  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,11-17 18:30:20.912  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:30:20.912  1336  1336 W dalvikvm: VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,11-17 18:30:20.922  1957  1957 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,11-17 18:30:20.932  1336  1336 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,11-17 18:30:20.952   906   916 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3037 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,11-17 18:30:21.102   906   934 D ConnectivityService: getActiveNetworkInfo called by  (906/1000)
,11-17 18:30:21.102   906   934 D PMS     : acquireWL(42874c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,11-17 18:30:21.102   906   934 D PMS     : releaseWL(42874c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,11-17 18:30:21.112   906  1319 I ActivityManager: Killing 2452:com.android.defcontainer/u0a19 (adj 15): empty #17
11-17 18:30:21.122   906  1319 D Process : killProcessQuiet, pid=2452
11-17 18:30:21.122   906  1319 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,11-17 18:30:21.132   906  1317 I ActivityManager: Recipient 2452
,11-17 18:30:21.132   906  1320 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:21.162  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,11-17 18:30:21.182   906  1350 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3037, uid=10074, userID:0
,11-17 18:30:21.222  3037  3037 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
11-17 18:30:21.222   906  1319 D ConnectivityService: getAllNetworkInfo called by com.android.vending (3037/10074)
,11-17 18:30:21.312  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,11-17 18:30:21.322  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,11-17 18:30:21.322   906  1104 D ConnectivityService: getAllNetworkInfo called by com.android.vending (3037/10074)
,11-17 18:30:21.342  3037  3037 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,11-17 18:30:21.342  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,11-17 18:30:21.352  3037  3037 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:30:21.362  3037  3037 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:30:21.382  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:30:21.392  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:30:21.392  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,11-17 18:30:21.422  3037  3037 W dalvikvm: VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
11-17 18:30:21.422   906  1350 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3037, uid=10074, userID:0
,11-17 18:30:21.482  3037  3054 D Volley  : [276] DiskBasedCache.clear: Cache cleared.
,11-17 18:30:21.482  3037  3061 D Volley  : [283] DiskBasedCache.clear: Cache cleared.
,11-17 18:30:21.482   906  1317 D Process : killProcessQuiet, pid=2653
,11-17 18:30:21.482   906  1317 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:30:21.482   906  1317 I ActivityManager: Killing 2653:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,11-17 18:30:21.492   906  1348 I ActivityManager: Recipient 2653
,11-17 18:30:21.492  3037  3074 D Ads     : Skipping gmscore version check
,11-17 18:30:21.492  3037  3037 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:30:21.492  3037  3037 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,11-17 18:30:21.492  3037  3037 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
11-17 18:30:21.492   906  1353 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:21.502   906  1316 I ActivityManager: Delay finish: com.htc.dotmatrix/.CoverStateReceiver
,11-17 18:30:21.512  1290  3077 D AutoSetting: receiver - intent: android.intent.action.USER_PRESENT
,11-17 18:30:21.512  3037  3037 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
11-17 18:30:21.512  2903  2903 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:30:21.512  2903  2903 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:30:21.512  2903  2903 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:30:21.512  2903  2903 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:30:21.512  2903  2903 D         : Cust_ConnectToPC   : IPT>true
11-17 18:30:21.512  2903  2903 D         : Cust_ConnectToPC   : Singel_USB>false
11-17 18:30:21.512  2903  2903 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:21.512  2903  2903 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:30:21.512  2903  2903 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
11-17 18:30:21.512  2903  2903 D SmartNS_NSReceiver: onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,11-17 18:30:21.512  1290  1290 D AutoSetting: service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,11-17 18:30:21.512   906   917 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:21.522  2903  2903 I PSReceiver: onReceive:android.intent.action.USER_PRESENT
,11-17 18:30:21.522  2903  2903 I SmartNS_PSService: onReceive:android.intent.action.USER_PRESENT
11-17 18:30:21.522  2903  2903 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:30:21.522  2903  2903 I SmartNS_PSService:  defaultType:0
11-17 18:30:21.522  2903  2903 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:30:21.562   906  1104 I ActivityManager: Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3079 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,11-17 18:30:21.592  3079  3079 D browser : Browser versionCode = 760001523 versionName = 7.0.2512153020
,11-17 18:30:21.612  3079  3079 W SWE_UI  : SWE using SurfaceView - Multi-Process
,11-17 18:30:21.612  3079  3079 I LibraryLoader: Loading: swewebviewchromium
,11-17 18:30:21.642  3079  3079 I LibraryLoader: Time to load native libraries: 38 ms (timestamps 1615-1653)
,11-17 18:30:21.642  3079  3079 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:30:21.642  3079  3079 I BrowserStartupController: Initializing chromium process, renderers=9
,11-17 18:30:21.652  3079  3079 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 18:30:21.652  3079  3079 I chromium: [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,11-17 18:30:21.702  1473  2111 I HtcModeClient: handler message = 4011
,11-17 18:30:21.702  1473  2111 E HtcModeClient: Check connection and retry 4 times.
,11-17 18:30:21.752  2685  2701 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:21.762  1957  1957 I GAv4-SVC: Google Analytics 8.3.01 is starting up.
,11-17 18:30:21.772   906  1102 D PMS     : releaseWL(41d9db10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,11-17 18:30:21.912  3079  3102 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,11-17 18:30:22.032  3079  3079 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
11-17 18:30:22.032  3079  3079 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.02.07
11-17 18:30:22.032  3079  3079 I Adreno-EGL: Build Date: 08/28/14 Thu
11-17 18:30:22.032  3079  3079 I Adreno-EGL: Local Branch: 
11-17 18:30:22.032  3079  3079 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
11-17 18:30:22.032  3079  3079 I Adreno-EGL: Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
11-17 18:30:22.032  3079  3079 I Adreno-EGL:                  aa63bbd948f41d15fc72f585e
,11-17 18:30:22.072   906  1350 D Process : killProcessQuiet, pid=2685
,11-17 18:30:22.072   906  1350 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,11-17 18:30:22.072   906  1350 I ActivityManager: Killing 2685:com.google.android.gm/u0a107 (adj 15): empty #17
11-17 18:30:22.082  1275  1275 V IccIntentReceiver: IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
11-17 18:30:22.082  1473  1473 I SIMStateChangeReceiver: SIM state: ABSENT
,11-17 18:30:22.082  1473  1473 I SIMStateChangeReceiver: phoneType = 0
11-17 18:30:22.082  1473  1473 I SIMStateChangeReceiver: remove notification
,11-17 18:30:22.112   906  1352 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3124 uid=10032 gids={50032, 3003, 5012}
,11-17 18:30:22.192   906   917 D Process : killProcessQuiet, pid=2731
,11-17 18:30:22.192   906   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:22.192   906   917 I ActivityManager: Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3136 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
11-17 18:30:22.192   906   917 I ActivityManager: Killing 2731:com.htc.backup/1000 (adj 15): empty #17
,11-17 18:30:22.202   906  1350 I ActivityManager: Recipient 2685
,11-17 18:30:22.202   906  1103 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.262  2472  2472 W SystemReader: Cannot find message_ambs_application_id, use default value instead
,11-17 18:30:22.262  2472  3150 D SmsReceiver: Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,11-17 18:30:22.262  2472  2472 D ExchangePolicystatus: onReceive()
,11-17 18:30:22.262  2472  2472 D ExchangePolicystatus: onReceive(): ACTION_SIM_STATE_CHANGED
,11-17 18:30:22.272  2472  2472 D ExchangePolicystatus: onReceive(): else
,11-17 18:30:22.272   906  1247 D Process : killProcessQuiet, pid=2668
,11-17 18:30:22.272   906  1247 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,11-17 18:30:22.272  1222  1222 D HtcBroadcastReceiver: onReceive: android.intent.action.SIM_STATE_CHANGED
11-17 18:30:22.272   906  1247 I ActivityManager: Killing 2668:com.htc.cs.dm/u0a98 (adj 15): empty #17
,11-17 18:30:22.282  1111  3151 W WeatherUtility: can't get weather sync account
11-17 18:30:22.292   906  1348 I ActivityManager: Recipient 2731
11-17 18:30:22.292   906  1319 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.312   906   917 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3153 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,11-17 18:30:22.332  1111  3151 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:30:22.342  3136  3166 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,11-17 18:30:22.362  3153  3153 D CalendarApplication: onCreate
11-17 18:30:22.362  3153  3153 D ProviderChangeReceiver: ---------------------------------------------------
,11-17 18:30:22.362  3153  3153 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start to update notification!
,11-17 18:30:22.362  3153  3169 D AlertService: start to updateAlertNotification!
,11-17 18:30:22.372  3136  3166 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:30:22.372  3136  3166 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
11-17 18:30:22.372  2878  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:22.382   906  1352 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:22.382   906  1319 I ActivityManager: Recipient 2668
,11-17 18:30:22.392   906  1348 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3171 uid=10041 gids={50041}
,11-17 18:30:22.402  3153  3169 D AlertService: No fired or scheduled alerts
,11-17 18:30:22.402  3153  3169 D HtcAlertUtils: -- cancelReminderNotification --
,11-17 18:30:22.402  3153  3169 D HtcAlertUtils: broadcastExistReminder!
,11-17 18:30:22.402  1532  1532 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,11-17 18:30:22.412   906  1320 D Process : killProcessQuiet, pid=2756
,11-17 18:30:22.412   906  1320 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,11-17 18:30:22.412   906  1320 I ActivityManager: Killing 2756:com.google.android.talk/u0a111 (adj 15): empty #17
11-17 18:30:22.422  3136  3166 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:30:22.432  3136  3166 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,11-17 18:30:22.442  3136  3166 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:30:22.442  3136  3166 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:30:22.462   906  1316 D Process : killProcessQuiet, pid=2806
,11-17 18:30:22.462   906  1316 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:22.462   906  1316 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3185 uid=10078 gids={50078}
11-17 18:30:22.462   906  1316 I ActivityManager: Killing 2806:com.htc.backupreset/1000 (adj 15): empty #17
,11-17 18:30:22.472   906  1247 I ActivityManager: Recipient 2806
,11-17 18:30:22.472  3136  3166 E ExternalAccountType: Unsupported attribute readOnly
11-17 18:30:22.472   906  1103 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:22.472   906  1319 I ActivityManager: Recipient 2756
11-17 18:30:22.472   906  1102 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.492  3185  3185 D SMSBackup: Got a database change event
,11-17 18:30:22.502   906  1350 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3197 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,11-17 18:30:22.502   906  1350 D Process : killProcessQuiet, pid=2835
,11-17 18:30:22.502   906  1350 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:22.502   906  1350 I ActivityManager: Killing 2835:com.htc.htccupd/u0a17 (adj 15): empty #17
,11-17 18:30:22.512   906   916 I ActivityManager: Recipient 2835
,11-17 18:30:22.512   906  1247 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.552   906  1352 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3212 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,11-17 18:30:22.562  3197  3210 W WeatherUtility: can't get weather sync account
,11-17 18:30:22.582  3197  3210 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:30:22.592  3197  3210 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:30:22.592  3212  3212 I DemoRecovery.RestoreReceiver: onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,11-17 18:30:22.592  3212  3212 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,11-17 18:30:22.602  3212  3224 I RestoreService: onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,11-17 18:30:22.602  1249  1249 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:30:22.602  1249  1249 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
11-17 18:30:22.602   906   917 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
11-17 18:30:22.602   906  1350 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:22.622  1249  1249 I RemoteViews.Performance: com.htc.widget.weatherclock 2 14 17
,11-17 18:30:22.622   906  1247 D Process : killProcessQuiet, pid=2856
,11-17 18:30:22.622   906  1247 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:22.622   906  1247 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3226 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
11-17 18:30:22.622   906  1247 I ActivityManager: Killing 2856:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,11-17 18:30:22.632   906  1104 I ActivityManager: Recipient 2856
,11-17 18:30:22.632   906   916 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.672   906  1103 D PMS     : acquireWL(42489070): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3226 10071 null
,11-17 18:30:22.682   906  1320 D PMS     : acquireWL(42485258): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3226 10071 null
,11-17 18:30:22.682   906  1348 I ActivityManager: Delay finish: com.htc.task/.TodoReceiver
,11-17 18:30:22.682   906  1353 D PMS     : releaseWL(42489070): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
11-17 18:30:22.692  3226  3239 D TodoTaskshortcut: update TASK shortcut>
,11-17 18:30:22.722  3226  3240 I TodoTaskNotifyService: Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,11-17 18:30:22.722  1532  1532 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,11-17 18:30:22.732  3226  3240 W NotifyReceiver: stopSelfResult true
11-17 18:30:22.732   906  1350 D PMS     : releaseWL(42485258): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
11-17 18:30:22.732   906  1351 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:22.752   906  1351 I ActivityManager: Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3241 uid=10082 gids={50082, 3003, 5012}
,11-17 18:30:22.752   906  1352 D Process : killProcessQuiet, pid=2893
,11-17 18:30:22.752   906  1352 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:22.752   906  1352 I ActivityManager: Killing 2893:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,11-17 18:30:22.762   906   917 I ActivityManager: Recipient 2893
,11-17 18:30:22.762   906  1320 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.802   906  1319 I ActivityManager: Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3253 uid=10082 gids={50082, 3003, 5012}
,11-17 18:30:22.882   906  1103 I ActivityManager: Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3265 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,11-17 18:30:22.882   906  1103 D Process : killProcessQuiet, pid=2939
,11-17 18:30:22.882   906  1103 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,11-17 18:30:22.882   906  1103 D Process : killProcessQuiet, pid=2925
,11-17 18:30:22.882   906  1103 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:22.882   906  1103 I ActivityManager: Killing 2939:com.android.smith/u0a163 (adj 15): empty #17
11-17 18:30:22.882   906  1103 I ActivityManager: Killing 2925:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
,11-17 18:30:22.892   906  1102 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.892   906  1350 I ActivityManager: Recipient 2939
,11-17 18:30:22.952  3265  3265 I ImageRamCache: create image Cache, size: 31457280.
11-17 18:30:22.952  3265  3265 I ImageRamCache: [resize] ImageRamCache resized to: 12Mb.
,11-17 18:30:22.952  3265  3265 I ImageRamCache: create image Cache, size: 12582912.
,11-17 18:30:22.962  3265  3265 I FeedSettings: [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
11-17 18:30:22.962  3265  3265 I FeedSettings: GroupBudget 0.500000 0.380000
,11-17 18:30:22.962  3265  3265 I FeedSettings: GroupBudget 60 45 15
,11-17 18:30:22.962  3265  3265 I Prism.ExternalStringMa_: changeLocale(): en_GB
,11-17 18:30:22.972  3265  3265 I Prism.AllAppsOptionsMa_: loadSortType() with Custom
,11-17 18:30:22.972  3265  3265 I Prism.AllAppsOptionsMa_: loadGridSize() with Alternative
,11-17 18:30:22.982   906  1320 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:22.982  3265  3265 D CustomHighlightReceiver: [custom highlight] onReceive
11-17 18:30:22.982   906   916 I ActivityManager: Recipient 2925
,11-17 18:30:22.992  3265  3279 D CustomHighlightService: [custom highlight] onHandleIntent
,11-17 18:30:22.992  3265  3279 D NewsDB  : set custom highlight []
11-17 18:30:22.992   906  1102 I ActivityManager: Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,11-17 18:30:23.022  3265  3279 D CustomHighlightService: [custom highlight] set tags 
,11-17 18:30:23.022  3185  3185 D SMSBackup: Got a database change event
,11-17 18:30:23.022   906  1351 I ActivityManager: Resuming delayed broadcast
11-17 18:30:23.032  2472  2472 D MessagingShortcutReceiver: keep hiding shortcut bubble
11-17 18:30:23.032  2472  2472 D MessagingShortcut: updateMsgShortcut, msg count> -1,
11-17 18:30:23.032  2472  2472 D MessagingShortcut: After query: 0
11-17 18:30:23.032  2472  2472 D MessagingShortcut: mPresentUnreadCount: -1
11-17 18:30:23.032  2472  2472 D MessagingShortcut: setMsgShortcutDrawable> 0
11-17 18:30:23.032  2472  2472 D MessagingShortcut: Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
11-17 18:30:23.042  1532  1532 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
11-17 18:30:23.042  1532  1532 D DotMatrix: [EventService] reorderNotification, total:0
11-17 18:30:23.042  1532  1532 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,11-17 18:30:23.042  1532  1532 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,11-17 18:30:23.042  3226  3280 D TodoTaskshortcut: update TASK shortcut>
11-17 18:30:23.042   906  1102 I ActivityManager: Delay finish: com.htc.task/.TodoReceiver
,11-17 18:30:23.052  1222  1222 D HtcBroadcastReceiver: onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,11-17 18:30:23.052   906  1317 D Process : killProcessQuiet, pid=2951
,11-17 18:30:23.052   906  1317 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:23.052   906  1104 I ActivityManager: Resuming delayed broadcast
11-17 18:30:23.052   906  1317 I ActivityManager: Killing 2951:com.google.android.youtube/u0a168 (adj 15): empty #17
,11-17 18:30:23.072   906  1317 I ActivityManager: Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3281 uid=10091 gids={50091, 3003, 5012}
,11-17 18:30:23.102   906  1247 I ActivityManager: Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,11-17 18:30:23.112  2472  2502 D MessagingNotification: New incoming message, can't cancel notification now
,11-17 18:30:23.112  2472  2502 D MessagingNotification: newMsgCnt: 0, false
,11-17 18:30:23.122   906  1352 I ActivityManager: Recipient 2951
11-17 18:30:23.122   906  1104 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:23.122   906  1350 D MediaRouterService: Client com.google.android.youtube (pid 2951): Died!
,11-17 18:30:23.122   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360022842
,11-17 18:30:23.122   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023216
,11-17 18:30:23.122   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023560
,11-17 18:30:23.132   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023564
,11-17 18:30:23.132   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023567
,11-17 18:30:23.132   906  1102 W AlarmManager: Converted elapesd time is over 1 year! when = 315360027688
,11-17 18:30:23.132   906  1077 V AlarmManager: sending alarm PendingIntent{42040e50: PendingIntentRecord{4262d868 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20714, Int=1800000
,11-17 18:30:23.132   906  1077 V AlarmManager: sending alarm PendingIntent{4268c0f0: PendingIntentRecord{426619c0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=46051, Int=259200000
,11-17 18:30:23.142   906  1316 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3296 uid=10091 gids={50091, 3003, 5012}
,11-17 18:30:23.152   906  1077 V AlarmManager: sending alarm PendingIntent{41e26938: PendingIntentRecord{424f9240 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49789, Int=0
,11-17 18:30:23.152   906  1077 V AlarmManager: sending alarm PendingIntent{42459910: PendingIntentRecord{42656628 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1447758000000, Int=86400000
,11-17 18:30:23.212  3281  3294 D MdScBoot: [210.1.] 30@-182956 -> 40@-183023
11-17 18:30:23.212   906  1102 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.212   906  1320 D Process : killProcessQuiet, pid=3037
,11-17 18:30:23.212   906  1320 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:23.212   906  1320 I ActivityManager: Killing 3037:com.android.vending/u0a74 (adj 15): empty #17
,11-17 18:30:23.222   906   917 D Process : killProcessQuiet, pid=2903
,11-17 18:30:23.222   906   917 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:30:23.222   906   917 I ActivityManager: Killing 2903:com.android.settings/1000 (adj 15): empty #17
,11-17 18:30:23.232   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:23.232  1201  1201 D WearableService: callingUid 10029, callindPid: 1201
11-17 18:30:23.232   906  1319 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:23.232   906  1103 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
11-17 18:30:23.232   906  1320 I ActivityManager: Recipient 2903
11-17 18:30:23.232   906  1317 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:23.242  1201  3308 E MDM     : [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,11-17 18:30:23.262  1957  3309 D LocationInitializer: Restart initialization of location
11-17 18:30:23.262   906  1317 I ActivityManager: Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,11-17 18:30:23.282   906  1348 D PMS     : acquireWL(4241bd10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
11-17 18:30:23.292  1201  1499 W GCoreFlp: No location to return for getLastLocation()
,11-17 18:30:23.292  1336  3310 W FusedLocationProvider: location=null
11-17 18:30:23.292   906  1317 D PMS     : releaseWL(4241bd10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360022842
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023216
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023560
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023564
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023567
11-17 18:30:23.292   906  1103 W AlarmManager: Converted elapesd time is over 1 year! when = 315360027688
11-17 18:30:23.292   906  1316 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.302  1336  3311 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,11-17 18:30:23.302  1336  1336 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:30:23.302  1336  1336 E AuthorizationBluetoothService: Proximity feature is not enabled.
11-17 18:30:23.302   906   917 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:30:23.312  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:23.312   906  1317 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
11-17 18:30:23.312   906  1348 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.322  1957  1957 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:30:23.322   906  1316 I ActivityManager: Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
11-17 18:30:23.322   906  1247 I ActivityManager: Resuming delayed broadcast
11-17 18:30:23.332   906  1317 I ActivityManager: Recipient 3037
11-17 18:30:23.332   906  1348 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:23.362   906  1320 D PMS     : acquireWL(42631ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.362   906  1103 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:30:23.372   906  1351 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:23.372   906  1320 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:23.382  1201  3314 E MDM     : [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
11-17 18:30:23.382   906  1319 D PMS     : releaseWL(42631ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:23.382   906  1103 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1957, uid=10029, userID:0
,11-17 18:30:23.402  1957  3315 D LocationInitializer: Restart initialization of location
11-17 18:30:23.402   906  1317 I ActivityManager: Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,11-17 18:30:23.412  1201  1499 W GCoreFlp: No location to return for getLastLocation()
,11-17 18:30:23.412  1336  3316 W FusedLocationProvider: location=null
11-17 18:30:23.412   906  1320 D PMS     : acquireWL(4261a3b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.422  1336  3317 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:30:23.422   906   916 D PMS     : releaseWL(4261a3b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360022842
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023216
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023560
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023564
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023567
11-17 18:30:23.422   906  1348 W AlarmManager: Converted elapesd time is over 1 year! when = 315360027688
11-17 18:30:23.422   906   917 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.432  1336  1336 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:30:23.432  1336  1336 E AuthorizationBluetoothService: Proximity feature is not enabled.
11-17 18:30:23.432   906  1102 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:30:23.442  1336  1336 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:23.442   906  1319 I ActivityManager: Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
11-17 18:30:23.442   906  1320 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.452   906  1319 I ActivityManager: Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,11-17 18:30:23.452  1957  1957 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:30:23.452   906   917 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:23.462   906  1104 D PMS     : acquireWL(42730200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.462   906  1319 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
,11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360022842
,11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023216
11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023560
,11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023564
11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023567
,11-17 18:30:23.472   906   916 W AlarmManager: Converted elapesd time is over 1 year! when = 315360027688
,11-17 18:30:23.472   906  1320 D PMS     : releaseWL(42730200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.512   906  1348 D PMS     : acquireWL(42877350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10029 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.512  2166  2166 D MtpReceiver: [MTP][MtpReceiver][onReceive]+
11-17 18:30:23.512  2166  2166 D MtpReceiver: [MTP][MtpReceiver][onReceive]1-
,11-17 18:30:23.512  2166  3320 D MtpReceiver: [MTP][handleMessage][startService]
,11-17 18:30:23.512   906  1102 D ConnectivityService: getActiveNetworkInfo called by  (1336/10029)
11-17 18:30:23.522  2166  3320 D MtpReceiver: [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,11-17 18:30:23.522  2166  3320 D MtpReceiver: [MTP][handleMessage]-
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360022842
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023216
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023560
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023564
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360023567
11-17 18:30:23.522   906  1352 W AlarmManager: Converted elapesd time is over 1 year! when = 315360027688
,11-17 18:30:23.532   906  1104 D PMS     : releaseWL(42877350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,11-17 18:30:23.542  2166  2166 D MtpService: [MTP] startForeground
,11-17 18:30:23.542   906  1320 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3321 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
11-17 18:30:23.552  1111  1111 I RemoteViews: com.android.providers.media (false,0)
11-17 18:30:23.552  1111  1111 I RemoteViews.Performance: com.android.providers.media 1 1 10
11-17 18:30:23.552  1111  1111 I RemoteViews: com.android.providers.media (false,0)
11-17 18:30:23.552  1111  1111 I RemoteViews.Performance: com.android.providers.media 0 1 15
11-17 18:30:23.552  2166  2166 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
11-17 18:30:23.552  1532  1544 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,11-17 18:30:23.552  2166  2166 D MtpDatabase: TotalSize=1918604,MediaCacheLimit=6000
,11-17 18:30:23.552   906   916 D PMS     : acquireWL(426a0ff8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1957 10029 null
11-17 18:30:23.562  2166  2166 D MtpService: [isMtpConnected] connected: true
,11-17 18:30:23.612  3321  3321 D SyncApplication: Loading default preferences
,11-17 18:30:23.622  1957  3333 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 56 ms
,11-17 18:30:23.622  3321  3321 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
11-17 18:30:23.622   906  1348 D PMS     : releaseWL(426a0ff8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,11-17 18:30:23.652   906  1090 D WifiService: New client listening to asynchronous messages
,11-17 18:30:23.662  3321  3321 D SyncApplication: Overriding preferences with custom values
,11-17 18:30:23.672  3321  3321 D SyncApplication: Updating preferences succeeded
,11-17 18:30:23.672  3321  3321 E SyncApplication: Application created.
,11-17 18:30:23.672  3321  3338 D VolumeInfo: check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
11-17 18:30:23.682  3321  3338 D VolumeInfo: The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
11-17 18:30:23.682  3321  3338 V VolumeInfo: Found 0 mount point(s)
,11-17 18:30:23.682  3321  3338 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,11-17 18:30:23.682  3321  3338 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,11-17 18:30:23.682  3321  3338 D VolumeInfo: Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,11-17 18:30:23.682  3321  3338 W VolumeInfo: Can not create volume ID for unmounted volume null
,11-17 18:30:23.692  3321  3321 I CalendarDefines: getNewCalendarAuthority()...
11-17 18:30:23.692   906  1350 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3321, uid=10008, userID:0
11-17 18:30:23.692   906  1350 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
11-17 18:30:23.692   906  1348 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3321, uid=10008, userID:0
,11-17 18:30:23.692   906  1348 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
11-17 18:30:23.702  3321  3321 D SyncApplication: enableAppOperation()+
11-17 18:30:23.702  3321  3321 D SyncApplication: enableAppOperation()-
11-17 18:30:23.702  3321  3321 D HTCUtilities: isNeorSinged() + 
,11-17 18:30:23.732  3321  3321 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,11-17 18:30:23.732  3321  3321 D HTCUtilities: isNeorSinged() return false
,11-17 18:30:23.742  3321  3321 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,11-17 18:30:23.742  3321  3321 D CDMountReceiver: USB connected to PC
,11-17 18:30:23.752  3321  3321 D FOTAReceiver: onReceive() enter 
,11-17 18:30:23.752  3321  3321 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,11-17 18:30:23.772   906  1353 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3341 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,11-17 18:30:23.782   906  1353 D Process : killProcessQuiet, pid=3079
,11-17 18:30:23.782   906  1353 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
11-17 18:30:23.782   906  1353 I ActivityManager: Killing 3079:com.htc.sense.browser/u0a12 (adj 15): empty #17
,11-17 18:30:23.922   906  1352 I ActivityManager: Recipient 3079
,11-17 18:30:23.922   906  1348 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:23.972  3341  3341 D HtcFingerPrintQuickLaunchProvider: -onCreate()
,11-17 18:30:23.972  3341  3341 V Settings:HtcSettingsApplication: [3341/3341] onCreate()
,11-17 18:30:23.982  3341  3341 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:30:23.982  3341  3341 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:30:23.982  3341  3341 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:30:23.982  3341  3341 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:30:23.982  3341  3341 D         : Cust_ConnectToPC   : IPT>true
,11-17 18:30:23.982  3341  3341 D         : Cust_ConnectToPC   : Singel_USB>false
,11-17 18:30:23.992  3341  3341 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:23.992  3341  3341 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
11-17 18:30:23.992  3341  3341 D         : Cust_ConnectToPC   : Internet_Sharing>true
11-17 18:30:23.992  3341  3341 D         : Cust_ConnectToPC   : Modem_Link>false
11-17 18:30:23.992  3341  3341 D         : Cust_ConnectToPC   : spcsc>false
11-17 18:30:23.992  3341  3341 D         : Cust_ConnectToPC   : IPT>true
11-17 18:30:23.992  3341  3341 D         : Cust_ConnectToPC   : Singel_USB>false
,11-17 18:30:23.992  3341  3341 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:23.992  3341  3341 E SmartNS_Utility: hasRemovableStorageSlot: true
11-17 18:30:23.992  3341  3341 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,11-17 18:30:23.992  3341  3341 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
11-17 18:30:23.992  3341  3341 D SmartNS_Utility: usb_cable_connect = 1
,11-17 18:30:23.992  3341  3341 D SmartNS_Utility: usb_denied = 0
11-17 18:30:24.002  3341  3341 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
,11-17 18:30:24.002  3341  3341 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
,11-17 18:30:24.002  3341  3341 I PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC
,11-17 18:30:24.002  3341  3341 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC
11-17 18:30:24.002  3341  3341 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:24.002  3341  3341 I SmartNS_PSService:  defaultType:0
,11-17 18:30:24.002  3341  3341 I SmartNS_PSService: fail notificaiton:false
,11-17 18:30:24.002  3341  3341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
11-17 18:30:24.012  3341  3341 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:30:24.012  3341  3341 D SmartNS_Utility: usb_denied = 0
,11-17 18:30:24.012  3341  3341 I SmartNS_PSService: usb notificaiton:true
,11-17 18:30:24.012   906  1247 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
,11-17 18:30:24.012   906  1247 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,11-17 18:30:24.012   906  1247 V Tethering: bSetPropertyMultiRAB:false
11-17 18:30:24.012   906  1353 I ActivityManager: Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
11-17 18:30:24.012   906  1247 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (3341/1000)
,11-17 18:30:24.012   906  1317 I ActivityManager: Resuming delayed broadcast
11-17 18:30:24.022  3341  3341 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:30:24.022  3341  3341 D SmartNS_Utility: usb_denied = 0
11-17 18:30:24.022  3341  3341 I SmartNS_PSService: usb notificaiton:true
11-17 18:30:24.022   906  1247 V Tethering: mTetherableUsbRegexs:{(usb0)(ncm0)}
11-17 18:30:24.022  1111  1111 I RemoteViews: com.android.settings (true,33751552)
11-17 18:30:24.022  1111  1111 I RemoteViews.Performance: com.android.settings 2 0 10
11-17 18:30:24.022   906  1247 D Tethering: Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,11-17 18:30:24.022   906  1247 V Tethering: bSetPropertyMultiRAB:false
,11-17 18:30:24.022  1532  2753 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,11-17 18:30:24.022  3197  3357 W WeatherUtility: can't get weather sync account
11-17 18:30:24.022   906  1247 D ConnectivityService: getActiveNetworkInfo called by com.android.settings (3341/1000)
,11-17 18:30:24.022   906  1102 I ActivityManager: Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
11-17 18:30:24.032  1111  1111 I RemoteViews: com.android.settings (true,33751552)
11-17 18:30:24.032  3341  3341 D SmartNS_Utility: usb_cable_connect = 1
11-17 18:30:24.032  1532  2754 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
11-17 18:30:24.032  1111  1111 I RemoteViews.Performance: com.android.settings 1 1 10
11-17 18:30:24.032  3341  3341 D SmartNS_Utility: usb_denied = 0
11-17 18:30:24.032  3341  3341 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false
,11-17 18:30:24.032  3341  3341 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
11-17 18:30:24.032   906  1317 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:24.052  3197  3357 W WeatherRequest: request cur loc, but there is no sys cur
,11-17 18:30:24.052  3197  3357 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:30:24.052  1249  1249 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
11-17 18:30:24.052  1249  1249 I RemoteViews: com.google.android.googlequicksearchbox (false,0)
,11-17 18:30:24.052  1249  1249 I RemoteViews.Performance: com.google.android.googlequicksearchbox 0 0 5
,11-17 18:30:24.052  1249  1249 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:30:24.052  1249  1249 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
,11-17 18:30:24.062  1249  1249 I RemoteViews.Performance: com.htc.widget.weatherclock 0 6 17
11-17 18:30:24.072   906   917 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3358 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,11-17 18:30:24.292  3358  3358 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,11-17 18:30:24.292  3358  3370 D PowerUsageService: call getInstance()
11-17 18:30:24.292   906  1353 I ActivityManager: Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,11-17 18:30:24.302  3358  3370 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,11-17 18:30:24.312   906  1351 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:30:24.442   906  1352 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:30:24.502   906  1350 W BatSI   : Couldn't get kernel wake lock stats
,11-17 18:30:24.712   906   917 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:24.732   906  1351 D Process : killProcessQuiet, pid=3124
,11-17 18:30:24.732   906  1351 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
11-17 18:30:24.732   906  1316 D PMS     : acquireWL(4287a910): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3358 1000 null
11-17 18:30:24.732   906  1351 I ActivityManager: Killing 3124:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,11-17 18:30:24.752   906   916 I ActivityManager: Recipient 3124
,11-17 18:30:24.752   906  1103 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:24.872  1111  3373 W WeatherUtility: can't get weather sync account
,11-17 18:30:24.882  1290  3375 D WeatherUtility: Weather sync is On
11-17 18:30:24.882   906  1102 D PMS     : releaseWL(4287a910): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,11-17 18:30:24.892   906  1353 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3376 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,11-17 18:30:24.902  1290  3375 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
11-17 18:30:24.902  3197  3380 W WeatherUtility: can't get weather sync account
,11-17 18:30:24.922   906  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:30:24.922   906  1104 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:30:24.922   906  1104 W HtcDLNAServiceManager: Settings:AgentMONITOR_LOG
11-17 18:30:24.922   906  1104 W HtcDLNAServiceManager: Settings:Agentname: bluetooth_on
,11-17 18:30:24.922   906  1104 W HtcDLNAServiceManager: Settings:Agentvalue: 0
11-17 18:30:24.922   906  1104 W Settings:Agent: >> traceCallingStack()
,11-17 18:30:24.922   906  1104 W Settings:Agent: Process.myPid(): 906
,11-17 18:30:24.922   906  1104 W Settings:Agent: Process.myTid(): 1104
,11-17 18:30:24.932   906  1104 W Settings:Agent: Process.myUid(): 1000
,11-17 18:30:24.932   906  1104 W Settings:Agent: 
,11-17 18:30:24.932   906  1104 W Settings:Agent: 
,11-17 18:30:24.932   906  1104 W System.err: java.lang.Throwable: stack dump
11-17 18:30:24.932   906  1104 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
,11-17 18:30:24.932   906  1104 W System.err: 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
11-17 18:30:24.932   906  1104 W System.err: 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
11-17 18:30:24.932   906  1104 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
11-17 18:30:24.932   906  1104 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:6170)
11-17 18:30:24.932   906  1104 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:6264)
11-17 18:30:24.932   906  1104 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
11-17 18:30:24.932   906  1104 W System.err: 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
11-17 18:30:24.932   906  1104 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
11-17 18:30:24.932   906  1104 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:30:24.932   906  1104 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:30:24.932   906  1104 W Settings:Agent: 
,11-17 18:30:24.932   906  1104 W Settings:Agent: << traceCallingStack(): 7(ms)
,11-17 18:30:24.932   906   944 D BluetoothManagerService: Message: MESSAGE_DISABLE
,11-17 18:30:24.942  2790  2790 D WifiManager: setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,11-17 18:30:24.942   906  1353 W HtcDLNAServiceManager: Settings:AgentMONITOR_LOG
,11-17 18:30:24.942   906  1353 W HtcDLNAServiceManager: Settings:Agentname: wifi_on
,11-17 18:30:24.942   906  1353 W HtcDLNAServiceManager: Settings:Agentvalue: 0
11-17 18:30:24.942   906  1353 W Settings:Agent: >> traceCallingStack()
,11-17 18:30:24.942   906  1353 W Settings:Agent: Process.myPid(): 906
,11-17 18:30:24.942   906  1353 W Settings:Agent: Process.myTid(): 1353
,11-17 18:30:24.942   906  1353 W Settings:Agent: Process.myUid(): 1000
,11-17 18:30:24.942   906  1353 W Settings:Agent: 
11-17 18:30:24.942   906  1090 D WifiService: New client listening to asynchronous messages
11-17 18:30:24.942   906  1353 D WifiService: setWifiEnabled: false pid=2790, uid=10396
11-17 18:30:24.942   906  1353 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:30:24.942   906  1353 I WifiService: isSprintWifiRestricted(): false
11-17 18:30:24.942   906  1353 I WifiService: isMdmWifiRestricted(): false
,11-17 18:30:24.942   906  1353 D WifiSettingsStore: [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
11-17 18:30:24.952   906  1353 W Settings:Agent: 
11-17 18:30:24.952   906  1353 W System.err: java.lang.Throwable: stack dump
11-17 18:30:24.952   906  1353 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:512)
11-17 18:30:24.952   906  1353 W System.err: 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
11-17 18:30:24.952   906  1353 W System.err: 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
11-17 18:30:24.952   906  1353 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
11-17 18:30:24.952   906  1353 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:6170)
11-17 18:30:24.952   906  1353 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:6264)
11-17 18:30:24.952   906  1353 W System.err: 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
11-17 18:30:24.952   906  1353 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
11-17 18:30:24.952   906  1353 W System.err: 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
11-17 18:30:24.952   906  1353 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
11-17 18:30:24.952   906  1353 W System.err: 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:30:24.952   906  1353 W System.err: 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:30:24.952   906  1353 W Settings:Agent: 
11-17 18:30:24.952   906  1353 W Settings:Agent: << traceCallingStack(): 5(ms)
11-17 18:30:24.952  2790  2790 I jxcore-log: ****TEST TOOK:  5055  ms ****
11-17 18:30:24.952  2790  2790 I jxcore-log: 
11-17 18:30:24.952  2790  2790 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:24.952  2790  2790 I jxcore-log: 
,11-17 18:30:24.972  3197  3380 W WeatherRequest: request cur loc, but there is no sys cur
11-17 18:30:24.972  3197  3380 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:30:24.992  1249  1249 D AppWidgetHostView: updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,11-17 18:30:24.992  1249  1249 I RemoteViews: com.htc.widget.weatherclock (true,33751552)
,11-17 18:30:24.992  1249  1249 I RemoteViews.Performance: com.htc.widget.weatherclock 1 6 17
,11-17 18:30:25.112   906  1103 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,11-17 18:30:25.322  3391  3391 E cutils-trace: Error opening trace file: No such file or directory (2)
,11-17 18:30:25.442  3391  3391 D CustomizationManager: ====startRecUseTime====
11-17 18:30:25.442  3391  3391 D htc.customization.log.level:  is 
,11-17 18:30:25.442  3391  3391 W CustomizationLogLevel: Level value is invalid, use default level 2
,11-17 18:30:25.472  1222  1318 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,11-17 18:30:25.472  1222  1318 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,11-17 18:30:25.532  3391  3391 D CustomizationManager:  Read ACC file spent 0.050 (s)
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__001
,11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__002
,11-17 18:30:25.532  3391  3391 D CIDMapFileReader: Parsing tag item name = HTC__031
,11-17 18:30:25.532  3391  3391 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
,11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = system
,11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = application
,11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = AudioService
,11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:30:25.532  3391  3391 I CustomizationCIDLoader: Parsing tag category name = Settings
,11-17 18:30:25.532  3391  3391 D CustomizationManager:  Read CID file spent 0.089 (s)
,11-17 18:30:25.532  3391  3391 D CustomizationManager:  All configurations done spent 0.089 (s)
11-17 18:30:25.542  3391  3391 W HtcNativeFlag: Fail to get flag string for type 'customer', use default value
11-17 18:30:25.542  3391  3391 W HtcNativeFlag: Fail to get flag for type 'customer', use default value: -1
11-17 18:30:25.542  3391  3391 W HtcNativeFlag: Fail to get flag string for type 'language', use default value
,11-17 18:30:25.542  3391  3391 W HtcNativeFlag: Fail to get flag for type 'language', use default value: -1
,11-17 18:30:25.582   906  1319 D PackageManager: deletePackageAsUser: pkg=com.example.hello, pid=3391, uid=2000 user=0
,11-17 18:30:25.602   906   933 I ActivityManager: Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,11-17 18:30:25.602   906   933 D Process : killProcessQuiet, pid=2790
,11-17 18:30:25.602   906   954 W asset   : Copying FileAsset 0x66c52f68 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,11-17 18:30:25.602   906   933 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
11-17 18:30:25.602   906   933 I ActivityManager: Killing 2790:com.example.hello/u0a396 (adj 0): stop com.example.hello
,11-17 18:30:25.602   906   933 W ActivityManager: Force removing ActivityRecord{4241de88 u0 com.example.hello/.MainActivity t2}: app died, no saved state
11-17 18:30:25.612   906   933 W ActivityManager: handleTopAppChanged(): The previous AP is died unexpectedly.
,11-17 18:30:25.662   906   954 W PackageSettings: Skipping PackageSetting{4226cd10 com.test.thalitest/10389} due to missing metadata
,11-17 18:30:25.682   906   954 I ActivityManager: Force stopping com.example.hello appid=10396 user=0: pkg removed
,11-17 18:30:25.692   906  1350 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:25.702  1532  1532 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,11-17 18:30:25.702  1111  1111 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
11-17 18:30:25.702  1111  1111 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver packageName:com.example.hello
,11-17 18:30:25.702  1111  1111 I HtcKeyguardAppUpdateMonitor: ApplicationsIntentReceiver replacing:false
11-17 18:30:25.702  1532  1532 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,11-17 18:30:25.702  1532  1532 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,11-17 18:30:25.712   906  1102 I WindowState: WIN DEATH: Window{426dc448 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:25.712   906  1090 D WifiService: Client connection lost with reason: 4
,11-17 18:30:25.712   906  1319 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:25.722  3136  3166 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
11-17 18:30:25.722  3265  3406 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:30:25.722  3265  3406 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,11-17 18:30:25.722  1321  1468 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,11-17 18:30:25.732  1201  1519 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:30:25.732   906  1247 D PMS     : acquireWL(426ab8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
11-17 18:30:25.732   906   917 D PMS     : releaseWL(426ab8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
11-17 18:30:25.732   906  1350 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3407 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,11-17 18:30:25.742  3136  3166 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:30:25.742  3136  3166 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
11-17 18:30:25.742  1321  1468 W AccTypeManager: No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,11-17 18:30:25.742  1321  1468 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:30:25.862  1249  1249 I FeedHostManager: [onResume]
,11-17 18:30:25.862  1249  1249 I FeedProviderManager: onResume
11-17 18:30:25.862   906  1348 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:25.862   906  1348 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:25.862   906  1348 I PackageManager:   Scheme: "sms"
,11-17 18:30:25.862   906  1348 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
11-17 18:30:25.872  1249  1750 I SocialFeedProvider: +onResume
11-17 18:30:25.872  1249  1750 I SocialFeedProvider: updateAccounts - Accounts is no change
11-17 18:30:25.872  1249  1750 I SocialFeedProvider: -onResume
,11-17 18:30:25.872   906  1353 D Process : killProcessQuiet, pid=3136
,11-17 18:30:25.872   906  1353 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:25.872   906  1353 I ActivityManager: Killing 3136:com.htc.contacts/u0a44 (adj 15): empty #17
,11-17 18:30:25.882  1249  1249 I ConnectivityHelper: [getCurrentConnectionType] no network connection
11-17 18:30:25.882   906   916 D ConnectivityService: getActiveNetworkInfo called by com.htc.launcher (1249/10076)
,11-17 18:30:25.892  1249  1456 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,11-17 18:30:25.892  1249  1456 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:30:25.892   906  1319 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:25.892   906  1319 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:25.892   906  1319 I PackageManager:   Scheme: "smsto"
11-17 18:30:25.892   906  1319 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,11-17 18:30:25.902  1321  1468 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:30:25.912   906  1077 V AlarmManager: sending alarm PendingIntent{426e24e0: PendingIntentRecord{427c8388 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1447781425907, Int=0
11-17 18:30:25.912   906  1350 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:25.912   906  1350 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:25.912   906  1350 I PackageManager:   Scheme: "mms"
11-17 18:30:25.912   906  1350 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,11-17 18:30:25.932   906   934 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,11-17 18:30:25.932   906  1102 I ActivityManager: Recipient 3136
,11-17 18:30:25.932   906  1104 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,11-17 18:30:25.972   906  1247 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:25.972   906  1247 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:25.972   906  1247 I PackageManager:   Scheme: "mmsto"
,11-17 18:30:25.972   906  1247 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
11-17 18:30:25.982  1235  1235 W SystemReader: Cannot find nfc_is_upgrade_to_ar890, use default value instead
,11-17 18:30:25.992   906  1102 D Process : killProcessQuiet, pid=3153
,11-17 18:30:25.992   906  1102 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:25.992   906  1102 I ActivityManager: Killing 3153:com.htc.calendar/u0a13 (adj 15): empty #17
,11-17 18:30:26.002   906  1104 I ActivityManager: Recipient 3153
,11-17 18:30:26.002   906  1316 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
11-17 18:30:26.012   906   916 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:26.012   906   916 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:26.012   906   916 I PackageManager:   Scheme: "sms"
,11-17 18:30:26.012  1188  1199 W Binder  : Caught a RuntimeException from the binder stub implementation.
11-17 18:30:26.012  1188  1199 W Binder  : java.lang.NullPointerException
11-17 18:30:26.012  1188  1199 W Binder  : 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
11-17 18:30:26.012  1188  1199 W Binder  : 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
11-17 18:30:26.012  1188  1199 W Binder  : 	at android.os.Binder.execTransact(Binder.java:412)
11-17 18:30:26.012  1188  1199 W Binder  : 	at dalvik.system.NativeStart.run(Native Method)
11-17 18:30:26.012   906   916 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
11-17 18:30:26.012   906  1352 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 2790 uid 10396
11-17 18:30:26.012   906  1352 I InputMethodManagerService: Enable input method client, pid=1249
,11-17 18:30:26.022   906  1319 I PackageManager:   Action: "android.intent.action.SENDTO"
,11-17 18:30:26.022   906  1319 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
11-17 18:30:26.032   906  1319 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:30:26.032   906  1319 I PackageManager:   Scheme: "smsto"
11-17 18:30:26.032  3407  3407 I MusicStore: Database version: 95
,11-17 18:30:26.052  3407  3407 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,11-17 18:30:26.062   906  1348 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:26.062   906  1348 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:26.062   906  1348 I PackageManager:   Scheme: "mms"
11-17 18:30:26.062   906  1348 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,11-17 18:30:26.072   906  1353 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:26.072   906  1353 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:26.072   906  1353 I PackageManager:   Scheme: "mmsto"
11-17 18:30:26.072   906  1353 I PackageManager: Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,11-17 18:30:26.092  1222  1222 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,11-17 18:30:26.102  3407  3407 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,11-17 18:30:26.112   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:30:26.112  3407  3407 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
11-17 18:30:26.112   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:30:26.162   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:30:26.162   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:30:26.172  3407  3407 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,11-17 18:30:26.172   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,11-17 18:30:26.172  3407  3407 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
11-17 18:30:26.172   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
,11-17 18:30:26.182   906  1316 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3407, uid=10154, userID:0
,11-17 18:30:26.202   906  1320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:30:26.202   906  1320 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:30:26.202   906  1320 D WifiDisplayAdapter:     GroupId: 
11-17 18:30:26.202   906  1320 D WifiDisplayAdapter:     Passphrase: 
11-17 18:30:26.202   906  1320 D WifiDisplayAdapter:     SessionId: 0
11-17 18:30:26.202   906  1320 D WifiDisplayAdapter:     IP Address: }
,11-17 18:30:26.202   906  1317 D MediaRouterService: Client com.google.android.music (pid 3407): Registered
,11-17 18:30:26.212  3407  3407 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
11-17 18:30:26.212   906   916 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
11-17 18:30:26.212   906   916 D WifiDisplayAdapter:     Client/Owner: Client
11-17 18:30:26.212   906   916 D WifiDisplayAdapter:     GroupId: 
11-17 18:30:26.212   906   916 D WifiDisplayAdapter:     Passphrase: 
11-17 18:30:26.212   906   916 D WifiDisplayAdapter:     SessionId: 0
11-17 18:30:26.212   906   916 D WifiDisplayAdapter:     IP Address: }
,11-17 18:30:26.222  3212  3212 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
11-17 18:30:26.222   906  1352 D ConnectivityService: getActiveNetworkInfo called by com.google.android.music (3407/10154)
11-17 18:30:26.232  3212  3429 I DFPI.ApkInstallService: onHandleIntent
,11-17 18:30:26.232  3212  3429 I DFPI.ApkInstallService: Media Scan Finished Case 
11-17 18:30:26.232  3212  3429 D DFPI.ApkInstallService: check CID = HTC__032
,11-17 18:30:26.232  3212  3429 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,11-17 18:30:26.232   906   906 I SensorManager: mEventCount = 300
11-17 18:30:26.232   906  1317 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
11-17 18:30:26.232   906   916 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:26.242  3407  3407 D MediaRouter: getSelectedRoute
11-17 18:30:26.242   906  1351 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
11-17 18:30:26.252   906  1319 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3407, uid=10154, userID:0
11-17 18:30:26.252   906  1351 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:26.262   906  1351 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3432 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,11-17 18:30:26.302   906  1320 I ActivityManager: Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,11-17 18:30:26.312   906  1319 D ConnectivityService: getActiveNetworkInfo called by com.htc.musicenhancer (3432/10053)
,11-17 18:30:26.312   906   906 W PackageManager: Unable to load service info ResolveInfo{4267d320 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:30:26.312   906   906 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:30:26.312   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:733)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:30:26.312   906   906 W PackageManager: 	at android.os.Looper.loop(Looper.java:157)
11-17 18:30:26.312   906   906 W PackageManager: 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
11-17 18:30:26.312   906   906 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:1591)
11-17 18:30:26.312   906   906 W PackageManager: 	at java.lang.reflect.Method.invokeNative(Native Method)
11-17 18:30:26.312   906   906 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:515)
11-17 18:30:26.312   906   906 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
11-17 18:30:26.312   906   906 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
11-17 18:30:26.312   906   906 W PackageManager: 	at dalvik.system.NativeStart.main(Native Method)
,11-17 18:30:26.312   353   802 E cutils  : Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
11-17 18:30:26.312   353   802 W Vold    : Returning OperationFailed - no handler for errno 30
11-17 18:30:26.322  3432  3449 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,11-17 18:30:26.532   906   906 D RemoteDisplayProvider: Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,11-17 18:30:26.532   906   906 D RemoteDisplayProvider: start
,11-17 18:30:26.552   906   934 D ConnectivityService: getActiveNetworkInfo called by  (906/1000)
,11-17 18:30:26.552   906   934 D PMS     : acquireWL(4275c0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,11-17 18:30:26.552   906   934 W AtomicFile: Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
11-17 18:30:26.552   906   934 D PMS     : releaseWL(4275c0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
11-17 18:30:26.552   906   934 W AppWidgetServiceImpl: Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,11-17 18:30:26.732  1473  2111 I HtcModeClient: handler message = 4011
,11-17 18:30:26.732  1473  2111 E HtcModeClient: Check connection and retry 5 times.
,11-17 18:30:27.222  3265  3406 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
11-17 18:30:27.222  3265  3406 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@41bb67e8 +
11-17 18:30:27.222  3265  3406 I Prism.WidgetManager: onLoadItems() +
,11-17 18:30:27.282   906  1316 I ActivityManager: Resuming delayed broadcast
,11-17 18:30:27.292   906  1104 D Process : killProcessQuiet, pid=2878
,11-17 18:30:27.292   906  1104 D Process : com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
11-17 18:30:27.292   906  1316 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3451 uid=10081 gids={50081, 5001, 1028, 1015}
11-17 18:30:27.292   906  1104 I ActivityManager: Killing 2878:com.android.settings:remote/1000 (adj 15): empty #17
,11-17 18:30:27.302   906  1350 I ActivityManager: Recipient 2878
,11-17 18:30:27.302   906  1320 I DisplayManagerService: stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
```
