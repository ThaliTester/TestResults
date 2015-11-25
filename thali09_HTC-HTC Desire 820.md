#### Test 503880196dc97cd_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/DeviceManagement( 2687): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/DeviceManagement( 2687): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 2687): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2687): Perf: Scan enabled apps - complete: 1009 ms
I/DeviceManagement( 2687): Perf: *** Enabled app cache update - complete: 1010 ms
I/DeviceManagement( 2687): Perf: *** Config cache update - start...
I/DeviceManagement( 2687): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2687): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2687): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2687): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2687): AlarmController: Scheduling TTL alarm for: 2015.11.25 at 17:04:57.514 CET (due to: com.htc.launcher)
--------- beginning of /dev/log/system
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2687, uid=10098, userID:0
I/DeviceManagement( 2687): Perf: *** Config cache update - complete: 22 ms
I/DeviceManagement( 2687): Perf: *** Cache update - complete: 1035 ms
I/DeviceManagement( 2687): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41b04378]
I/DeviceManagement( 2687): WorkflowService: Stopping workflow service
I/ActivityManager(  906): Resuming delayed broadcast
I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2704, uid=10107, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=2367
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2367:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2367
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2751 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/htcbackup-core( 2751): ModelRegistry: Loading model meta data from resources...
W/ContextImpl( 2751): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
W/ContextImpl( 2751): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
I/Icing   ( 1956): Internal init done: storage state 0
I/Icing   ( 1956): Post-init done
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews( 1106): com.htc.backup (true,33751552)
W/ContextImpl( 2751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41b2c400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DeviceManagement( 2687): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 2687): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.inputdevices, com.htc.android.htcloglevel, com.htc.guide, com.htc.usage, com.htc.autobot.cargps.provider, com.android.providers.settings, com.htc.drive.activator, com.qualcomm.timeservice, com.htc.lockscreen, com.htc.smartdim, com.android.keychain, com.android.CSDFunctionG, com.qualcomm.privinit, com.htc.htcpowermanager, com.htc.mirrorlinkserver, com.android.location.fused, com.android.settings, com.htc.home.personalize, android, com.htc.backup, com.htc.cirmodule, com.htc.checkinprovider, com.htc.feedback, com.htc.android.htcsetupwizard, com.htc.backupreset]
I/RemoteViews.Performance( 1106): com.htc.backup 1 8 5 15
I/DeviceManagement( 2687): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/ActivityManager(  906): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/DeviceManagement( 2687): WorkflowService: Starting workflow service
I/DeviceManagement( 2687): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e05420] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2687): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2687): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41b56c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DeviceManagement( 2687): SessionStateController: Checking invariants...
I/RemoteViews( 1106): com.htc.backup (true,33751552)
E/cutils-trace( 2747): Error opening trace file: No such file or directory (2)
I/RemoteViews.Performance( 1106): com.htc.backup 1 5 4 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 2 1 1 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 1 2 1 4
I/RemoteViews.Performance( 1106): com.htc.backup 2 8 21 21
I/DeviceManagement( 2687): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2687): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e05420]
I/DeviceManagement( 2687): WorkflowService: Stopping workflow service
D/PMS     (  906): releaseWL(4284a650): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/htcbackup-core( 2751): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2786 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
V/AlarmManager(  906): sending alarm PendingIntent{42423b50: PendingIntentRecord{42484bc0 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=13, w=1440901414353, Int=604800000
D/CustomizationManager( 2747): ====startRecUseTime====
D/htc.customization.log.level( 2747):  is 
W/CustomizationLogLevel( 2747): Level value is invalid, use default level 2
W/dalvikvm( 2751): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 2 2 15
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews( 1106): com.htc.backup (true,33751552)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews.Performance( 1106): com.htc.backup 1 3 0 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 2 1 1 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 2 2 0 4
I/RemoteViews.Performance( 1106): com.htc.backup 3 16 21
D/UPolicy ( 2751): IUserBehaviorLoggingService reference is gotten !
D/Process (  906): killProcessQuiet, pid=2381
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2381:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2381
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 2747):  Read ACC file spent 0.078 (s)
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2747): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2747): Parsing tag category name = system
I/CustomizationCIDLoader( 2747): Parsing tag category name = application
I/CustomizationCIDLoader( 2747): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2747): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2747): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2747): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2747): Parsing tag category name = Settings
D/CustomizationManager( 2747):  Read CID file spent 0.124 (s)
D/CustomizationManager( 2747):  All configurations done spent 0.124 (s)
W/HtcNativeFlag( 2747): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2747): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2747): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2747): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2747
D/PMS     (  906): acquireHCC(423d0158): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
W/asset   (  906): Copying FileAsset 0x635f7658 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1111554160
W/dalvikvm( 2786): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2786): VFY: unable to resolve instance field 46
D/PMS     (  906): acquireHCC(422ec8b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
D/PMS     (  906): acquireWL(424aa770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
W/dalvikvm( 2786): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 2786): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c39d30
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
I/Babel   ( 2786): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 2786): MmsConfig.loadMmsSettings
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2812 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
D/MmsCustomizationProvider( 2487): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2786, uid=10111, userID:0
D/MmsCustomizationProvider( 2487): query uri: content://htc-mms-customization/mms-ua/ua_profile
W/asset   ( 2812): Copying FileAsset 0x5c770520 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1246): [trimMemory] 20
W/Settings( 2786): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 2786): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 2786): MmsConfig.loadFromDatabase
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2786, uid=10111, userID:0
E/Babel   ( 2786): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 2786): MmsConfig.loadFromResources
E/Babel   ( 2786): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 2786): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
V/WebViewChromiumFactoryProvider( 2812): Binding Chromium to main looper Looper (main, tid 1) {41adad98}
I/LibraryLoader( 2812): Expected native library version number "",actual native library version number ""
I/chromium( 2812): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2812): Initializing chromium process, renderers=0
I/ProviderInstaller( 2786): Installed default security provider GmsCore_OpenSSL
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2786, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2786, uid=10111, userID:0
V/Babel   ( 2786): babel boot account: thalitester@gmail.com
V/Babel   ( 2786): babel boot account: SMS
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e0af98:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 2812): 1101989776: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): acquireWL(425346d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  906): acquireWL(423ab040): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  906): releaseWL(423ab040): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2812): Local Branch: 
I/Adreno-EGL( 2812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2812):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  906): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2839 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2394
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2394:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
V/AlarmManager(  906): sending alarm PendingIntent{423e4500: PendingIntentRecord{423250c0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=45421, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42579438: PendingIntentRecord{425397d0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=45426, Int=0
W/chromium( 2812): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager(  906): Recipient 2394
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 2812): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2812): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2812): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2812): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2812): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2812): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2812): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2812): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2812): CordovaWebView is running on device made by: HTC
I/ActivityManager(  906): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2862 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  906): killProcessQuiet, pid=2419
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2419:com.htc.video/u0a57 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2419
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ResetNotifyBootCompleteReceiver( 1215): Receive bootcomplete intent
W/ContextImpl( 1215): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2882 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/HtcCupdXmlParser( 2862): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 2862): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
W/AwContents( 2812): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1246
I/InputMethodManagerService(  906): Enable input method client, pid=2812
W/ResourceType( 2812): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2812): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b21b18, mServedView=org.apache.cordova.engine.SystemWebView{41ae7ab0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 2812): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +483ms
W/XT9_C   ( 1184): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1184): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(424aa770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/AppTag  ( 2882): getInstance(Context context)
D/AppTag  ( 2882): getInstance(Context context)
D/AppTag  ( 2882): onCreate()
D/QXDM2SD:HtcNative( 1215): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2902 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2436
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2436:com.htc.lmw/u0a60 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2436
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcCupdXmlParser( 2862): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
E/AndroidProtocolHandler( 2812): Unable to open asset URL: file:///android_asset/www/jxcore.js
V/Settings:HtcSettingsApplication( 2902): [2902/2902] onCreate()
W/ContextImpl( 2902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/chromium( 2812): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2918 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2505
I/ActivityManager(  906): Killing 2505:com.htc.reportagent/u0a66 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/AlarmManager(  906): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  906): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  906): [AlarmQueuing] init alarm queuing list
I/ActivityManager(  906): Recipient 2505
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/JsMessageQueue( 2812): Set native->JS mode to OnlineEventsBridgeMode
D/Process (  906): killProcessQuiet, pid=2554
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2930 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  906): Killing 2554:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2554
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 2918): -onCreate()
D/jxcore_app_log( 2812): JniHelper::setJavaVM(0x415ab048), pthread_self() = 1657831848
D/JX-Cordova( 2812): jxcore cordova android initializing
W/jxcore-log( 2812): Initializing JXcore engine
W/jxcore-log( 2812): JXcore engine is ready
W/jxcore-log( 2812): Starting JXcore engine
V/Settings:HtcSettingsApplication( 2918): [2918/2918] onCreate()
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@427c4d38
W/ContextImpl( 2918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42631410
D/TetherSettings( 2918): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2918): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2918): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2918): Cust_ConnectToPC   : spcsc>false
D/        ( 2918): Cust_ConnectToPC   : IPT>true
D/        ( 2918): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Process (  906): killProcessQuiet, pid=2567
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/TetherSettings( 2918): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2918): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2918): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2918): Cust_ConnectToPC   : spcsc>false
D/        ( 2918): Cust_ConnectToPC   : IPT>true
D/        ( 2918): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2918): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2918): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2918): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2918): setISNotification
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@425daba8
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  906): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  906): Killing 2567:com.htc.showme/u0a83 (adj 15): empty #17
D/SmartNS_Utility( 2918): usb_cable_connect = 1
D/SmartNS_Utility( 2918): usb_denied = 0
I/SmartNS_PSService( 2918): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 2918): usb_cable_connect = 1
D/SmartNS_Utility( 2918): usb_denied = 0
I/SmartNS_PSService( 2918): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  906): Recipient 2567
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (2918/1000)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (2918/1000)
D/Process (  906): killProcessQuiet, pid=2581
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2581:com.htc.updater/u0a85 (adj 15): empty #17
I/RemoteViews( 1106): com.android.settings (true,33751552)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41b32320 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1106): com.android.settings 1 7 1 10
I/RemoteViews( 1106): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1106): com.android.settings 1 0 10
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4239a8c0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4239a8c0, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c7700
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@4215a380
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@4239a8c0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4239a8c0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
I/ActivityManager(  906): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2946 uid=9987 gids={49987}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42598fe8 u0 ReceiverList{4242a660 906 system/1000/u0 local:42157dc8}}
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = CM36282 Proximity sensor
D/NfcUiccLockService( 2946): -- To check whether previous opened channel needed to be closed ...
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2581
,I/ActivityManager(  906): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2960 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
D/Process (  906): killProcessQuiet, pid=2610
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2610:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 3
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4239a8c0, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c7700
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@4215a380
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@4239a8c0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): Recipient 2610
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 2812): Platform android
W/jxcore-log( 2812): 
,W/jxcore-log( 2812): Process ARCH arm
W/jxcore-log( 2812): 
I/ActivityManager(  906): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2972 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2461
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2461:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2461
,I/jxcore-log( 2812): JXcore Cordova bridge is ready!
I/jxcore-log( 2812): 
,W/jxcore-log( 2812): JXcore engine is started
,E/jxcore-log( 2812): >> HTC-HTC Desire 820
E/jxcore-log( 2812): 
,I/jxcore-log( 2812): Total memory 1964650496
I/jxcore-log( 2812): 
,I/jxcore-log( 2812): Free memory 708001792
I/jxcore-log( 2812): 
I/jxcore-log( 2812): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2812): 
,I/jxcore-log( 2812): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2812): 
,I/jxcore-log( 2812): userPath [ 'www' ]
I/jxcore-log( 2812): 
,I/jxcore-log( 2812): Size 720 1184
I/jxcore-log( 2812): 
,I/jxcore-log( 2812): Screen Brightness 142
I/jxcore-log( 2812): 
,E/jxcore-log( 2812): Dummy Error Log.
E/jxcore-log( 2812): 
,E/YouTube ( 2972): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2972): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2972): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2972): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (2972/10168)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2972): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2972): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2972): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2972): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.youtube (pid 2972): Registered
,I/MediaRouter( 2972): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.youtube (2972/10168)
D/YouTube ( 2972): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2972): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448460676&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 2972): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2972): [NET] getaddrinfo-,err=8
D/libc    ( 2972): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2972): [NET] getaddrinfo-, 1
D/libc    ( 2972): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 2972): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2972): Error sending ping
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 2972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2972): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,D/MediaRouter( 2972): getSelectedRoute
,D/YouTube ( 2972): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2972): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (2972/10168)
,D/Process (  906): killProcessQuiet, pid=2640
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2640:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/YouTube ( 2972): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2972): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2972): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/jxcore-log( 2812): getBuffer is called!!!!
I/jxcore-log( 2812): 
I/ActivityManager(  906): Recipient 2640
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1956): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1956): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1956): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1956): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1956): Beginning GMS chimera module scan
,W/asset   ( 1956): Copying FileAsset 0x658739a8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1956): Beginning module configuration check
,D/ChimeraCfgMgr( 1956): Module APKs unchanged, check complete,
I/ActivityManager(  906): Resuming delayed broadcast
E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
D/PMS     (  906): acquireWL(41c72428): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1956): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1956): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  906): releaseHCC(423d0158): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(422ec8b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/PMS     (  906): acquireWL(42669860): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41c72428): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1956): COMPAT: Multi user not supported
,D/PMS     (  906): acquireWL(4243b7b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1338): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1448458931419 min interval config: 0 actual interval: 1745184
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,I/GCoreUlr( 1956): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1196): DispatchingService.onCreate()
,I/CheckinService( 1956): Disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 1956): onCreate
,D/SystemUpdateService( 1956): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,V/AuthZen ( 1956): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1956): cancelUpdate (empty URL)
,I/SystemUpdateService( 1956): active receiver: disabled
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/PMS     (  906): acquireWL(42591cd8): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/CheckinService( 1956): Checking schedule, now: 1448460676681 next: 1448981868386
,I/CheckinService( 1956): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1956, uid=10029, userID:0
,D/AuthZenEventHandler( 1956): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  906): acquireWL(42595790): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  906): releaseWL(42591cd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/PMS     (  906): releaseWL(42669860): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,D/SystemUpdateService( 1956): onDestroy
D/PMS     (  906): releaseWL(4243b7b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1196): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1956): Fetching signing key...
,I/AuthZen ( 1956): Signing key fetched successfully!
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1196, uid=10029, userID:0
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 1956): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1956): Clearing transaction cache
,I/GCoreUlr( 1196): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1196): Unbound from all location providers
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(425a9a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42595790): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/PMS     (  906): releaseWL(425a9a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42669f18): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1956 10029 null
,D/PMS     (  906): acquireWL(42666c68): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1196): DispatchingService.onDestroy()
,I/GCoreUlr( 1196): Stopping handler for UlrDispSvcFast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
D/PMS     (  906): acquireWL(426508e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/PMS     (  906): releaseWL(42669f18): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  906): releaseWL(42666c68): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426508e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,I/GCoreUlr( 1196): Unbound from all location providers
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,W/Auth    ( 1338): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): acquireWL(426875f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1338 10029 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  906): releaseWL(426875f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1338): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3060 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42656e20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42656e20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3060, uid=10074, userID:0
,D/Finsky  ( 3060): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3060/10074)
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3060/10074)
,D/Finsky  ( 3060): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3060): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3060): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3060): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3060, uid=10074, userID:0
,D/Volley  ( 3060): [286] DiskBasedCache.clear: Cache cleared.
,D/Process (  906): killProcessQuiet, pid=2660
D/Ads     ( 3060): Skipping gmscore version check
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Volley  ( 3060): [279] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  906): Killing 2660:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2660
,D/Finsky  ( 3060): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3060): [1] Libraries$2.run: Finished loading 1 libraries.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3060): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1306): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1306): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
,D/Finsky  ( 3060): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/TetherSettings( 2918): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2918): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2918): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2918): Cust_ConnectToPC   : spcsc>false
D/        ( 2918): Cust_ConnectToPC   : IPT>true
D/        ( 2918): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2918): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2918): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2918): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 2918): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 2918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 2918): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2918):  defaultType:0
,I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3099 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3099): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3099): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3099): Loading: swewebviewchromium
,I/LibraryLoader( 3099): Time to load native libraries: 34 ms (timestamps 7606-7640)
,I/LibraryLoader( 3099): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3099): Initializing chromium process, renderers=9
I/LibraryLoader( 3099): Expected native library version number "",actual native library version number ""
I/chromium( 3099): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/PMS     (  906): releaseWL(425346d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/chromium( 3099): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3099): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3099): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3099): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3099): Local Branch: 
I/Adreno-EGL( 3099): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3099): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3099):                  aa63bbd948f41d15fc72f585e
,D/Process (  906): killProcessQuiet, pid=2672
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 2672:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1276): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1484): SIM state: ABSENT
I/SIMStateChangeReceiver( 1484): phoneType = 0
,I/SIMStateChangeReceiver( 1484): remove notification
I/ActivityManager(  906): Recipient 2672
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3138 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3150 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2704
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2704:com.google.android.gm/u0a107 (adj 15): empty #17
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 4 times.
,W/SystemReader( 2487): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2487): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2487): onReceive()
D/ExchangePolicystatus( 2487): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2487): onReceive(): else
,D/Process (  906): killProcessQuiet, pid=2751
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1215): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  906): Killing 2751:com.htc.backup/1000 (adj 15): empty #17
,W/WeatherUtility( 1106): can't get weather sync account
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2704
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3167 uid=10041 gids={50041}
,W/WeatherRequest( 1106): request cur loc, but there is no sys cur
,D/AccTypeManager( 3150): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  906): Recipient 2751
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3150): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3150): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  906): killProcessQuiet, pid=2687
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3183 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 2687:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/ExternalAccountType( 3150): Unsupported attribute readOnly
,D/SMSBackup( 3183): Got a database change event
,D/Process (  906): killProcessQuiet, pid=2786
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3195 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 2786:com.google.android.talk/u0a111 (adj 15): empty #17
D/AccTypeManager( 3150): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3150): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3150): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2687
,E/ExternalAccountType( 3150): Unsupported attribute readOnly
,D/CalendarApplication( 3195): onCreate
D/ProviderChangeReceiver( 3195): ---------------------------------------------------
,D/ProviderChangeReceiver( 3195): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3195): start to updateAlertNotification!
,W/ContextImpl( 2902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3195): No fired or scheduled alerts
,D/HtcAlertUtils( 3195): -- cancelReminderNotification --
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3210 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/HtcAlertUtils( 3195): broadcastExistReminder!
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  906): killProcessQuiet, pid=2839
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2839:com.htc.backupreset/1000 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2786
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2839
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3224 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3210): can't get weather sync account
,W/WeatherRequest( 3210): request cur loc, but there is no sys cur
,W/Settings( 3210): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3224): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3224): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3224): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Resuming delayed broadcast
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 12 17
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3239 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2862
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2862:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2862
,D/PMS     (  906): acquireWL(424d06c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3239 10071 null
,D/PMS     (  906): acquireWL(424cf7a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3239 10071 null
,D/PMS     (  906): releaseWL(424d06c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3239): update TASK shortcut>
,I/TodoTaskNotifyService( 3239): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): releaseWL(424cf7a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3254 uid=10082 gids={50082, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=2882
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/NotifyReceiver( 3239): stopSelfResult true
I/ActivityManager(  906): Killing 2882:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2882
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3266 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3278 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  906): killProcessQuiet, pid=2946
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=2930
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2946:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  906): Killing 2930:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 2946
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2930
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3278): create image Cache, size: 31457280.
I/ImageRamCache( 3278): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3278): create image Cache, size: 12582912.
,I/FeedSettings( 3278): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3278): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3278): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3278): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3278): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3278): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3278): [custom highlight] onReceive
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3278): [custom highlight] onHandleIntent
D/NewsDB  ( 3278): set custom highlight []
,D/CustomHighlightService( 3278): [custom highlight] set tags 
,D/SMSBackup( 3183): Got a database change event
,I/ActivityManager(  906): Resuming delayed broadcast
,D/MessagingShortcutReceiver( 2487): keep hiding shortcut bubble
D/MessagingShortcut( 2487): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2487): After query: 0
D/MessagingShortcut( 2487): mPresentUnreadCount: -1
D/MessagingShortcut( 2487): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2487): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderNotification, total:0
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3239): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1215): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  906): killProcessQuiet, pid=2960
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2960:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2960
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3294 uid=10091 gids={50091, 3003, 5012}
,D/MessagingNotification( 2487): New incoming message, can't cancel notification now
,D/MessagingNotification( 2487): newMsgCnt: 0, false
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023036
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023437
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023555
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023558
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023560
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027563
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3308 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  906): sending alarm PendingIntent{41f3aa68: PendingIntentRecord{425d2c80 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20608, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{4217afc0: PendingIntentRecord{41dbe3f8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=45383, Int=259200000
,V/AlarmManager(  906): sending alarm PendingIntent{41d9b7c0: PendingIntentRecord{4247cd68 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49753, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41c4a060: PendingIntentRecord{4231a748 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448449200001, Int=86400000
,D/MdScBoot( 3294): [8c0.1.] 30@-151052 -> 40@-151119
,D/Process (  906): killProcessQuiet, pid=2972
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2972:com.google.android.youtube/u0a168 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3060
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3060:com.android.vending/u0a74 (adj 15): empty #17
,D/WearableService( 1196): callingUid 10029, callindPid: 1196
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,E/MDM     ( 1196): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1196): No location to return for getLastLocation()
,W/FusedLocationProvider( 1338): location=null
D/PMS     (  906): acquireWL(42696760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42696760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023036
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023437
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023555
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023558
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023560
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027563
I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1338): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1338): Proximity feature is not enabled.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Recipient 3060
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2972
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 2972): Died!
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42784878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/PMS     (  906): releaseWL(42784878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/MDM     ( 1196): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1196): No location to return for getLastLocation()
,D/PMS     (  906): acquireWL(427fee58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,W/FusedLocationProvider( 1338): location=null
D/PMS     (  906): releaseWL(427fee58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023036
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023437
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023555
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023558
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023560
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027563
I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1338): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1338): Proximity feature is not enabled.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/PMS     (  906): acquireWL(426839a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023036
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023437
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023555
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023558
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023560
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027563
,D/PMS     (  906): releaseWL(426839a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2167): [MTP][MtpReceiver][onReceive]+
,D/MtpReceiver( 2167): [MTP][handleMessage][startService]
D/MtpReceiver( 2167): [MTP][MtpReceiver][onReceive]1-,
D/MtpReceiver( 2167): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2167): [MTP][handleMessage]-
D/PMS     (  906): acquireWL(42658340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1338/10029)
,D/MtpService( 2167): [MTP] startForeground
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3333 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1106): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1106): com.android.providers.media 1 1 10
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023036
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023437
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023555
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023558
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023560
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027563
I/RemoteViews( 1106): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1106): com.android.providers.media 1 2 15
,D/MtpService( 2167): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2167): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  906): acquireWL(4238c0f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1956 10029 null
,D/MtpService( 2167): [isMtpConnected] connected: true
D/PMS     (  906): releaseWL(42658340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=2918
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2918:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2918
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3333): Loading default preferences
,I/iu.UploadsManager( 1956): End new media; added: 0, uploading: 0, time: 63 ms
,W/Resources( 3333): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  906): releaseWL(4238c0f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 3333): Overriding preferences with custom values
,D/SyncApplication( 3333): Updating preferences succeeded
,E/SyncApplication( 3333): Application created.
D/VolumeInfo( 3333): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3333): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3333): Found 0 mount point(s)
,V/VolumeInfo( 3333): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3333): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3333): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3333): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3333): getNewCalendarAuthority()...
,D/SyncApplication( 3333): enableAppOperation()+
,D/SyncApplication( 3333): enableAppOperation()-
,D/HTCUtilities( 3333): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3333, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3333, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3333): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3333): isNeorSinged() return false
,D/CDMountReceiver( 3333): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3333): USB connected to PC
,D/FOTAReceiver( 3333): onReceive() enter 
,D/FOTAReceiver( 3333): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3353 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3099
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3099:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3099
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3353): -onCreate(),
,V/Settings:HtcSettingsApplication( 3353): [3353/3353] onCreate()
,D/TetherSettings( 3353): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3353): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3353): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3353): Cust_ConnectToPC   : spcsc>false
D/        ( 3353): Cust_ConnectToPC   : IPT>true
,D/        ( 3353): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3353): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3353): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3353): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3353): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3353): Cust_ConnectToPC   : spcsc>false
D/        ( 3353): Cust_ConnectToPC   : IPT>true
D/        ( 3353): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3353): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3353): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3353): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3353): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3353): usb_cable_connect = 1
,D/SmartNS_Utility( 3353): usb_denied = 0
I/SmartNS_NSReceiver( 3353): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3353): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3353): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3353): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3353): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3353):  defaultType:0
I/SmartNS_PSService( 3353): fail notificaiton:false
,D/SmartNS_Utility( 3353): usb_cable_connect = 1
D/SmartNS_Utility( 3353): usb_denied = 0
,I/SmartNS_PSService( 3353): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3353/1000)
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3353): usb_cable_connect = 1
D/SmartNS_Utility( 3353): usb_denied = 0
,I/SmartNS_PSService( 3353): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews( 1106): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1106): com.android.settings 0 1 10
I/ActivityManager(  906): Resuming delayed broadcast
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 3353): usb_cable_connect = 1
,D/SmartNS_Utility( 3353): usb_denied = 0
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,W/WeatherUtility( 3210): can't get weather sync account
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3353/1000)
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1106): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1106): com.android.settings 1 1 10
I/SmartNS_PSService( 3353): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3353): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  906): Resuming delayed broadcast
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
W/WeatherRequest( 3210): request cur loc, but there is no sys cur
,W/Settings( 3210): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/RemoteViews( 1246): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1246): com.google.android.googlequicksearchbox 1 1 5
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3370 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 8 17
,W/ContextImpl( 3370): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3370): call getInstance()
I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3370): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3138
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3138:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  906): acquireWL(427dfab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3370 1000 null
,W/WeatherUtility( 1106): can't get weather sync account
,I/ActivityManager(  906): Recipient 3138
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WeatherUtility( 1306): Weather sync is On
D/WSP     ( 1306): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3210): can't get weather sync account
I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3387 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3210): request cur loc, but there is no sys cur
,W/Settings( 3210): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1355
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  906): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/WifiManager( 2812): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 914
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552),
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: false pid=2812, uid=10396
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 4(ms)
I/jxcore-log( 2812): ****TEST TOOK:  5043  ms ****
I/jxcore-log( 2812): 
I/jxcore-log( 2812): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2812): 
,I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 10 17
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/cutils-trace( 3406): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3406): ====startRecUseTime====
D/htc.customization.log.level( 3406):  is 
,W/CustomizationLogLevel( 3406): Level value is invalid, use default level 2
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3150
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3415 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3150:com.htc.contacts/u0a44 (adj 15): empty #17
,D/CustomizationManager( 3406):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3406): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 3406): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3406): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3406): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3406): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3406): Parsing tag category name = system
,I/CustomizationCIDLoader( 3406): Parsing tag category name = application
I/CustomizationCIDLoader( 3406): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3406): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3406): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3406): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3406): Parsing tag category name = Settings
D/CustomizationManager( 3406):  Read CID file spent 0.117 (s)
,D/CustomizationManager( 3406):  All configurations done spent 0.117 (s)
I/ActivityManager(  906): Recipient 3150
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/HtcNativeFlag( 3406): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3406): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3406): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3406): Fail to get flag for type 'language', use default value: -1
,I/MusicStore( 3415): Database version: 95
,W/ContextImpl( 3415): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3415): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3406, uid=2000 user=0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3415): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,W/asset   (  906): Copying FileAsset 0x63255f58 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  906): killProcessQuiet, pid=2812
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 2812:com.example.hello/u0a396 (adj 0): stop com.example.hello
,W/ActivityManager(  906): Force removing ActivityRecord{4244a5f0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,W/PackageSettings(  906): Skipping PackageSetting{42256498 com.test.thalitest/10389} due to missing metadata
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  906): WIN DEATH: Window{4233af70 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  906): Client connection lost with reason: 4
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3415): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
V/AlarmManager(  906): sending alarm PendingIntent{41fe3e60: PendingIntentRecord{42824ad8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448460681630, Int=0
I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/FeedHostManager( 1246): [onResume]
,I/FeedProviderManager( 1246): onResume
W/ContextImpl( 3415): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/SocialFeedProvider( 1246): +onResume
I/SocialFeedProvider( 1246): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1246): -onResume
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
,I/ConnectivityHelper( 1246): [getCurrentConnectionType] no network connection
D/PMS     (  906): acquireWL(429504b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1246/10076)
D/PMS     (  906): releaseWL(429504b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3415, uid=10154, userID:0
,D/Process (  906): killProcessQuiet, pid=3195
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3195:com.htc.calendar/u0a13 (adj 15): empty #17
,W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  906): Recipient 3195
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC <<
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/MediaRouterService(  906): Client com.google.android.music (pid 3415): Registered
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/MediaRouter( 3415): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/DFPI.PIReciver( 3224): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3415/10154)
I/DFPI.ApkInstallService( 3224): onHandleIntent
I/DFPI.ApkInstallService( 3224): Media Scan Finished Case 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3224): check CID = HTC__032
,I/DFPI.ApkInstallService( 3224): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/MediaRouter( 3415): getSelectedRoute
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3415, uid=10154, userID:0
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3441 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3441/10053)
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 2812 uid 10396
,W/Binder  ( 1184): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1184): java.lang.NullPointerException
W/Binder  ( 1184): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1184): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1184): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1184): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  906): Enable input method client, pid=1246
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
,E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3441): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 3370): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteDatabase( 3370): Error inserting ...
E/SQLiteDatabase( 3370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3370): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3370): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3370): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3370): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3370): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3370): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3370): (3850) statement aborts at 34: [SELECT * FROM smartsync_golden_wed ORDER BY date] disk I/O error
E/SQLiteDBG( 3370): func: nativeExecuteForCursorWindow errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x620e77b0
E/SQLiteQuery( 3370): exception: disk I/O error (code 3850); query: SELECT * FROM smartsync_golden_wed ORDER BY date
D/PMS     (  906): releaseWL(427dfab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/PackageManager(  906): Unable to load service info ResolveInfo{42630740 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(427bde68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(427bde68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  906): start
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SensorManager(  906): mEventCount = 300
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3462 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2902
,I/ActivityManager(  906): Killing 2902:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2902
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 5 times.
,I/SoundPicker( 3462): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3462): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3462): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3462): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3462): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3462): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3462): MODE_GSM access default DB
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3462): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3462): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3462): MODE_GSM access default DB
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3462): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3462): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3462): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3462): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3462): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3462): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3462): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac

```
