#### Test 503880196b4ec73_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
,I/htcbackup-core( 2745): ModelRegistry: Loading model meta data from resources...
W/ContextImpl( 2745): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
--------- beginning of /dev/log/system
W/ContextImpl( 2745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 2696): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 2696): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.htcpowermanager, com.android.location.fused, com.htc.guide, com.htc.usage, com.android.inputdevices, com.htc.backupreset, com.htc.android.htcsetupwizard, com.htc.backup, com.android.CSDFunctionG, com.htc.smartdim, com.android.keychain, com.htc.feedback, com.htc.home.personalize, com.htc.mirrorlinkserver, com.android.settings, com.htc.android.htcloglevel, android, com.htc.lockscreen, com.htc.cirmodule, com.android.providers.settings, com.htc.drive.activator, com.qualcomm.privinit, com.htc.checkinprovider, com.htc.autobot.cargps.provider, com.qualcomm.timeservice]
I/DeviceManagement( 2696): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
W/ContextImpl( 2745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b8bb90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1109): com.htc.backup 2 9 6 15
I/RemoteViews( 1109): com.htc.backup (true,33751552)
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b8f4f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1109): com.htc.backup 1 4 8 4
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1109): com.htc.backup 1 1 1 4
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1109): com.htc.backup 1 1 3 4
I/RemoteViews.Performance( 1109): com.htc.backup 0 10 25 21
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
I/DeviceManagement( 2696): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/DeviceManagement( 2696): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
E/cutils-trace( 2766): Error opening trace file: No such file or directory (2)
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2696): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2696): Perf: Scan enabled apps - complete: 1097 ms
I/DeviceManagement( 2696): Perf: *** Enabled app cache update - complete: 1099 ms
I/DeviceManagement( 2696): Perf: *** Config cache update - start...
I/DeviceManagement( 2696): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2696): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2696): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2696): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2696): AlarmController: Scheduling TTL alarm for: 2015.11.24 at 10:16:08.212 CET (due to: com.htc.launcher)
I/DeviceManagement( 2696): Perf: *** Config cache update - complete: 21 ms
I/DeviceManagement( 2696): Perf: *** Cache update - complete: 1122 ms
I/DeviceManagement( 2696): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41b384d0]
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2696, uid=10098, userID:0
I/DeviceManagement( 2696): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e384f8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2696): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2696): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2696): SessionStateController: Checking invariants...
I/DeviceManagement( 2696): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2696): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e384f8]
I/ActivityManager(  908): Resuming delayed broadcast
I/DeviceManagement( 2696): WorkflowService: Stopping workflow service
I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2778 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/Process (  908): killProcessQuiet, pid=2355
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2355:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2355
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 2766): ====startRecUseTime====
D/htc.customization.log.level( 2766):  is 
W/CustomizationLogLevel( 2766): Level value is invalid, use default level 2
I/htcbackup-core( 2745): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  908): sending alarm PendingIntent{42625490: PendingIntentRecord{423d4790 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=13, w=1440901414353, Int=604800000
D/CustomizationManager( 2766):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2766): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2766): full path : /system/customize/CID/HTC__032.xml
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/CustomizationCIDLoader( 2766): Parsing tag category name = system
I/CustomizationCIDLoader( 2766): Parsing tag category name = application
W/dalvikvm( 2745): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
I/RemoteViews.Performance( 1109): com.htc.backup 0 4 15
I/CustomizationCIDLoader( 2766): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2766): Parsing tag category name = AutomotiveHome
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/CustomizationCIDLoader( 2766): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2766): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2766): Parsing tag category name = Settings
I/RemoteViews( 1109): com.htc.backup (true,33751552)
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/CustomizationManager( 2766):  Read CID file spent 0.127 (s)
D/CustomizationManager( 2766):  All configurations done spent 0.128 (s)
I/RemoteViews.Performance( 1109): com.htc.backup 1 1 0 4
I/RemoteViews( 1109): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1109): com.htc.backup 3 2 0 4
I/RemoteViews( 1109): com.htc.backup (true,33751552)
W/HtcNativeFlag( 2766): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2766): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2766): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2766): Fail to get flag for type 'language', use default value: -1
I/RemoteViews.Performance( 1109): com.htc.backup 1 1 0 4
I/RemoteViews.Performance( 1109): com.htc.backup 2 13 21
D/UPolicy ( 2745): IUserBehaviorLoggingService reference is gotten !
D/Process (  908): killProcessQuiet, pid=2369
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2369:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2369
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2766
D/PMS     (  908): acquireHCC(4253b4b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
W/asset   (  908): Copying FileAsset 0x6f414908 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  908): acquireHCC(424db048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1113456464
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b3bb50
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  908): acquireWL(425fd610): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
W/dalvikvm( 2778): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2778): VFY: unable to resolve instance field 46
W/dalvikvm( 2778): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 2778): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 2778): MmsConfig.loadMmsSettings
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2804 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
V/JNIHelp ( 2778): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_string
I/TrimMemoryManager( 1251): [trimMemory] 20
W/asset   ( 2804): Copying FileAsset 0x5c780420 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 2778): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 2778): MmsConfig.loadFromDatabase
V/WebViewChromiumFactoryProvider( 2804): Binding Chromium to main looper Looper (main, tid 1) {41b0eef0}
I/LibraryLoader( 2804): Expected native library version number "",actual native library version number ""
I/chromium( 2804): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2778, uid=10111, userID:0
I/BrowserStartupController( 2804): Initializing chromium process, renderers=0
W/Settings( 2778): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  908): acquireWL(424894e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  908): acquireWL(4251e910): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothAdapter( 2804): 1102203112: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4242f168:true
E/Babel   ( 2778): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 2778): MmsConfig.loadFromResources
E/Babel   ( 2778): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 2778): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  908): releaseWL(424894e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2778, uid=10111, userID:0
I/Adreno-EGL( 2804): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2804): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2804): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2804): Local Branch: 
I/Adreno-EGL( 2804): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2804): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2804):                  aa63bbd948f41d15fc72f585e
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2778, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2778, uid=10111, userID:0
V/Babel   ( 2778): babel boot account: thalitester@gmail.com
V/Babel   ( 2778): babel boot account: SMS
I/ActivityManager(  908): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2828 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2382
I/ProviderInstaller( 2778): Installed default security provider GmsCore_OpenSSL
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2382:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2382
V/AlarmManager(  908): sending alarm PendingIntent{427d0668: PendingIntentRecord{423f5060 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=48440, Int=0
W/chromium( 2804): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
V/AlarmManager(  908): sending alarm PendingIntent{425a4f68: PendingIntentRecord{426476c8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=48446, Int=0
W/dalvikvm( 2804): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2804): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2804): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2804): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2804): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2804): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2804): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2804): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 2804): CordovaWebView is running on device made by: HTC
I/ActivityManager(  908): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2852 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  908): killProcessQuiet, pid=2404
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2404:com.htc.video/u0a57 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2404
D/ResetNotifyBootCompleteReceiver( 1217): Receive bootcomplete intent
W/ContextImpl( 1217): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2872 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/dalvikvm-heap( 1217): Grow heap (frag case) to 12.397MB for 2097144-byte allocation
W/AwContents( 2804): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1251
W/ResourceType( 2804): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2804): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b55c30, mServedView=org.apache.cordova.engine.SystemWebView{41b1bc08 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 2804): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +368ms
I/InputMethodManagerService(  908): Enable input method client, pid=2804
D/AppTag  ( 2872): getInstance(Context context)
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/HtcCupdXmlParser( 2852): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/PMS     (  908): releaseWL(425fd610): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ActivityThread( 2852): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
D/AppTag  ( 2872): getInstance(Context context)
D/AppTag  ( 2872): onCreate()
D/QXDM2SD:HtcNative( 1217): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2892 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2422
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2422:com.htc.lmw/u0a60 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2422
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/chromium( 2804): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 2804): Unable to open asset URL: file:///android_asset/www/jxcore.js
V/Settings:HtcSettingsApplication( 2892): [2892/2892] onCreate()
I/HtcCupdXmlParser( 2852): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
W/ContextImpl( 2892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/JsMessageQueue( 2804): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2911 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2525
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2525:com.htc.reportagent/u0a66 (adj 15): empty #17
I/AlarmManager(  908): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  908): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  908): [AlarmQueuing] init alarm queuing list
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2921 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  908): killProcessQuiet, pid=2542
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Recipient 2525
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Killing 2542:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2542
D/HtcFingerPrintQuickLaunchProvider( 2911): -onCreate()
V/Settings:HtcSettingsApplication( 2911): [2911/2911] onCreate()
D/jxcore_app_log( 2804): JniHelper::setJavaVM(0x415e0048), pthread_self() = 1657956752
D/JX-Cordova( 2804): jxcore cordova android initializing
W/ContextImpl( 2911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41ef70d0
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41e8b830
D/TetherSettings( 2911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2911): Cust_ConnectToPC   : spcsc>false
D/        ( 2911): Cust_ConnectToPC   : IPT>true
D/        ( 2911): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41d82250
D/Process (  908): killProcessQuiet, pid=2554
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/TetherSettings( 2911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2911): Cust_ConnectToPC   : spcsc>false
D/        ( 2911): Cust_ConnectToPC   : IPT>true
D/        ( 2911): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2911): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2911): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2911): setISNotification
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  908): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  908): Killing 2554:com.htc.showme/u0a83 (adj 15): empty #17
D/SmartNS_Utility( 2911): usb_cable_connect = 1
D/SmartNS_Utility( 2911): usb_denied = 0
I/SmartNS_PSService( 2911): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2554
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (2911/1000)
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 2911): usb_cable_connect = 1
D/SmartNS_Utility( 2911): usb_denied = 0
I/SmartNS_PSService( 2911): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (2911/1000)
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  908): killProcessQuiet, pid=2568
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/ActivityManager(  908): Killing 2568:com.htc.updater/u0a85 (adj 15): empty #17
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e3e698 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1109): com.android.settings 2 10 0 10
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Recipient 2568
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 2804): Initializing JXcore engine
W/jxcore-log( 2804): JXcore engine is ready
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1109): com.android.settings 2 0 10
W/jxcore-log( 2804): Starting JXcore engine
I/ActivityManager(  908): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2938 uid=9987 gids={49987}
,I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4241c068, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4241c068, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423e5418
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@42181de8
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@4241c068
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4241c068, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{425d7d68 u0 ReceiverList{425e06b0 908 system/1000/u0 local:425ef130}}
D/NfcUiccLockService( 2938): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2952 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,D/Process (  908): killProcessQuiet, pid=2599
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2599:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2599
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 3
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4241c068, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423e5418
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@42181de8
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@4241c068
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2964 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2642
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2642:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2642
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 2582): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1955): Google Analytics 8.3.01 is starting up.
,W/jxcore-log( 2804): Platform android
W/jxcore-log( 2804): 
,W/jxcore-log( 2804): Process ARCH arm
W/jxcore-log( 2804): 
,I/jxcore-log( 2804): JXcore Cordova bridge is ready!
I/jxcore-log( 2804): 
,W/jxcore-log( 2804): JXcore engine is started
,E/jxcore-log( 2804): >> HTC-HTC Desire 820
E/jxcore-log( 2804): 
,I/jxcore-log( 2804): Total memory 1964650496
I/jxcore-log( 2804): 
I/jxcore-log( 2804): Free memory 701075456
I/jxcore-log( 2804): 
I/jxcore-log( 2804): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2804): 
,I/jxcore-log( 2804): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2804): 
,I/jxcore-log( 2804): userPath [ 'www' ]
I/jxcore-log( 2804): 
,I/jxcore-log( 2804): Size 720 1184
I/jxcore-log( 2804): 
,I/jxcore-log( 2804): Screen Brightness 142
I/jxcore-log( 2804): 
,E/jxcore-log( 2804): Dummy Error Log.
E/jxcore-log( 2804): 
,E/YouTube ( 2964): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2964): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2964): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2964): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (2964/10168)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2964): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2964): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2964): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2964): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2964): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.youtube (pid 2964): Registered
,I/MediaRouter( 2964): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
D/YouTube ( 2964): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2964): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448306446&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.youtube (2964/10168)
D/libc    ( 2964): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2964): [NET] getaddrinfo-,err=8
D/libc    ( 2964): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2964): [NET] getaddrinfo-, 1
D/libc    ( 2964): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 2964): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2964): Error sending ping
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2964): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2964): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 2964): getSelectedRoute
,D/YouTube ( 2964): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (2964/10168)
D/YouTube ( 2964): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=2670
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2670:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2670
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/YouTube ( 2964): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2964): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2964): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/jxcore-log( 2804): getBuffer is called!!!!
I/jxcore-log( 2804): 
,W/dalvikvm( 1955): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1955): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1955): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1955): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1955): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(4253b4b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  908): releaseHCC(424db048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/GmsModuleFndr( 1955): Beginning GMS chimera module scan
,W/asset   ( 1955): Copying FileAsset 0x6530dcf8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 1955): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1955): Beginning module configuration check
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/ChimeraCfgMgr( 1955): Module APKs unchanged, check complete
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver,
E/dalvikvm( 1955): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1955): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1955/10029)
D/PMS     (  908): acquireWL(42547048): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(4253a6b0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1955 10029 null,
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,E/dalvikvm( 1955): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1955): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1955): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1955): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  908): acquireWL(429966f8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1955): COMPAT: Multi user not supported
,D/GCM     ( 1338): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  908): acquireWL(4265eec8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(426d63f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42547048): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
,I/CheckinService( 1955): Checkin interval check for package: unspecified last checkin: 1448298643009 min interval config: 0 actual interval: 7803911
,I/GCoreUlr( 1955): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1201): DispatchingService.onCreate()
,I/CheckinService( 1955): Disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1955, uid=10029, userID:0
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
,D/SystemUpdateService( 1955): onCreate
D/PMS     (  908): acquireWL(426dd0e0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42697428): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(429966f8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1955, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1955, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
,D/SystemUpdateService( 1955): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
D/PMS     (  908): releaseWL(4253a6b0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
D/PMS     (  908): acquireWL(4282fcf8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1955, uid=10029, userID:0
D/PMS     (  908): releaseWL(426dd0e0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/CheckinService( 1955): Checking schedule, now: 1448306446987 next: 1448298672940
,I/CheckinService( 1955): active receiver: enabled
W/dalvikvm( 1955): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1955/10029)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1955, uid=10029, userID:0
V/AuthZen ( 1955): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1955): cancelUpdate (empty URL)
I/SystemUpdateService( 1955): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
D/AuthZenEventHandler( 1955): Handling event: android.intent.action.BOOT_COMPLETED
D/PMS     (  908): acquireWL(4263cb28): PARTIAL_WAKE_LOCK  Icing 0x1 1955 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 1201): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  908): releaseWL(4263cb28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(426d63f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 1955): onDestroy
D/PMS     (  908): releaseWL(4265eec8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 1955): Aggregate from 1448304437859 (log), 1448304437859 (data)
,W/BaseAppContext( 1955): Using Auth Proxy for data requests.
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1201, uid=10029, userID:0
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1955): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GCoreUlr( 1201): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  908): acquireWL(428215c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1201): Unbound from all location providers
D/PMS     (  908): releaseWL(428215c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4282fcf8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,W/dalvikvm( 1955): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/GCoreUlr( 1201): DispatchingService.onDestroy()
,I/GCoreUlr( 1201): Stopping handler for UlrDispSvcFast
,I/AuthZen ( 1955): Fetching signing key...
,D/PMS     (  908): acquireWL(42981148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 4 times.
,I/GCoreUlr( 1201): Unbound from all location providers
D/PMS     (  908): releaseWL(42981148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/AuthZen ( 1955): Signing key fetched successfully!
,W/BaseAppContext( 1955): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 1955): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1955): Clearing transaction cache
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(42697428): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,W/Auth    ( 1338): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/ActivityManager(  908): Resuming delayed broadcast
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  908): acquireWL(426d20b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1338 10029 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  908): releaseWL(426d20b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1338): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 1955): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1338): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3055 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(4288a868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/PMS     (  908): releaseWL(4288a868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3055, uid=10074, userID:0
,D/Finsky  ( 3055): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3055/10074)
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3055/10074)
,D/Finsky  ( 3055): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3055): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3055): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3055): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3055, uid=10074, userID:0
,D/Volley  ( 3055): [283] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3055): Skipping gmscore version check
D/Volley  ( 3055): [276] DiskBasedCache.clear: Cache cleared.
,D/Process (  908): killProcessQuiet, pid=2682
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 2682:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/PMS     (  908): releaseWL(4251e910): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  908): Recipient 2682
,D/Finsky  ( 3055): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3055): [1] Libraries$2.run: Finished loading 1 libraries.
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 3055): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1290): receiver - intent: android.intent.action.USER_PRESENT,
,D/AutoSetting( 1290): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
,D/TetherSettings( 2911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2911): Cust_ConnectToPC   : spcsc>false
D/        ( 2911): Cust_ConnectToPC   : IPT>true
D/        ( 2911): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2911): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 2911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2911): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/Finsky  ( 3055): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  908): Resuming delayed broadcast
,I/PSReceiver( 2911): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 2911): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2911):  defaultType:0
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3093 uid=10041 gids={50041}
,D/Process (  908): killProcessQuiet, pid=2451
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3106 uid=10078 gids={50078}
I/ActivityManager(  908): Killing 2451:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2451
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3106): Got a database change event
,D/Process (  908): killProcessQuiet, pid=2711
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 2711:com.google.android.gm/u0a107 (adj 15): empty #17
,W/WeatherUtility( 1109): can't get weather sync account
,I/ActivityManager(  908): Recipient 2711
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3119 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
,D/CalendarApplication( 3119): onCreate
D/ProviderChangeReceiver( 3119): ---------------------------------------------------
,D/ProviderChangeReceiver( 3119): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3119): start to updateAlertNotification!
W/ContextImpl( 2892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3134 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
D/AlertService( 3119): No fired or scheduled alerts
D/HtcAlertUtils( 3119): -- cancelReminderNotification --
D/HtcAlertUtils( 3119): broadcastExistReminder!
D/DotMatrix( 1575): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  908): killProcessQuiet, pid=2745
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2745:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3149 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3134): can't get weather sync account
,W/WeatherRequest( 3134): request cur loc, but there is no sys cur
,W/Settings( 3134): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3149): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3149): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3149): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  908): Resuming delayed broadcast
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 10 17
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3163 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2696
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2696:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2745
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(423dc400): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3163 10071 null
,D/PMS     (  908): acquireWL(41ea5650): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3163 10071 null
,D/PMS     (  908): releaseWL(423dc400): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3163): update TASK shortcut>
,I/TodoTaskNotifyService( 3163): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1575): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): releaseWL(41ea5650): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,W/NotifyReceiver( 3163): stopSelfResult true
,D/Process (  908): killProcessQuiet, pid=2778
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3178 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  908): Killing 2778:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2696
,I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3190 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  908): Recipient 2778
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=2828
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  908): Killing 2828:com.htc.backupreset/1000 (adj 15): empty #17
,D/SMSBackup( 3106): Got a database change event
,I/ActivityManager(  908): Recipient 2828
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3202 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  908): killProcessQuiet, pid=2852
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2852:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2852
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3202): create image Cache, size: 31457280.,
I/ImageRamCache( 3202): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3202): create image Cache, size: 12582912.
,I/FeedSettings( 3202): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3202): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3202): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3202): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3202): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3202): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3202): [custom highlight] onReceive
,D/CustomHighlightService( 3202): [custom highlight] onHandleIntent
,I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3202): set custom highlight []
,D/CustomHighlightService( 3202): [custom highlight] set tags 
,D/Process (  908): killProcessQuiet, pid=2872
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2872:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2872
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1955, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1955, uid=10029, userID:0
,D/WearableService( 1201): callingUid 10029, callindPid: 1201
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
E/MDM     ( 1201): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1955): Restart initialization of location
,D/MessagingNotification( 2477): New incoming message, can't cancel notification now
,D/MessagingNotification( 2477): newMsgCnt: 0, false
,W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1338): location=null
D/PMS     (  908): acquireWL(427dae70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(427dae70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024145
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024443
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024556
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024578
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024582
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028878
,V/AlarmManager(  908): sending alarm PendingIntent{42028278: PendingIntentRecord{42601748 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21443, Int=1800000
,I/ActivityManager(  908): Resuming delayed broadcast
,V/AlarmManager(  908): sending alarm PendingIntent{42427798: PendingIntentRecord{42547390 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=48404, Int=259200000
,V/AlarmManager(  908): sending alarm PendingIntent{41ded098: PendingIntentRecord{424d38d8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50594, Int=0
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1338): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1338): Proximity feature is not enabled.
V/AlarmManager(  908): sending alarm PendingIntent{4240c8c8: PendingIntentRecord{424fa100 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448276400000, Int=86400000
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,V/GmsCoreStatsServiceLauncher( 1955): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2477): keep hiding shortcut bubble
D/MessagingShortcut( 2477): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2477): After query: 0
D/MessagingShortcut( 2477): mPresentUnreadCount: -1
D/MessagingShortcut( 2477): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2477): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1575): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1575): [EventService] reorderNotification, total:0
D/DotMatrix( 1575): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1575): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3163): update TASK shortcut>
,D/HtcBroadcastReceiver( 1217): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3224 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024145
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024443
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024556
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024578
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024582
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028878
,I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3238 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3224): [528.1.] 30@-202020 -> 40@-202049
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=2921
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  908): killProcessQuiet, pid=2938
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2921:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  908): Killing 2938:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2921
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2938
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(425c9890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
,E/MDM     ( 1201): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/PMS     (  908): releaseWL(425c9890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1955, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1955, uid=10029, userID:0
,D/LocationInitializer( 1955): Restart initialization of location
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1338): location=null
D/PMS     (  908): acquireWL(4257b020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4257b020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024145
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024443
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024556
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024578
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024582
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028878
I/ActivityManager(  908): Resuming delayed broadcast
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
D/AuthorizationBluetoothService( 1338): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1338): Proximity feature is not enabled.
,V/GLSActivity( 1338): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1955): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(429902e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024145
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024443
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024556
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024578
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024582
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028878
,D/PMS     (  908): releaseWL(429902e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4268cdb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10029 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2169): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2169): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2169): [MTP][handleMessage][startService]
D/MtpReceiver( 2169): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2169): [MTP][handleMessage]-
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1338/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024145
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024443
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024556
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024578
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024582
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028878
D/PMS     (  908): releaseWL(4268cdb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpService( 2169): [MTP] startForeground
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3257 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpService( 2169): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2169): TotalSize=1918604,MediaCacheLimit=6000
,D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/PMS     (  908): acquireWL(426a86f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1955 10029 null
D/MtpService( 2169): [isMtpConnected] connected: true
I/RemoteViews( 1109): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1109): com.android.providers.media 1 1 10
I/RemoteViews( 1109): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1109): com.android.providers.media 1 2 15
,D/Process (  908): killProcessQuiet, pid=2952
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2952:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2952
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3257): Loading default preferences
,W/Resources( 3257): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/iu.UploadsManager( 1955): End new media; added: 0, uploading: 0, time: 80 ms
D/PMS     (  908): releaseWL(426a86f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3257): Overriding preferences with custom values
,D/SyncApplication( 3257): Updating preferences succeeded
,E/SyncApplication( 3257): Application created.
D/VolumeInfo( 3257): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3257): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3257): Found 0 mount point(s)
,V/VolumeInfo( 3257): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3257): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3257): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3257): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3257): getNewCalendarAuthority()...,
,D/SyncApplication( 3257): enableAppOperation()+
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3257, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3257, uid=10008, userID:0
,W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3257): enableAppOperation()-
D/HTCUtilities( 3257): isNeorSinged() + 
,D/HTCUtilities( 3257): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3257): isNeorSinged() return false
D/CDMountReceiver( 3257): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3257): USB connected to PC
,D/FOTAReceiver( 3257): onReceive() enter 
,D/FOTAReceiver( 3257): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 2911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 2911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2911): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 2911): Cust_ConnectToPC   : spcsc>false
D/        ( 2911): Cust_ConnectToPC   : IPT>true
,D/        ( 2911): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 2911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2911): Cust_ConnectToPC   : spcsc>false
D/        ( 2911): Cust_ConnectToPC   : IPT>true
D/        ( 2911): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2911): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2911): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 2911): usb_cable_connect = 1
,D/SmartNS_Utility( 2911): usb_denied = 0
,I/SmartNS_NSReceiver( 2911): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 2911): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 2911): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 2911): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 2911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2911):  defaultType:0
I/SmartNS_PSService( 2911): fail notificaiton:false
,W/ContextImpl( 2911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 2911): usb_cable_connect = 1
D/SmartNS_Utility( 2911): usb_denied = 0
I/SmartNS_PSService( 2911): usb notificaiton:true
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2911/1000)
I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 2911): usb_cable_connect = 1
D/SmartNS_Utility( 2911): usb_denied = 0
I/SmartNS_PSService( 2911): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1109): com.android.settings 1 1 10
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
I/ActivityManager(  908): Resuming delayed broadcast
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2911/1000)
D/SmartNS_Utility( 2911): usb_cable_connect = 1
D/SmartNS_Utility( 2911): usb_denied = 0
D/DotMatrix( 1575): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/SmartNS_PSService( 2911): KeyGuard locked:falseKeyGuard is secured:false
I/RemoteViews.Performance( 1109): com.android.settings 0 1 10
D/SmartNS_PSService( 2911): USB Plugged, Set USBPlugged=  truePSenabled:false
W/WeatherUtility( 3134): can't get weather sync account
I/ActivityManager(  908): Resuming delayed broadcast
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1251): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1251): com.google.android.googlequicksearchbox 0 1 5
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3280 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/WeatherRequest( 3134): request cur loc, but there is no sys cur
,W/Settings( 3134): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 3 11 17
,W/ContextImpl( 3280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3280): call getInstance()
I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3280): MY_DEBUG = false
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42651dc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3280 1000 null
,D/Process (  908): killProcessQuiet, pid=2964
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 2964:com.google.android.youtube/u0a168 (adj 15): empty #17
,W/WeatherUtility( 1109): can't get weather sync account
,D/WeatherUtility( 1290): Weather sync is On
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3297 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
D/WSP     ( 1290): [Receiver] auto sync agent, auto sync is enabled, reset schedule
W/WeatherUtility( 3134): can't get weather sync account
,I/ActivityManager(  908): Recipient 2964
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  908): Client com.google.android.youtube (pid 2964): Died!
,W/WeatherRequest( 3134): request cur loc, but there is no sys cur
,W/Settings( 3134): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 9 17
,I/SensorManager(  908): mEventCount = 300
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3316 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3055
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3055:com.android.vending/u0a74 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3055
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  908): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
,W/Settings:Agent(  908): >> traceCallingStack()
,W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1359
,I/MusicStore( 3316): Database version: 95
,W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
,W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  908): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): << traceCallingStack(): 10(ms)
,D/BluetoothManagerService(  908): Message: MESSAGE_DISABLE
,D/WifiManager( 2804): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
,W/ContextImpl( 3316): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: false pid=2804, uid=10396
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1102
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 5(ms)
I/jxcore-log( 2804): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 2804): 
I/jxcore-log( 2804): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2804): 
,W/ContextImpl( 3316): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3316): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,V/AlarmManager(  908): sending alarm PendingIntent{42140d78: PendingIntentRecord{427c3290 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448306451282, Int=0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3316): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3316): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3316, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 3316): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/MediaRouter( 3316): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (3316/10154)
,D/MediaRouter( 3316): getSelectedRoute
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3316, uid=10154, userID:0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(426dccb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(426dccb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/DFPI.PIReciver( 3149): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3149): onHandleIntent
I/DFPI.ApkInstallService( 3149): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3149): check CID = HTC__032
,I/DFPI.ApkInstallService( 3149): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3342 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=3119
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3119:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3342/10053)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3342): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/ActivityManager(  908): Recipient 3119
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils-trace( 3336): Error opening trace file: No such file or directory (2)
,D/PMS     (  908): releaseWL(42651dc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/CustomizationManager( 3336): ====startRecUseTime====
D/htc.customization.log.level( 3336):  is 
,W/CustomizationLogLevel( 3336): Level value is invalid, use default level 2
,D/CustomizationManager( 3336):  Read ACC file spent 0.057 (s)
,D/CIDMapFileReader( 3336): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 3336): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3336): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3336): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3336): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3336): Parsing tag category name = system
,I/CustomizationCIDLoader( 3336): Parsing tag category name = application
,I/CustomizationCIDLoader( 3336): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3336): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3336): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3336): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3336): Parsing tag category name = Settings
,D/CustomizationManager( 3336):  Read CID file spent 0.106 (s)
,D/CustomizationManager( 3336):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 3336): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3336): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3336): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3336): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  908): deletePackageAsUser: pkg=com.example.hello, pid=3336, uid=2000 user=0
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  908): killProcessQuiet, pid=2804
,W/asset   (  908): Copying FileAsset 0x62ab1270 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  908): Killing 2804:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{42349fb0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  908): Skipping PackageSetting{41e3bfc8 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=0: pkg removed
,W/InputDispatcher(  908): channel '423ff730 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  908): channel '423ff730 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '423ff730 com.example.hello.MainActivity (s)'
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1575): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1575): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1575): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/WindowManager(  908): WINDOW DIED Window{423ff730 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3202): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3202): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
D/PMS     (  908): acquireWL(42859508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/FeedHostManager( 1251): [onResume]
,I/FeedProviderManager( 1251): onResume
,I/SocialFeedProvider( 1251): +onResume
I/SocialFeedProvider( 1251): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1251): -onResume
W/WindowManager(  908): Failed looking up window
W/WindowManager(  908): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42683720 does not exist
W/WindowManager(  908): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  908): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  908): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  908): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  908): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  908): WIN DEATH: null
,I/ConnectivityHelper( 1251): [getCurrentConnectionType] no network connection
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 5 times.
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (1251/10076)
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PMS     (  908): releaseWL(42859508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,W/Binder  ( 1187): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1187): java.lang.NullPointerException
W/Binder  ( 1187): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1187): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1187): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1187): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 2804 uid 10396
I/InputMethodManagerService(  908): Enable input method client, pid=1251
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3372 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2892
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2892:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2892
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3372): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3372): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3372): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3372): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3372): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3372): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3372): MODE_GSM access default DB
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
,I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3372): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3372): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3372): MODE_GSM access default DB
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
W/PackageManager(  908): Unable to load service info ResolveInfo{4258b408 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/RingtoneManager( 3372): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3372): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3372): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3372): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  908): start
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  908): Resuming delayed broadcast
,D/DFPI.PIReciver( 3149): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3149): onHandleIntent
,I/DFPI.ApkInstallService( 3149): Media Scan Finished Case 
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3149): check CID = HTC__032
,I/DFPI.ApkInstallService( 3149): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver

```
