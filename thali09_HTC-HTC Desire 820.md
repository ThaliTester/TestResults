#### Test 503880191ec81a5_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
I/htcbackup-core( 3105): ModelRegistry: Loading model meta data from resources...
W/ContextImpl( 3105): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3105): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 3057): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 3057): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.guide, com.htc.smartdim, com.android.settings, com.htc.drive.activator, com.htc.usage, android, com.htc.backupreset, com.htc.autobot.cargps.provider, com.htc.htcpowermanager, com.android.inputdevices, com.qualcomm.privinit, com.htc.lockscreen, com.android.location.fused, com.android.keychain, com.htc.checkinprovider, com.htc.cirmodule, com.htc.mirrorlinkserver, com.htc.home.personalize, com.qualcomm.timeservice, com.android.CSDFunctionG, com.android.providers.settings, com.htc.android.htcsetupwizard, com.htc.backup, com.htc.feedback, com.htc.android.htcloglevel]
I/DeviceManagement( 3057): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
W/ContextImpl( 3105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41b45568 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1114): com.htc.backup 2 7 5 15
I/RemoteViews( 1114): com.htc.backup (true,33751552)
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41b4e8b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 1 3 8 4
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 1 1 1 4
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 1 1 2 4
I/RemoteViews.Performance( 1114): com.htc.backup 1 10 23 21
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
E/cutils-trace( 3128): Error opening trace file: No such file or directory (2)
I/DeviceManagement( 3057): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/DeviceManagement( 3057): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 3057): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 3057): Perf: Scan enabled apps - complete: 1064 ms
I/DeviceManagement( 3057): Perf: *** Enabled app cache update - complete: 1064 ms
I/DeviceManagement( 3057): Perf: *** Config cache update - start...
I/DeviceManagement( 3057): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3057): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 3057): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 3057): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 3057): AlarmController: Scheduling TTL alarm for: 2015.12.29 at 14:39:42.675 CET (due to: com.htc.aurora)
I/DeviceManagement( 3057): Perf: *** Config cache update - complete: 17 ms
I/DeviceManagement( 3057): Perf: *** Cache update - complete: 1082 ms
I/DeviceManagement( 3057): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41aec4c8]
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3057, uid=10098, userID:0
I/DeviceManagement( 3057): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41dec640] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3057): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3057): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3057): SessionStateController: Checking invariants...
D/CustomizationManager( 3128): ====startRecUseTime====
D/htc.customization.log.level( 3128):  is 
W/CustomizationLogLevel( 3128): Level value is invalid, use default level 2
I/DeviceManagement( 3057): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3057): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41dec640]
I/ActivityManager(  903): Resuming delayed broadcast
I/DeviceManagement( 3057): WorkflowService: Stopping workflow service
D/Process (  903): killProcessQuiet, pid=2798
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3138 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  903): Killing 2798:com.htc.video/u0a57 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2798
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3128):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3128): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3128): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3128): Parsing tag category name = system
I/CustomizationCIDLoader( 3128): Parsing tag category name = application
I/CustomizationCIDLoader( 3128): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3128): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3128): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3128): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3128): Parsing tag category name = Settings
D/CustomizationManager( 3128):  Read CID file spent 0.112 (s)
D/CustomizationManager( 3128):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 3128): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3128): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3128): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3128): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3128
D/PMS     (  903): acquireHCC(427333d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
W/asset   (  903): Copying FileAsset 0x626f3c68 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1114844328
D/PMS     (  903): acquireHCC(42733d60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c2cd90
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  903): acquireWL(427366a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/HtcModeClient( 1523): handler message = 4011
E/HtcModeClient( 1523): Check connection and retry 4 times.
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3154 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1267): [trimMemory] 20
W/dalvikvm( 3138): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 3138): VFY: unable to resolve instance field 36
W/dalvikvm( 3138): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 3138): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Babel   ( 3138): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3138): MmsConfig.loadMmsSettings
D/MmsCustomizationProvider( 2830): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3138, uid=10111, userID:0
W/asset   ( 3154): Copying FileAsset 0x5c745530 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/MmsCustomizationProvider( 2830): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3138): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3138): MmsConfig.loadFromDatabase
W/Settings( 3138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/ProviderInstaller( 3138): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 3138): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3138): MmsConfig.loadFromResources
E/Babel   ( 3138): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3138): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
V/WebViewChromiumFactoryProvider( 3154): Binding Chromium to main looper Looper (main, tid 1) {41ac2ea8}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3138, uid=10111, userID:0
I/LibraryLoader( 3154): Expected native library version number "",actual native library version number ""
I/chromium( 3154): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3154): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42548c60:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3138, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3138, uid=10111, userID:0
D/PMS     (  903): acquireWL(428ad0a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): acquireWL(4288be80): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): releaseWL(428ad0a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3154): 1101891744: getState(). Returning 12
V/Babel   ( 3138): babel boot account: thalitester@gmail.com
V/Babel   ( 3138): babel boot account: SMS
,I/ActivityManager(  903): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3183 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=2813
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2813:com.htc.lmw/u0a60 (adj 15): empty #17
V/AlarmManager(  903): sending alarm PendingIntent{4252b980: PendingIntentRecord{425cc260 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=50867, Int=0
,I/Adreno-EGL( 3154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3154): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3154): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3154): Local Branch: 
I/Adreno-EGL( 3154): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3154): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3154):                  aa63bbd948f41d15fc72f585e
V/AlarmManager(  903): sending alarm PendingIntent{42521cc0: PendingIntentRecord{425a8d68 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=50869, Int=0
I/ActivityManager(  903): Recipient 2813
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/htcbackup-core( 3105): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
,W/chromium( 3154): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
V/AlarmManager(  903): sending alarm PendingIntent{42503c08: PendingIntentRecord{42546978 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=18, w=1440901414353, Int=604800000
,W/dalvikvm( 3105): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1114): com.htc.backup 1 2 15
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
W/dalvikvm( 3154): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 3154): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1114): com.htc.backup 1 0 1 4
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1114): com.htc.backup 1 1 0 4
,I/RemoteViews( 1114): com.htc.backup (true,33751552)
,W/dalvikvm( 3154): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3154): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3154): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,I/RemoteViews.Performance( 1114): com.htc.backup 0 1 1 4
,I/RemoteViews.Performance( 1114): com.htc.backup 1 12 21
,W/dalvikvm( 3154): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3154): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 3154): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 3154): CordovaWebView is running on device made by: HTC
,D/Process (  903): killProcessQuiet, pid=2471
I/ActivityManager(  903): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3215 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  903): Killing 2471:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/GAV2    ( 2949): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 2180): Google Analytics 8.4.89 is starting up.
,D/ResetNotifyBootCompleteReceiver( 1240): Receive bootcomplete intent
,W/ContextImpl( 1240): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,D/UPolicy ( 3105): IUserBehaviorLoggingService reference is gotten !
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3237 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
I/HtcCupdXmlParser( 3215): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0(  903):    returned true
D/ActivityThread( 3215): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/ActivityManager(  903): Recipient 2471
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 1240): Grow heap (frag case) to 12.443MB for 2097144-byte allocation
,V/AlarmManager(  903): sending alarm PendingIntent{425773b8: PendingIntentRecord{427334c8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=50839, Int=259200000
,I/ActivityManager(  903): Killing 2432:com.google.android.videos/u0a165 (adj 15): empty #17
W/AwContents( 3154): nativeOnDraw failed; clearing to background color.
,D/Process (  903): killProcessQuiet, pid=2432
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/InputMethodManagerService(  903): Disable input method client, pid=1267
I/InputMethodManagerService(  903): Enable input method client, pid=3154
W/ResourceType( 3154): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3154): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b09d50, mServedView=org.apache.cordova.engine.SystemWebView{41acfbc0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3154): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +534ms
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  903): releaseWL(427366a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/AppTag  ( 3237): getInstance(Context context)
D/AppTag  ( 3237): getInstance(Context context)
D/AppTag  ( 3237): onCreate()
D/QXDM2SD:HtcNative( 1240): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
D/MediaRouterService(  903): Client com.google.android.videos (pid 2432): Died!
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2432
I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3261 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  903): killProcessQuiet, pid=2892
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2892:com.htc.reportagent/u0a66 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2892
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/Settings:HtcSettingsApplication( 3261): [3261/3261] onCreate()
I/HtcCupdXmlParser( 3215): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
W/ContextImpl( 3261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/chromium( 3154): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3154): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3277 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  903): killProcessQuiet, pid=2909
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2909:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/AlarmManager(  903): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  903): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  903): [AlarmQueuing] init alarm queuing list
I/ActivityManager(  903): Recipient 2909
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3289 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/JsMessageQueue( 3154): Set native->JS mode to OnlineEventsBridgeMode
D/Process (  903): killProcessQuiet, pid=2921
I/ActivityManager(  903): Killing 2921:com.htc.showme/u0a83 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Recipient 2921
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 3277): -onCreate()
D/jxcore_app_log( 3154): JniHelper::setJavaVM(0x41596048), pthread_self() = 1658311176
D/JX-Cordova( 3154): jxcore cordova android initializing
V/Settings:HtcSettingsApplication( 3277): [3277/3277] onCreate()
W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42749080
D/TetherSettings( 3277): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3277): Cust_ConnectToPC   : Internet_Sharing>true
I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42749fe0
D/        ( 3277): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3277): Cust_ConnectToPC   : spcsc>false
D/        ( 3277): Cust_ConnectToPC   : IPT>true
D/        ( 3277): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3277): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3277): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3277): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3277): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3277): Cust_ConnectToPC   : spcsc>false
D/        ( 3277): Cust_ConnectToPC   : IPT>true
D/        ( 3277): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3277): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3277): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3277): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3277): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4274ab58
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  903): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/SmartNS_Utility( 3277): setISNotification
D/Process (  903): killProcessQuiet, pid=2935
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/SmartNS_Utility( 3277): usb_cable_connect = 1
D/SmartNS_Utility( 3277): usb_denied = 0
I/SmartNS_PSService( 3277): usb notificaiton:true
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  903): bSetPropertyMultiRAB:false
I/ActivityManager(  903): Killing 2935:com.htc.updater/u0a85 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3277/1000)
D/SmartNS_Utility( 3277): usb_cable_connect = 1
D/SmartNS_Utility( 3277): usb_denied = 0
I/SmartNS_PSService( 3277): usb notificaiton:true
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  903): bSetPropertyMultiRAB:false
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3277/1000)
I/ActivityManager(  903): Recipient 2935
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  903): killProcessQuiet, pid=2964
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 2964:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/RemoteViews( 1114): com.android.settings (true,33751552)
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ae36f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1114): com.android.settings 3 7 0 10
I/ActivityManager(  903): Recipient 2964
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1114): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1114): com.android.settings 1 0 10
I/SensorManager(  903): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@425c6768, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c6768, eanble = 1, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d98470
W/SensorService(  903): Listener[1] = com.android.server.power.DisplayPowerController$10@421597c0
W/SensorService(  903): Listener[2] = com.htc.smartdim.sensor_eye@425c6768
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  903): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@425c6768, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): enable: get sensor name = CM36282 Proximity sensor
I/ActivityManager(  903): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3304 uid=9987 gids={49987}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{41c8ad50 u0 ReceiverList{41c8cc18 903 system/1000/u0 local:42759a98}}
D/NfcUiccLockService( 3304): -- To check whether previous opened channel needed to be closed ...
W/jxcore-log( 3154): Initializing JXcore engine
W/jxcore-log( 3154): JXcore engine is ready
W/jxcore-log( 3154): Starting JXcore engine
I/ActivityManager(  903): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3318 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
D/Process (  903): killProcessQuiet, pid=2595
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2595:com.android.defcontainer/u0a19 (adj 15): empty #17
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 3
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c6768, eanble = 1, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d98470
W/SensorService(  903): Listener[1] = com.android.server.power.DisplayPowerController$10@421597c0
W/SensorService(  903): Listener[2] = com.htc.smartdim.sensor_eye@425c6768
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  903): Recipient 2595
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3330 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=3010
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3010:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3010
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/jxcore-log( 3154): Platform android
W/jxcore-log( 3154): 
W/jxcore-log( 3154): Process ARCH arm
W/jxcore-log( 3154): 
I/jxcore-log( 3154): JXcore Cordova bridge is ready!
I/jxcore-log( 3154): 
W/jxcore-log( 3154): JXcore engine is started
E/jxcore-log( 3154): >> HTC-HTC Desire 820
E/jxcore-log( 3154): 
I/jxcore-log( 3154): Total memory 1964650496
I/jxcore-log( 3154): 
I/jxcore-log( 3154): Free memory 618356736
I/jxcore-log( 3154): 
I/jxcore-log( 3154): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3154): 
I/jxcore-log( 3154): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3154): 
I/jxcore-log( 3154): userPath [ 'www' ]
I/jxcore-log( 3154): 
I/jxcore-log( 3154): Size 720 1184
I/jxcore-log( 3154): 
I/jxcore-log( 3154): Screen Brightness 142
I/jxcore-log( 3154): 
E/jxcore-log( 3154): Dummy Error Log.
E/jxcore-log( 3154): 
E/YouTube ( 3330): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 3330): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3330): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3330): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3330/10168)
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3330): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3330): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3330): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3330): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 3330): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.youtube (pid 3330): Registered
,I/MediaRouter( 3330): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.youtube (3330/10168)
D/YouTube ( 3330): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3330): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1451341429&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3330): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3330): [NET] getaddrinfo-,err=8
D/libc    ( 3330): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3330): [NET] getaddrinfo-, 1
D/libc    ( 3330): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1864 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3330): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3330): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 3330): getSelectedRoute
,D/YouTube ( 3330): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3330): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
,D/YouTube ( 3330): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3330/10168)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3330/10168)
,D/YouTube ( 3330): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 24
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3330): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3381 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3330/10168)
,D/Process (  903): killProcessQuiet, pid=3030
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3030:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3030
,D/YouTube ( 3330): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3330): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3330): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
,D/YouTube ( 3330): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3330): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
,D/YouTube ( 3330): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
,I/GoogleConversionPing( 3330): Ping responded with response code 200
,D/YouTube ( 3330): apps.youtube.datalib.offline.b.run:86 Dispatching stored offline request immediately.
,D/YouTube ( 3330): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3330/10168)
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3381, uid=10074, userID:0
,I/jxcore-log( 3154): getBuffer is called!!!!
I/jxcore-log( 3154): 
,D/Finsky  ( 3381): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3381/10074)
W/dalvikvm( 3330): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 3330): VFY: unable to resolve instance field 36
W/dalvikvm( 3330): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3330): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3381/10074)
,D/Finsky  ( 3381): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/ProviderInstaller( 3330): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3381): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3381): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/libc    ( 3330): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 4
D/libc    ( 3330): [NET] getaddrinfo-,err=8
D/libc    ( 3330): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    ( 3330): [NET] getaddrinfo-, 1
D/libc    ( 3330): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9d53 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  903): releaseHCC(427333d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(42733d60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/dalvikvm( 3381): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3381, uid=10074, userID:0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 259
D/libc    (  363): [NET]res_nsend:resplen=83
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3330): [NET] getaddrinfo_proxy-, success
,I/global  ( 3330): call createSocket() return a new socket.
D/libc    ( 3330): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3330): [NET] getaddrinfo-, SUCCESS
D/Process (  903): killProcessQuiet, pid=3042
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  903): Killing 3042:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Volley  ( 3381): [310] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 3381): [303] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3381): Skipping gmscore version check
,I/ActivityManager(  903): Recipient 3042
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3381): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3381): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3381): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
,D/Finsky  ( 3381): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  903): Resuming delayed broadcast
,W/dalvikvm( 2180): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2180): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2180): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2180): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  903): acquireWL(42787130): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2180 10029 null
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,D/PMS     (  903): acquireWL(42787978): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/FileApkUtils( 2180): Spent 25ms computing apk sha1.
,D/FileApkUtils( 2180): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/PMS     (  903): releaseWL(42787130): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/DexOptUtils( 2180): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2180): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 2180): Reading stored module config
D/PMS     (  903): releaseWL(42787978): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
,D/GmsModuleFndr( 2180): Beginning GMS chimera module scan
,W/asset   ( 2180): Copying FileAsset 0x656614b0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
,D/ChimeraCfgMgr( 2180): Beginning module configuration check
,D/ChimeraCfgMgr( 2180): Module APKs unchanged, check complete
,W/InstanceID/Rpc( 2180): Found 10029
,E/dalvikvm( 2180): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 2180): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2180): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2180): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2180): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2180): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/dalvikvm( 2180): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2180): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=5 [19][1][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,E/dalvikvm( 1223): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1223): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1223): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1223): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1223): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1223): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1223): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1223): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/ActivityManager(  903): Resuming delayed broadcast
E/dalvikvm( 2180): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 2180): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/PMS     (  903): acquireWL(428e9d50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,E/dalvikvm( 2180): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a,
,W/dalvikvm( 2180): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 2180): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  903): acquireWL(428e9d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(428e9d50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(428d93c8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 2180): COMPAT: Multi user not supported
I/CheckinService( 2180): Checkin interval check for package: unspecified last checkin: 1451336015456 min interval config: 0 actual interval: 5414628
,I/GCoreUlr( 2180): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/dalvikvm( 1361): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,I/GCoreUlr( 1223): DispatchingService.onCreate()
,I/CheckinService( 2180): Disabling old GoogleServicesFramework version
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2180, uid=10029, userID:0
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 2180): onCreate
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
,W/dalvikvm( 1361): VFY: unable to resolve instance field 161
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
,D/SystemUpdateService( 2180): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2180, uid=10029, userID:0
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2180, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2180, uid=10029, userID:0
D/PMS     (  903): acquireWL(42885e58): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
,V/AuthZen ( 2180): Handling intent: android.intent.action.BOOT_COMPLETED
D/PMS     (  903): acquireWL(427759e0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2180, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2180, uid=10029, userID:0
I/CheckinService( 2180): Checking schedule, now: 1451341430195 next: 1451858952413
,I/CheckinService( 2180): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2180, uid=10029, userID:0
D/PMS     (  903): releaseWL(427759e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2180, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2180, uid=10029, userID:0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,I/GCoreUlr( 1223): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 2180): Handling event: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 2180): cancelUpdate (empty URL)
,I/SystemUpdateService( 2180): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2180, uid=10029, userID:0
,W/dalvikvm( 1361): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/PMS     (  903): releaseWL(428e9d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 2180): onDestroy
,W/dalvikvm( 1361): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/PMS     (  903): releaseWL(428d93c8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 2180): Using Auth Proxy for data requests.
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,E/BaseAppContext( 2180): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/PMS     (  903): acquireWL(41dfc898): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
D/GCM     ( 1361): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =92e9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AuthZen ( 2180): Fetching signing key...
,I/AuthZen ( 2180): Signing key fetched successfully!
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1223, uid=10029, userID:0
,W/BaseAppContext( 2180): Using Auth Proxy for data requests.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 283
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/AuthZenTransactionCache( 2180): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2180): Clearing transaction cache
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,I/GCoreUlr( 1223): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1223): Unbound from all location providers
,I/GCoreUlr( 1223): Place inference reporting - stopped
D/PMS     (  903): acquireWL(41d810f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(41d810f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42885e58): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/GCoreUlr( 1223): DispatchingService.onDestroy()
,I/GCoreUlr( 1223): Stopping handler for UlrDispSvcFast
D/PMS     (  903): acquireWL(427ab518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(427ab518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1223): Unbound from all location providers
I/GCoreUlr( 1223): Place inference reporting - stopped
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427af190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/ActivityManager(  903): Resuming delayed broadcast
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ChimeraCfgMgr( 2180): Loading module com.google.android.gms.gass from APK com.google.android.gms
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/BootCompletedReceiver( 2180): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2180): Got an BootCompleted event.
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(427b3b40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 903 1000 WorkSource{10029}
,I/IntentController( 1114): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/BootCompletedReceiver( 2180): Will NOT schedule AdAttestation signal task because it's disabled.
D/PMS     (  903): releaseWL(427af190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(427b6be8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/PMS     (  903): releaseWL(427b6be8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,I/GCM     ( 1361): GCM config loaded
,W/dalvikvm( 1361): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
W/Auth    ( 1361): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  903): acquireWL(422d93c0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1361 10029 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneStatusBar( 1114): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/PMS     (  903): releaseWL(422d93c0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1223): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/PMS     (  903): acquireWL(4235a828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  903): releaseWL(41dfc898): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/PMS     (  903): releaseWL(4235a828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 1316): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3277): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3277): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3277): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3277): Cust_ConnectToPC   : spcsc>false
D/        ( 3277): Cust_ConnectToPC   : IPT>true
D/        ( 3277): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3277): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3277): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3277): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3277): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3277): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/SmartNS_PSService( 3277): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3277): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3277):  defaultType:0
W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  903): acquireWL(42655de0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025186
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025336
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025477
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025499
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025523
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026856
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026877
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029870
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360034191
,I/ActivityManager(  903): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3470 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
V/AlarmManager(  903): sending alarm PendingIntent{41d93820: PendingIntentRecord{428e1190 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1451341427342, Int=0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(42604800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
V/AlarmManager(  903): sending alarm PendingIntent{41bd17e0: PendingIntentRecord{4244db58 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51102, Int=0
D/PMS     (  903): acquireWL(4273c0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 903 1000 WorkSource{10029}
I/ActivityManager(  903): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService: pid=3483 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
V/AlarmManager(  903): sending alarm PendingIntent{4206fd20: PendingIntentRecord{427f15a8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1451341430302, Int=0
D/PMS     (  903): releaseWL(42655de0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/browser ( 3470): Browser versionCode = 760001523 versionName = 7.0.2512153020
D/PMS     (  903): releaseWL(42604800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(423983e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(4288be80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  903): releaseWL(427b3b40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  903): releaseWL(423983e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42668ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42668ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SWE_UI  ( 3470): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3470): Loading: swewebviewchromium
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
I/LibraryLoader( 3470): Time to load native libraries: 39 ms (timestamps 738-777)
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
I/LibraryLoader( 3470): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3470): Initializing chromium process, renderers=9
,I/LibraryLoader( 3470): Expected native library version number "",actual native library version number ""
,I/chromium( 3470): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/iu.UploadsManager( 2180): End new media; added: 0, uploading: 0, time: 113 ms
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42682ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(4273c0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  903): acquireWL(4261f820): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3483 10160 null
,I/IntentController( 1114): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42682ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(42577fa8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3483 10160 null
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(4261f820): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3483/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3483/10160)
,D/PMS     (  903): releaseWL(42577fa8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PhoneStatusBar( 1114): removeIcon slot=sync_active index=7 viewIndex=0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/Adreno-EGL( 3470): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3470): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3470): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3470): Local Branch: 
I/Adreno-EGL( 3470): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3470): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3470):                  aa63bbd948f41d15fc72f585e
,D/Process (  903): killProcessQuiet, pid=3072
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1286): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/ActivityManager(  903): Killing 3072:com.google.android.gm/u0a107 (adj 15): empty #17
I/SIMStateChangeReceiver( 1523): SIM state: ABSENT
I/SIMStateChangeReceiver( 1523): phoneType = 0
I/SIMStateChangeReceiver( 1523): remove notification
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3536 uid=10032 gids={50032, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3105
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3548 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 3105:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3072
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3105
,W/SystemReader( 2830): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2830): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2830): onReceive()
D/ExchangePolicystatus( 2830): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2830): onReceive(): else
,D/Process (  903): killProcessQuiet, pid=3057
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1240): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  903): Killing 3057:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3563 uid=10041 gids={50041}
,D/AccTypeManager( 3548): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3578 uid=10078 gids={50078}
,D/Process (  903): killProcessQuiet, pid=3138
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3138:com.google.android.talk/u0a111 (adj 15): empty #17
,W/AccTypeManager( 3548): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3548): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3057
,D/SMSBackup( 3578): Got a database change event
,D/Process (  903): killProcessQuiet, pid=3183
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3183:com.htc.backupreset/1000 (adj 15): empty #17
,W/WeatherUtility( 1114): can't get weather sync account
,E/ExternalAccountType( 3548): Unsupported attribute readOnly
I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3593 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1114): request cur loc, but there is no sys cur
,D/AccTypeManager( 3548): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  903): Recipient 3138
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3548): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3548): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/CalendarApplication( 3593): onCreate
D/ProviderChangeReceiver( 3593): ---------------------------------------------------
,D/ProviderChangeReceiver( 3593): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3593): start to updateAlertNotification!
,E/ExternalAccountType( 3548): Unsupported attribute readOnly
W/ContextImpl( 3261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/AlertService( 3593): No fired or scheduled alerts
D/HtcAlertUtils( 3593): -- cancelReminderNotification --
D/HtcAlertUtils( 3593): broadcastExistReminder!
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3215
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3215:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3183
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3215
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,E/MDM     ( 1223): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/LocationInitializer( 2180): Restart initialization of location
I/ActivityManager(  903): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  903): acquireWL(42357cf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42357cf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025186
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025336
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025477
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025499
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025523
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026856
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026877
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029870
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360034191
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3613 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3613): can't get weather sync account
,W/WeatherRequest( 3613): request cur loc, but there is no sys cur
,W/Settings( 3613): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1267): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1267): com.htc.widget.weatherclock 1 11 17
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3628 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  903): sending alarm PendingIntent{42255c98: PendingIntentRecord{42565290 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54957, Int=0
,I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3642 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3628): [980.1.] 30@-232320 -> 40@-232352
,I/ActivityManager(  903): Killing 3237:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3237
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  903): killProcessQuiet, pid=3289
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3289:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3289
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3237
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 5 times.
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3654 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3304
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3304:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3304
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3654): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3654): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3654): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3668 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3318
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3318:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3318
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(41be24f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3668 10071 null
,D/PMS     (  903): acquireWL(42495ea8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3668 10071 null
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  903): releaseWL(41be24f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3668): update TASK shortcut>
,I/TodoTaskNotifyService( 3668): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3668): stopSelfResult true
D/PMS     (  903): releaseWL(42495ea8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3683 uid=10082 gids={50082, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3330
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3330:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  903): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3695 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  903): Recipient 3330
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.youtube (pid 3330): Died!
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3707 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3277
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  903): killProcessQuiet, pid=3381
I/ActivityManager(  903): Killing 3277:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  903): Killing 3381:com.android.vending/u0a74 (adj 15): empty #18
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  903): Recipient 3277
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3381
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3707): Database version: 95
,W/ContextImpl( 3707): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3707): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/MessagingNotification( 2830): New incoming message, can't cancel notification now
,W/ContextImpl( 3707): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/MessagingNotification( 2830): newMsgCnt: 0, false
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3707): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3707): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3707, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 3707): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/MediaRouter( 3707): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3707/10154)
,I/NetworkMonitor( 3707): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1932/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3728 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 3707): getSelectedRoute
,I/NetworkMonitor( 3707): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3707/10154),
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3707, uid=10154, userID:0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(426397a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/Process (  903): killProcessQuiet, pid=3470
I/ActivityManager(  903): Killing 3470:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/PMS     (  903): releaseWL(426397a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3728): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3728): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3728): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/ActivityManager(  903): Recipient 3470
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 3728): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3728): Preparing secondary program dexes.
V/DexLibLoader( 3728): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3728): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3728): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3728): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3728): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3728): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 3728): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3728): Dex already copied
D/OdexVerifier( 3728): Odex verification is skipped.
,V/DexLibLoader( 3728): Creating class loader
,V/DexLibLoader( 3728): Finished creating class loader
,V/DexLibLoader( 3728): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3728): Dex already copied
D/OdexVerifier( 3728): Odex verification is skipped.
,V/DexLibLoader( 3728): Creating class loader
,V/DexLibLoader( 3728): Finished creating class loader
,V/DexLibLoader( 3728): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3728): Dex already copied
D/OdexVerifier( 3728): Odex verification is skipped.
,V/DexLibLoader( 3728): Creating class loader
,V/DexLibLoader( 3728): Finished creating class loader
,V/DexLibLoader( 3728): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3728): Dex already copied
D/OdexVerifier( 3728): Odex verification is skipped.
,V/DexLibLoader( 3728): Creating class loader
,V/DexLibLoader( 3728): Finished creating class loader
,V/DexLibLoader( 3728): Verifying classes from secondary dexes.
,D/DexLibLoader( 3728): DexLibLoader.ensureDexLoaded took 142 ms
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  903): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@41d189f0 mBinding = false
,W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
,W/Settings:Agent(  903): Process.myPid(): 903
,W/Settings:Agent(  903): Process.myTid(): 1380
,W/Settings:Agent(  903): Process.myUid(): 1000
,W/Settings:Agent(  903): 
,W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 9(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  903): Sending off request.
,D/BluetoothAdapterState( 1635): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1635): Setting state to 13
,I/BluetoothAdapterState( 1635): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1635): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  903): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 1635): onBluetoothDisable()
,I/bt-btm  ( 1635): BTM_SetDiscoverability
I/bt-btm  ( 1635): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1635): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1635): br_edr_supported=0x0
,I/bt-btm  ( 1635): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1635): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1635): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1635): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterState( 1635): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 1635): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1635): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 1635): evt_type=0x3 p-cb->evt_type=0x3 
,I/bt-btm  ( 1635): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1635): BTM_SetConnectability
,I/bt-btm  ( 1635): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1635): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 1635): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 1635): Scan Mode:20
E/BTIF_CORE( 1635): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1635): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothRemoteDevices( 1635): Wake lock Aquired
D/BluetoothAdapterState( 1635): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/WifiManager( 3154): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
D/bt-btm  ( 1635): BTM_FreeSCN 
,I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btif ( 1635): BTA_JvDeleteRecord
I/bt-btif ( 1635): BTA_JvRfcommStopServer
,D/bt-btm  ( 1635): BTM_FreeSCN 
V/BluetoothSapService( 1635): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BtOppRfcommListener( 1635): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/PMS     (  903): acquireWL(426a1080): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1635 1002 null
,D/WifiService(  903): New client listening to asynchronous messages
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1635): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1635): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1635): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1635): Write Extended Inquiry Response to controller
I/bt-btm  ( 1635): Write Extended Inquiry Response to controller
I/bt-btm  ( 1635): Write Extended Inquiry Response to controller
I/bt-btm  ( 1635): Write Extended Inquiry Response to controller
I/bt-btm  ( 1635): BTM_SetDiscoverability
I/bt-btm  ( 1635): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1635): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1635): br_edr_supported=0x0
I/bt-btm  ( 1635): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1635): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1635): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1635): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1635): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1635): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1635): BTM_SetConnectability
I/bt-btm  ( 1635): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1635): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1635): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1635): BTM_IsInquiryActive
I/bt-btm  ( 1635): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1635): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btm  ( 1635): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1635): BTM_FreeSCN 
I/bt-btm  ( 1635): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1635): AVRC_Close handle:0
I/IntentController( 1114): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1356
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSe,ttingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1772): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ae5258
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): onDeInitialized
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:4
D/WifiService(  903): setWifiEnabled: false pid=3154, uid=10397
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/bt-sdp  ( 1635): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1635): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1635): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1635): GATT_Deregister gatt_if=3
I/bt-att  ( 1635): GATT_Deregister gatt_if=4
V/BluetoothPbapReceiver( 1635): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1635): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): getNotificationManager
D/BluetoothMasReceiver( 1635): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1635): SapReceiver onReceive 
V/BluetoothSapReceiver( 1635): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1635):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1635): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1635): Pbap Service closeService in
D/PMS     (  903): acquireWL(426a5290): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1223 10029 null
I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3745 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  903): releaseWL(426a5290): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
V/BluetoothPbapService( 1635): successfully stopped pbap service
V/BluetoothPbapService( 1635): Pbap Service closeService out
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1772): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1772):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1772): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1772): deinit: 0
D/BluetoothManagerService(  903): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm
D/BluetoothManagerService(  903): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423e13a8:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm: null
I/BtOppRfcommListener( 1635): stopping Accept Thread
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1772): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1772): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1772): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1772): setPendingRequestAlarm: false, mContext = null, null
I/BtOppRfcommListener( 1635): BluetoothSocket listen thread finished
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1772): Exit IdleState
V/BluetoothSapService( 1635): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1635): state: 13
D/BluetoothAdapter( 1635): 1101884192: getState(). Returning 13
V/BluetoothSapService( 1635): Stopping SAP server process
V/BluetoothSapService( 1635): Sap Service closeSapService in
V/BluetoothSapService( 1635): Close listen Socket : 
V/BluetoothSapService( 1635): Close rfcomm Socket : 
V/BluetoothSapService( 1635): Close sapd  Socket : 
V/BluetoothSapReceiver( 1635): BluetoothSapReceiver deinit
I/jxcore-log( 3154): ****TEST TOOK:  5134  ms ****
I/jxcore-log( 3154): 
I/jxcore-log( 3154): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3154): 
D/WirelessDisplayService(  903): getMirrorDisplayStatus:falsecurState:1
V/BluetoothSapService( 1635): successfully stopped Sap service
V/BluetoothSapService( 1635): Sap Service closeSapService out
V/BluetoothPbapService( 1635): Pbap Service onDestroy
V/BluetoothPbapService( 1635): Pbap Service closeService in
,V/BluetoothPbapService( 1635): Pbap Service closeService out
V/BluetoothSapService( 1635): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b10cb8
V/BluetoothSapService( 1635): Sap Service closeSapService in
V/BluetoothSapService( 1635): Close listen Socket : 
V/BluetoothSapService( 1635): Close rfcomm Socket : 
V/BluetoothSapService( 1635): Close sapd  Socket : 
V/BluetoothSapService( 1635): Sap Service closeSapService out
D/WifiPerfLock(  903): release()
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
V/BluetoothSapService( 1635): ***onDestroyed***
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
I/QuickSettingBluetooth( 1114): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1114): removeIcon slot=bluetooth index=12 viewIndex=0
D/PMS     (  903): acquireWL(425bb4f8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025186
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025336
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025477
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025499
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025523
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026856
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026877
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029870
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360034191
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=21050 mDataStallAlarmIntent=PendingIntent{424ff330: PendingIntentRecord{424ff2d0 android broadcastIntent}}
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/HtcFingerPrintQuickLaunchProvider( 3745): -onCreate()
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/UsbnetStateTracker(  903): isAvailable+-
,D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,V/Settings:HtcSettingsApplication( 3745): [3745/3745] onCreate()
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  903): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  903): P2pDisablingState
,D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  903): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  903): set wifi.miracastlock to 0 for disconnect case
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  903): updateConnection
I/WifiDisplayController(  903): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  903): updateConnection enter step 4
D/WifiP2pService(  903): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): p2p socket connection lost
D/WifiStateMachine(  903): Call handleNetworkDisconnect() in SupplicantStoppingState
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/bt-btif ( 1635): ag scb idx 1 not allocated
W/bt-btif ( 1635): ag scb idx 2 not allocated
E/bt-btif ( 1635): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1635): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1635): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1635): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1635): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1635): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1635): L2CAP - PSM: 0x0017 not found for deregistration
V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
,D/HtcEffectManager(  903): convertEffect after=902
,D/WISPrService( 3745): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiP2pService(  903): P2pDisabledState
D/PMS     (  903): acquireWL(42885f20): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3745 1000 null
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/WifiP2pService(  903): P2pDisabledState{ when=-4ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-5ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
,D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  903): Failed to set WFD info with reason 2.
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS,
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,V/NativeCrypto( 1361): Read error: ssl=0x663ecfe0: I/O error during system call, Connection timed out
,D/WISPrService( 3745): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiP2pService(  903): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/PMS     (  903): releaseWL(42885f20): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/WifiService(  903): New client listening to asynchronous messages
D/PMS     (  903): acquireWL(427b31a8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3745 1000 null
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425d2c38:true
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	,at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x663ecfe0: I/O error during system call, Broken pipe
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  903): acquireWL(427b3108): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3765 uid=10040 gids={50040, 3002, 3001}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025186
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025336
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025477
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025499
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025523
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026856
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026877
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029870
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360034191
D/WifiNative-p2p0(  903): doBoolean: TERMINATE
I/LocationAgent( 3745): new LocationAgent instance!!
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  903): QCOM Debug wifi_send_command "TERMINATE"
,E/wpa_supplicant( 1150): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiNative-p2p0(  903):    returned true
D/wpa_supplicant( 1150): TDLS: Tear down peers
I/wpa_supplicant( 1150): wpa_driver_nl80211_disconnect(reason_code=3)
D/HtcTagManager( 3745): HtcTagManager construction complete
D/libc    (  363): [NET] entry_id:6   entry:0xb7d68d08  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7d68c20  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb7d68b20  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7d71db8  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7d6d370  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb7d6d270  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7d71f70  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7d71cf8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7d6d458  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-22ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/bt_userial_mct( 1635): userial_close userial_thread_created userial_running is 1 
,D/BluetoothAdapter( 3745): 1101893616: getState(). Returning 13
D/BluetoothInputDevice( 3745): BluetoothInputDevice()
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 7
,I/IntentController( 1114): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothAdapter( 3745): 1101893616: getState(). Returning 13
,D/BluetoothInputDevice( 3745): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3745): Bluetooth service connected
,W/BluetoothInputDevice( 3745): Proxy not attached to service
,D/BluetoothPan( 3745): BluetoothPan()
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1114): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  903): acquireWL(426a8b10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 8
D/BluetoothAdapter( 3745): 1101893616: getState(). Returning 13
D/BluetoothPan( 3745): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3745): Bluetooth service connected
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  903): releaseWL(427b3108): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BluetoothMap( 3745): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 9
E/BluetoothMap( 3745): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 10
D/BluetoothSap( 3745): BluetoothSap() call bindService
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1150): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1150): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
D/wpa_supplicant( 1150): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e3bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1150):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1150): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1150): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED ,bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/BluetoothPbap( 3745): BluetoothPbap()
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 11
D/PMS     (  903): releaseWL(426a8b10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/BluetoothAdapter( 3745): 1101893616: getState(). Returning 13
D/BluetoothPbap( 3745): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3745): Bluetooth service connected
,D/LocalBluetoothProfileManager( 3745): LocalBluetoothProfileManager construction complete
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/DockEventReceiver( 3745): finishStartingService: stopping service
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/HtcBtWidget_BTWidgetProvider( 3765): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3765): updateWidget(context) for widget: 
,D/Process (  903): killProcessQuiet, pid=3483
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/QuickSettingWifi( 1114): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  903): Killing 3483:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/WISPrService( 3745): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3745): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1635): Shutdown
D/PMS     (  903): releaseWL(427b31a8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,E/cutils-trace( 3759): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  903): Recipient 3483
,D/BluetoothMasReceiver( 1635): Bluetooth STATE CHANGED to 13
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1772): Received state change = 13
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ae5258
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): deinitLeServices: null
,D/Process (  903): killProcessQuiet, pid=3536
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3536:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/WifiService(  903): New client listening to asynchronous messages
,D/Process (  903): killProcessQuiet, pid=3548
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  903): Killing 3548:com.htc.contacts/u0a44 (adj 15): empty #17
,E/wpa_supplicant( 1150): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1150): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
I/wpa_supplicant( 1150): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
I/ActivityManager(  903): Recipient 3536
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/bt-btif ( 1635): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1635): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1635): Received stop request...Stopping profile...
D/BluetoothHeadset(  903): Proxy object disconnected
,D/BluetoothHeadset( 1114): Proxy object disconnected
D/BluetoothHeadset( 1240): Proxy object disconnected
,I/QuickSettingMiniLite( 1114): btListener.disconnect:HEADSET
D/BluetoothHeadset( 1240): Proxy object disconnected
D/A2dpService( 1635): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1635): doQuit
,D/A2dpStateMachine( 1635): Exit Disconnected: -1
I/ActivityManager(  903): Recipient 3548
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothPhoneService( 1240): BluetoothHeadset onServiceDisconnected
D/BluetoothA2dp(  903): Proxy object disconnected
D/BluetoothAdapterState( 1635): Stopping profile services that were post enabled
D/HidService( 1635): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1635): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1635): Profile still running: com.android.bluetooth.hdp.HealthService
D/HealthService( 1635): Received stop request...Stopping profile...
W/BluetoothHeadsetServiceJni( 1635): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1635): Cleaning up Bluetooth Handsfree callback object
D/PanService( 1635): Received stop request...Stopping profile...
D/PanService( 1635): stop
D/PanService( 1635): stop: mTetherAc send disconnect
D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  903): attempted to stop reverse tether with nothing tethered
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=0, operstate=6
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/CustomizationManager( 3759): ====startRecUseTime====
D/htc.customization.log.level( 3759):  is 
W/CustomizationLogLevel( 3759): Level value is invalid, use default level 2
D/wpa_supplicant( 1150): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1150): nl80211: Unsubscribe mgmt frames handle 0xb8e3c718 (mode change)
I/wpa_supplicant( 1150): htc_wext_command_deinit +
I/wpa_supplicant( 1150): htc_wext_command_deinit -
E/wpa_supplicant( 1150): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1150): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1150): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1150): TDLS: Tear down peers
I/wpa_supplicant( 1150): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/BluetoothPan(  903): BluetoothPAN Proxy object disconnected
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/A2dpStateMachine( 1635): cleanup
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x611019b0
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x61101a98
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/Avrcp   ( 1635): Unregistering previous receiver
D/WifiStateMachine(  903): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  903):    returned false
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
D/WifiDat,aStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  903): WIFI Trun OFF
D/WirelessDisplayService(  903): getDiscoveryDongleList
I/IntentController( 1114): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/BtGatt.DebugUtils( 1635): handleDebugAction() action=null
D/BtGatt.GattService( 1635): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1635): stop()
D/BluetoothAdapterService( 1635): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1635): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1635): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1635): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1635): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1635): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1635): Cleaning up Bluetooth Health object
D/PanService( 1635): CMD_CHANNEL_DISCONNECTED
D/PanService( 1635): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1635): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1635): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1635): Cleaning up Bluetooth PAN callback object
D/WIFI_ICON( 1114): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothAdapterState( 1635): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1635): Setting state to 10
I/BluetoothAdapterState( 1635): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1635): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=13 new=10
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 6 { when=-21ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1223): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/BluetoothAdapterState( 1635): Entering OffState
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  903): acquireWL(423f97b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/BluetoothPan( 3745): 
E/BluetoothPan( 3745): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41ae8c88
E/BluetoothPan( 3745): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3745): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3745): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3745): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3745): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3745): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3745): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1114): onBluetoothStateChange: up=false
,D/WISPrService( 3745): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3745): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/BluetoothInputDevice( 3745): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3745): 
E/BluetoothInputDevice( 3745): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41ae6f98
E/BluetoothInputDevice( 3745): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3745): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3745): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3745): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3745): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3745): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3745): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset(  903): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3745): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3745): 
E/BluetoothPbap( 3745): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41af0120
E/BluetoothPbap( 3745): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3745): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3745): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3745): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3745): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3745): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3745): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothSap( 3745): onBluetoothStateChange on: false
,D/BluetoothMap( 3745): onBluetoothStateChange: up=false
,E/BluetoothMap( 3745): 
E/BluetoothMap( 3745): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41aea008
E/BluetoothMap( 3745): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3745): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3745): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3745): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3745): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3745): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3745): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothA2dp(  903): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
D/BluetoothManagerService(  903): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 3745): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ad9a70
,D/BluetoothAdapter( 3745): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1114): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41eabf50
,D/BluetoothAdapter( 1114): onBluetoothServiceDown: done
D/BluetoothAdapter( 1223): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e08310
,D/BluetoothAdapter( 1223): onBluetoothServiceDown: done
D/BluetoothAdapter(  903): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d189f0
D/BluetoothAdapter(  903): onBluetoothServiceDown: done
D/BluetoothAdapter( 1252): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b91b48
,D/BluetoothAdapter( 1252): onBluetoothServiceDown: done
D/BluetoothAdapter( 1240): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d639b0
,D/BluetoothAdapter( 1240): onBluetoothServiceDown: done
D/BluetoothAdapter( 1635): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ad4f90
,D/BluetoothDevice( 1635): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 1635): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1772): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ae5b28
,D/BluetoothAdapter( 1772): onBluetoothServiceDown: done
D/BluetoothAdapter( 3154): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ad9308
,D/BluetoothAdapter( 3154): onBluetoothServiceDown: done
,D/BluetoothManagerService(  903): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@41d189f0 mBinding = false
,D/BluetoothManagerService(  903): Sending unbind request.
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1114): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NfcHandover( 1252): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 3745): setBluetoothStateOff
D/HtcTagManager( 3745): stopProxy
,W/BluetoothEventManager( 3745): unregister mProfileBroadcastReceiver fail
,D/BluetoothAdapter( 1223): 1105223736: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingWifi( 1114): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
D/BluetoothAdapterService( 1635): Cleaning up adapter native....
D/BluetoothAdapter( 1223): 1105223736: getState() :  mService = null. Returning STATE_OFF
,I/bt-btif ( 1635): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 1635): Done cleaning up adapter native....
,D/BluetoothAdapterService(1101866016)( 1635): ****onDestroy()********
D/BtGatt.GattService( 1635): cleanup()
W/bt-btif ( 1635): GATTC Module not enabled/already disabled
,W/bt-btif ( 1635): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 1635): Bluetooth STATE CHANGED to 10
D/PMS     (  903): releaseWL(426a1080): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/PMS     (  903): acquireWL(4261a6d0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1223 10029 null
,D/PMS     (  903): releaseWL(4261a6d0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/TetherPref( 3745): persistRestoreBluetoothState false
,V/BluetoothMasService( 1635): onDestroy: mIsEmailEnabled: true
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/HtcBtWidget_BTWidgetProvider( 3765): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3765): updateWidget(context) for widget: 
D/PMS     (  903): acquireWL(42836db8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3745 1000 null
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  903): releaseWL(42836db8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  903): acquireWL(425c8898): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3745 1000 null
,D/DockEventReceiver( 3745): finishStartingService: stopping service
,W/BluetoothHeadset( 1114): Proxy not attached to service
,I/QuickSettingMiniLite( 1114): updateLiteState:no connect device!
,D/BluetoothMasReceiver( 1635): Bluetooth STATE CHANGED to 10
,D/PMS     (  903): releaseWL(425c8898): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1772): Received state change = 10
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424a8fd0:true
,W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
,D/CustomizationManager( 3759):  Read ACC file spent 0.064 (s)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3759): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3759): Parsing tag item name = HTC__031
,W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
V/CustomizationCIDLoader( 3759): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3759): Parsing tag category name = system
,I/CustomizationCIDLoader( 3759): Parsing tag category name = application
I/CustomizationCIDLoader( 3759): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 3759): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3759): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3759): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3759): Parsing tag category name = Settings
D/CustomizationManager( 3759):  Read CID file spent 0.108 (s)
,D/CustomizationManager( 3759):  All configurations done spent 0.108 (s)
,W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,D/BluetoothAdapter( 1114): 1104599528: getState() :  mService = null. Returning STATE_OFF
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
I/QuickSettingBluetooth( 1114): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
W/HtcNativeFlag( 3759): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3759): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3759): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3759): Fail to get flag for type 'language', use default value: -1
,I/LocationAgent( 3261): new LocationAgent instance!!
,D/HtcTagManager( 3261): HtcTagManager construction complete
,D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 3261): BluetoothInputDevice()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  903): Registered receivers: 12
D/BluetoothInputDevice( 3261): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3261): Bluetooth service connected
,W/BluetoothInputDevice( 3261): Proxy not attached to service
,D/BluetoothPan( 3261): BluetoothPan()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 13
D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3261): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3261): Bluetooth service connected
,D/BluetoothMap( 3261): Create BluetoothMap proxy object
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 14
,E/BluetoothMap( 3261): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothSap( 3261): BluetoothSap() call bindService
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 15
,D/BluetoothPbap( 3261): BluetoothPbap()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3261): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3261): Bluetooth service connected
D/LocalBluetoothProfileManager( 3261): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3261): 1101974344: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3261): setBluetoothStateOff
D/HtcTagManager( 3261): stopProxy
D/BluetoothManagerService(  903): Registered receivers: 16
,W/BluetoothEventManager( 3261): unregister mProfileBroadcastReceiver fail
,D/Process (  903): killProcessQuiet, pid=3563
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/ContextImpl( 3261): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,I/ActivityManager(  903): Killing 3563:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  903): Recipient 3563
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=3759, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=3154
,W/asset   (  903): Copying FileAsset 0x697b0378 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/ActivityManager(  903): Killing 3154:com.example.hello/u0a397 (adj 0): stop com.example.hello
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  903): Force removing ActivityRecord{42314908 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  903): Skipping PackageSetting{4224cf68 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  903): Force stopping com.example.hello appid=10397 user=0: pkg removed
,W/InputDispatcher(  903): channel '424c9dc0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  903): channel '424c9dc0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/dalvikvm( 3728): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/WifiService(  903): Client connection lost with reason: 4
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '424c9dc0 com.example.hello.MainActivity (s)'
D/PMS     (  903): acquireWL(428cb5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
I/WindowState(  903): WIN DEATH: Window{424c9dc0 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  903): releaseWL(428cb5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/FeedHostManager( 1267): [onResume]
,I/FeedProviderManager( 1267): onResume
I/ConnectivityHelper( 1267): [getCurrentConnectionType] no network connection
,I/SocialFeedProvider( 1267): +onResume
,I/SocialFeedProvider( 1267): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1267): -onResume
,W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/WindowManager(  903): WINDOW DIED Window{424c9dc0 u0 com.example.hello/com.example.hello.MainActivity}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1267/10076)
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3154 uid 10397
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  903): Enable input method client, pid=1267
,W/dalvikvm( 3728): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3707): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3707/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
,W/PackageManager(  903): Unable to load service info ResolveInfo{4292d9d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,W/Netd    (  363): No subsystem found in netlink event
,V/Tethering(  903): remove iface:wlan0
D/Tethering(  903): interfaceRemoved wlan0
,E/Tethering(  903): attempting to remove unknown iface (wlan0), ignoring
,W/dalvikvm( 3728): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,E/FbInjectorInitializer( 3728): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/Tethering(  903): interfaceLinkStateChanged p2p0, false
,D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/PMS     (  903): acquireWL(42679be0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
,W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025186
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025336
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025477
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025499
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025523
D/PMS     (  903): releaseWL(42679be0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026856
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360026877
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029870
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360034191
,W/fb4a(:<default>):StaticBindingVerifier( 3728): Verify
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  903): remove iface:p2p0
D/Tethering(  903): interfaceRemoved p2p0
,E/Tethering(  903): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3728/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3728): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3728): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3728): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3578
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3578:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3578
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3810 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/AutoSetting( 1316): Util - no network available!
,D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1316): service - mHandler: cancel location update
,D/AutoSetting( 1316): service -           changes count: 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,D/MobileConnectivityChangeReceiver( 3810): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3810): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3810): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3810): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3823 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3593
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3593:com.htc.calendar/u0a13 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3810/10079)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3810/10079)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3810/10079)
,I/ActivityManager(  903): Recipient 3593
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,D/Process (  903): killProcessQuiet, pid=3613
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3836 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 3613:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3613
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 3836): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 3836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3836/10151)
V/WebViewChromiumFactoryProvider( 3836): Binding Chromium to main looper Looper (main, tid 1) {41ac1360}
I/LibraryLoader( 3836): Expected native library version number "",actual native library version number ""
I/chromium( 3836): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3836): Initializing chromium process, renderers=0
E/NSDepend( 3836): Could not load library: pdflib.dex.jar
E/NSDepend( 3836): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 3836): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/NSDepend( 3836): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/NSDepend( 3836): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:217)
E/NSDepend( 3836): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:205)
E/NSDepend( 3836): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:112)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:971)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:918)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.NSDepend$1.doInBackground(NSDepend.java:951)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 3836): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 3836): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 3836): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 3836): 	at com.google.apps.dots.android.newsstand.async.Queue$3$1.run(Queue.java:162)
E/NSDepend( 3836): 	at java.lang.Thread.run(Thread.java:864)
E/NSDepend( 3836): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 3836): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 3836): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/NSDepend( 3836): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/NSDepend( 3836): 	... 14 more
E/AudioManagerAndroid( 3836): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3836): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3836): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3836): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3836): Local Branch: 
I/Adreno-EGL( 3836): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3836): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3836):                  aa63bbd948f41d15fc72f585e
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,I/NSApplication( 3836): Starting up...
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3836/10151)
,E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3836/10151)
,I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3871 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3628
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3628:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3628
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 3728): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3728): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3728): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3728): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3728): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3728): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3728): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3728): 	at com.faceb,ook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3728): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3728): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3728): 	at java.lang.Thread.run(Thread.java:864)
,W/dalvikvm( 3728): threadid=12: thread exiting with uncaught exception (group=0x4168ee30)
,E/ACRA    ( 3728): ACRA caught a RuntimeException exception for com.facebook.katana. Building report.

```
