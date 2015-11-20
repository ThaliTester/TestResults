#### Test 50388019aa1a16d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/DeviceManagement( 2939): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2939): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2939): Perf: Scan enabled apps - complete: 1118 ms
I/DeviceManagement( 2939): Perf: *** Enabled app cache update - complete: 1118 ms
I/DeviceManagement( 2939): Perf: *** Config cache update - start...
I/DeviceManagement( 2939): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2939): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2939): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2939): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2939): AlarmController: Scheduling TTL alarm for: 2015.11.21 at 10:12:29.299 CET (due to: com.htc.launcher)
I/DeviceManagement( 2939): Perf: *** Config cache update - complete: 23 ms
I/DeviceManagement( 2939): Perf: *** Cache update - complete: 1143 ms
I/DeviceManagement( 2939): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41ae16c8]
I/DeviceManagement( 2939): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41de15e8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2939): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2939): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2939): SessionStateController: Checking invariants...
--------- beginning of /dev/log/system
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2939, uid=10098, userID:0
,I/DeviceManagement( 2939): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2939): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41de15e8]
I/DeviceManagement( 2939): WorkflowService: Stopping workflow service
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3013 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/Process (  905): killProcessQuiet, pid=2624
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2624:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2624
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/htcbackup-core( 2989): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  905): sending alarm PendingIntent{423600d8: PendingIntentRecord{423b9c80 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=12, w=1440901414353, Int=604800000
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 1 2 15
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
W/dalvikvm( 2989): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 0 3 0 4
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 2 1 0 4
I/RemoteViews( 1114): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1114): com.htc.backup 1 2 0 4
I/RemoteViews.Performance( 1114): com.htc.backup 2 13 21
D/UPolicy ( 2989): IUserBehaviorLoggingService reference is gotten !
D/Process (  905): killProcessQuiet, pid=2639
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2639:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2639
I/Babel   ( 3013): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3013): MmsConfig.loadMmsSettings
W/dalvikvm( 3013): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 3013): VFY: unable to resolve instance field 46
W/dalvikvm( 3013): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 3013): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/MmsCustomizationProvider( 2743): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2743): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3013): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3013): MmsConfig.loadFromDatabase
E/Babel   ( 3013): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3013): MmsConfig.loadFromResources
E/Babel   ( 3013): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3013): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3013, uid=10111, userID:0
W/Settings( 3013): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3013, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3013, uid=10111, userID:0
V/Babel   ( 3013): babel boot account: thalitester@gmail.com
V/Babel   ( 3013): babel boot account: SMS
I/ProviderInstaller( 3013): Installed default security provider GmsCore_OpenSSL
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/Process (  905): killProcessQuiet, pid=2674
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3051 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 2674:com.htc.video/u0a57 (adj 15): empty #17
V/AlarmManager(  905): sending alarm PendingIntent{4215cab0: PendingIntentRecord{41d3f720 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47041, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{42143c90: PendingIntentRecord{41c1d2a8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47046, Int=0
I/ActivityManager(  905): Recipient 2674
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3025): ====startRecUseTime====
D/htc.customization.log.level( 3025):  is 
W/CustomizationLogLevel( 3025): Level value is invalid, use default level 2
I/ActivityManager(  905): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3066 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  905): killProcessQuiet, pid=2692
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2692:com.htc.lmw/u0a60 (adj 15): empty #17
D/CustomizationManager( 3025):  Read ACC file spent 0.077 (s)
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3025): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3025): full path : /system/customize/CID/HTC__032.xml
I/ActivityManager(  905): Recipient 2692
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CustomizationCIDLoader( 3025): Parsing tag category name = system
I/CustomizationCIDLoader( 3025): Parsing tag category name = application
I/CustomizationCIDLoader( 3025): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3025): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3025): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3025): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3025): Parsing tag category name = Settings
D/CustomizationManager( 3025):  Read CID file spent 0.133 (s)
D/CustomizationManager( 3025):  All configurations done spent 0.134 (s)
W/HtcNativeFlag( 3025): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3025): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3025): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3025): Fail to get flag for type 'language', use default value: -1
D/ResetNotifyBootCompleteReceiver( 1240): Receive bootcomplete intent
W/ContextImpl( 1240): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/HtcCupdXmlParser( 3066): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3081 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 3066): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  905): acquireHCC(4295c310): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(4295c880): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x65caafc0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1117109832
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3025
D/PMS     (  905): acquireWL(4295f060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f9dff8
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
E/cutils-trace( 3025): Error opening trace file: No such file or directory (2)
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3095 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
D/AppTag  ( 3081): getInstance(Context context)
D/AppTag  ( 3081): getInstance(Context context)
D/AppTag  ( 3081): onCreate()
I/HtcCupdXmlParser( 3066): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
W/asset   ( 3095): Copying FileAsset 0x5c736428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/QXDM2SD:HtcNative( 1240): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/TrimMemoryManager( 1269): [trimMemory] 20
I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3109 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  905): killProcessQuiet, pid=2791
V/WebViewChromiumFactoryProvider( 3095): Binding Chromium to main looper Looper (main, tid 1) {41abb158}
I/LibraryLoader( 3095): Expected native library version number "",actual native library version number ""
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/chromium( 3095): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3095): Initializing chromium process, renderers=0
I/ActivityManager(  905): Killing 2791:com.htc.reportagent/u0a66 (adj 15): empty #17
D/PMS     (  905): acquireWL(4255f8f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(42488288): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
I/ActivityManager(  905): Recipient 2791
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42390940:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3095): 1101859664: getState(). Returning 12
D/PMS     (  905): releaseWL(4255f8f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/AlarmManager(  905): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  905): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  905): [AlarmQueuing] init alarm queuing list
I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3124 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  905): killProcessQuiet, pid=2808
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
V/Settings:HtcSettingsApplication( 3109): [3109/3109] onCreate()
I/ActivityManager(  905): Killing 2808:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
W/ContextImpl( 3109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Recipient 2808
I/Adreno-EGL( 3095): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3095): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3095): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3095): Local Branch: 
I/Adreno-EGL( 3095): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3095): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3095):                  aa63bbd948f41d15fc72f585e
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3148 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/chromium( 3095): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3095): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3095): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3095): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3095): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3095): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@422d32b0
W/dalvikvm( 3095): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3095): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3095): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3095): CordovaWebView is running on device made by: HTC
D/HtcFingerPrintQuickLaunchProvider( 3148): -onCreate()
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41b3ce60
V/Settings:HtcSettingsApplication( 3148): [3148/3148] onCreate()
D/Process (  905): killProcessQuiet, pid=2820
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/ContextImpl( 3148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4265e090
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  905): Killing 2820:com.htc.showme/u0a83 (adj 15): empty #17
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  905): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  905): killProcessQuiet, pid=2834
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 2834:com.htc.updater/u0a85 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2820
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2834
I/ActivityManager(  905): Resuming delayed broadcast
D/TetherSettings( 3148): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3148): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3148): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3148): Cust_ConnectToPC   : spcsc>false
D/        ( 3148): Cust_ConnectToPC   : IPT>true
D/        ( 3148): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3148): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3148): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3148): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3148): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3148): Cust_ConnectToPC   : spcsc>false
D/        ( 3148): Cust_ConnectToPC   : IPT>true
D/        ( 3148): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3148): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3148): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3148): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3148): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 3148): setISNotification
D/SmartNS_Utility( 3148): usb_cable_connect = 1
D/SmartNS_Utility( 3148): usb_denied = 0
I/SmartNS_PSService( 3148): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3148/1000)
D/SmartNS_Utility( 3148): usb_cable_connect = 1
D/SmartNS_Utility( 3148): usb_denied = 0
I/SmartNS_PSService( 3148): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3148/1000)
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  905): killProcessQuiet, pid=2863
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2863:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/RemoteViews( 1114): com.android.settings (true,33751552)
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c29a98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1114): com.android.settings 3 13 0 10
I/ActivityManager(  905): Recipient 2863
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3177 uid=9987 gids={49987}
I/RemoteViews( 1114): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1114): com.android.settings 1 1 10
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@426d7bc8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426d7bc8, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423a6ee0
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42171340
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@426d7bc8
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@426d7bc8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{427c2cd0 u0 ReceiverList{427c2c70 905 system/1000/u0 local:4292d680}}
D/NfcUiccLockService( 3177): -- To check whether previous opened channel needed to be closed ...
I/ActivityManager(  905): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3191 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
D/Process (  905): killProcessQuiet, pid=2706
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2706:com.android.defcontainer/u0a19 (adj 15): empty #17
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 3
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426d7bc8, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423a6ee0
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42171340
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@426d7bc8
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3204 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=2893
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2893:com.htc.android.worldclock/u0a90 (adj 15): empty #17
W/AwContents( 3095): nativeOnDraw failed; clearing to background color.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2893
I/InputMethodManagerService(  905): Disable input method client, pid=1269
W/ResourceType( 3095): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3095): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b05420, mServedView=org.apache.cordova.engine.SystemWebView{41ac7e70 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Enable input method client, pid=3095
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3095): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Recipient 2706
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +667ms
D/PMS     (  905): releaseWL(4295f060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/YouTube ( 3204): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
E/AndroidProtocolHandler( 3095): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3095): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/libc    ( 3204): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3204): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3204): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/JsMessageQueue( 3095): Set native->JS mode to OnlineEventsBridgeMode
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3204/10168)
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3204): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/jxcore_app_log( 3095): JniHelper::setJavaVM(0x4158d048), pthread_self() = 1657658944
D/JX-Cordova( 3095): jxcore cordova android initializing
D/YouTube ( 3204): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3204): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3204): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
W/jxcore-log( 3095): Initializing JXcore engine
W/jxcore-log( 3095): JXcore engine is ready
,W/jxcore-log( 3095): Starting JXcore engine
,D/YouTube ( 3204): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 3204): Registered
,I/MediaRouter( 3204): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (3204/10168)
D/YouTube ( 3204): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3204): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448020190&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3204): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3204): [NET] getaddrinfo-,err=8
D/libc    ( 3204): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3204): [NET] getaddrinfo-, 1
D/libc    ( 3204): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7e3a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3204): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3204): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,D/YouTube ( 3204): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
,D/YouTube ( 3204): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
,D/MediaRouter( 3204): getSelectedRoute
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3204/10168)
D/YouTube ( 3204): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 281
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3204): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3204/10168)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3204/10168)
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/YouTube ( 3204): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,W/jxcore-log( 3095): Platform android
W/jxcore-log( 3095): 
,W/jxcore-log( 3095): Process ARCH arm
W/jxcore-log( 3095): 
,D/YouTube ( 3204): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3204): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3204): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/jxcore-log( 3095): JXcore Cordova bridge is ready!
I/jxcore-log( 3095): 
,W/jxcore-log( 3095): JXcore engine is started
,I/GoogleConversionPing( 3204): Ping responded with response code 200
,E/jxcore-log( 3095): >> HTC-HTC Desire 820
E/jxcore-log( 3095): 
,I/jxcore-log( 3095): Total memory 1964650496
I/jxcore-log( 3095): 
I/jxcore-log( 3095): Free memory 659394560
I/jxcore-log( 3095): 
I/jxcore-log( 3095): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3095): 
,I/jxcore-log( 3095): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3095): 
,I/jxcore-log( 3095): userPath [ 'www' ]
I/jxcore-log( 3095): 
,I/jxcore-log( 3095): Size 720 1184
I/jxcore-log( 3095): 
,I/jxcore-log( 3095): Screen Brightness 142
I/jxcore-log( 3095): 
,E/jxcore-log( 3095): Dummy Error Log.
E/jxcore-log( 3095): 
,W/dalvikvm( 2171): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 2171): Spent 21ms computing apk sha1.
,D/FileApkUtils( 2171): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/GAV2    ( 2848): Thread[GAThread,5,main]: No campaign data found.
,D/DexOptUtils( 2171): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2171): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 2171): Beginning GMS chimera module scan
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/asset   ( 2171): Copying FileAsset 0x652d3db8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
I/GAv4-SVC( 2171): Google Analytics 8.3.01 is starting up.
,W/dalvikvm( 2171): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 2171): Beginning module configuration check
,D/ChimeraCfgMgr( 2171): Module APKs unchanged, check complete
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
E/dalvikvm( 2171): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 2171): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42074850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 2171): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 2171): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
W/dalvikvm( 2171): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [5][0][0]
W/dalvikvm( 2171): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42406bc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42074850): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2171): Checkin interval check for package: unspecified last checkin: 1448018034658 min interval config: 0 actual interval: 2156726
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/GCM     ( 2171): COMPAT: Multi user not supported
D/PMS     (  905): acquireWL(42136b28): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 2171): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1220): DispatchingService.onCreate()
,D/GCM     ( 1342): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 2171): Disabling old GoogleServicesFramework version
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2171, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 2171): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,D/SystemUpdateService( 2171): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
D/PMS     (  905): acquireWL(41c47a28): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2171, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,W/dalvikvm( 2171): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,V/AuthZen ( 2171): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2171, uid=10029, userID:0
,D/PMS     (  905): acquireWL(41c35e28): PARTIAL_WAKE_LOCK  Icing 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
I/SystemUpdateService( 2171): cancelUpdate (empty URL)
,I/SystemUpdateService( 2171): active receiver: disabled
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
,D/AuthZenEventHandler( 2171): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,D/PMS     (  905): releaseWL(41c35e28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2171): Checking schedule, now: 1448020191508 next: 1448540971619
I/CheckinService( 2171): active receiver: disabled
,I/GCoreUlr( 1220): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 2171): onDestroy
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
,D/PMS     (  905): releaseWL(42136b28): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42406bc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 2171): Using Auth Proxy for data requests.
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1220, uid=10029, userID:0
W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2171): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 2171): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,I/AuthZen ( 2171): Fetching signing key...
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/AuthZen ( 2171): Signing key fetched successfully!
,W/BaseAppContext( 2171): Using Auth Proxy for data requests.
,I/GCoreUlr( 1220): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1220): Unbound from all location providers
D/PMS     (  905): acquireWL(4264c238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4264c238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/AuthZenTransactionCache( 2171): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2171): Clearing transaction cache
D/PMS     (  905): releaseWL(41c47a28): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/GCoreUlr( 1220): DispatchingService.onDestroy()
,I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1220): Unbound from all location providers
W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(4295c310): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  905): releaseHCC(4295c880): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
D/PMS     (  905): acquireWL(426a60f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(426a60f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3095): getBuffer is called!!!!
I/jxcore-log( 3095): 
,D/PMS     (  905): acquireWL(425f31e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2171 10029 null
,D/PMS     (  905): acquireWL(42800590): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/PMS     (  905): releaseWL(425f31e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  905): releaseWL(42800590): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,W/Auth    ( 1342): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
D/PMS     (  905): acquireWL(4254ba30): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1342 10029 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): releaseWL(4254ba30): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
I/ActivityManager(  905): Resuming delayed broadcast
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 2171): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1342): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3299 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426a2188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42673a80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
,I/IntentController( 1114): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(426a2188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(425f3bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(425f3bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/dalvikvm( 3299): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3299, uid=10074, userID:0
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 4 times.
,D/Finsky  ( 3299): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3299/10074)
,D/PhoneStatusBar( 1114): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,W/dalvikvm( 3299): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3299): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3299/10074)
,I/IntentController( 1114): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(426baff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42673a80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): releaseWL(426baff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/Finsky  ( 3299): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 3299): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3299): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3299): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3299): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3299): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3299): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/PhoneStatusBar( 1114): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 3299): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3299, uid=10074, userID:0
,D/Volley  ( 3299): [297] DiskBasedCache.clear: Cache cleared.
D/Process (  905): killProcessQuiet, pid=2913
,D/Ads     ( 3299): Skipping gmscore version check
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Volley  ( 3299): [304] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  905): Killing 2913:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/Finsky  ( 3299): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3299): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  905): Recipient 2913
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3299): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  905): Delay finish: com.htc.dotmatrix/.CoverStateReceiver
,D/AutoSetting( 1386): receiver - intent: android.intent.action.USER_PRESENT
,I/ActivityManager(  905): Resuming delayed broadcast
D/Finsky  ( 3299): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/TetherSettings( 3148): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3148): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3148): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3148): Cust_ConnectToPC   : spcsc>false
D/        ( 3148): Cust_ConnectToPC   : IPT>true
D/        ( 3148): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3148): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3148): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3148): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3148): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1386): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3148): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3148): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3148): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3148):  defaultType:0
,D/AutoSetting( 1386): receiver - intent: android.intent.action.SERVICE_STATE
D/PMS     (  905): acquireWL(42854c58): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 1497 10014 null
,D/PMS     (  905): releaseWL(42854c58): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 null
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/WeatherUtility( 1114): can't get weather sync account
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3341 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1114): request cur loc, but there is no sys cur
,D/browser ( 3341): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3341): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3341): Loading: swewebviewchromium
,I/GAV2    ( 2954): Thread[GAThread,5,main]: No campaign data found.
,I/LibraryLoader( 3341): Time to load native libraries: 35 ms (timestamps 2608-2643)
,I/LibraryLoader( 3341): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3341): Initializing chromium process, renderers=9
I/LibraryLoader( 3341): Expected native library version number "",actual native library version number ""
,I/chromium( 3341): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/PMS     (  905): releaseWL(42488288): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3341): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3341): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3341): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3341): Local Branch: 
I/Adreno-EGL( 3341): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3341): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3341):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=2925
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 2925:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1293): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/SIMStateChangeReceiver( 1497): SIM state: ABSENT
I/SIMStateChangeReceiver( 1497): phoneType = 0
,I/SIMStateChangeReceiver( 1497): remove notification
I/ActivityManager(  905): Recipient 2925
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3382 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3394 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2954
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2954:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2954
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2743): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2743): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2743): onReceive()
D/ExchangePolicystatus( 2743): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2743): onReceive(): else
,D/Process (  905): killProcessQuiet, pid=2989
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1240): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  905): Killing 2989:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2989
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2171, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=2171, uid=10029, userID:0
,D/WearableService( 1220): callingUid 10029, callindPid: 1220
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
E/MDM     ( 1220): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2171): Restart initialization of location
,D/AccTypeManager( 3394): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  905): Delay finish: com.google.android.gms/.nearby.messages.NearbyMessagesBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,W/AccTypeManager( 3394): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3394): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1342): location=null
D/PMS     (  905): acquireWL(42672ad8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42672ad8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
,V/GmsCoreStatsServiceLauncher( 2171): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
V/AlarmManager(  905): sending alarm PendingIntent{421a8c28: PendingIntentRecord{41fb2130 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=47008, Int=259200000
V/AlarmManager(  905): sending alarm PendingIntent{41da1840: PendingIntentRecord{424805f0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49697, Int=0
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3418 uid=10041 gids={50041}
,E/ExternalAccountType( 3394): Unsupported attribute readOnly
,D/AccTypeManager( 3394): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3394): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3394): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  905): killProcessQuiet, pid=2939
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3431 uid=10078 gids={50078}
I/ActivityManager(  905): Killing 2939:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/ExternalAccountType( 3394): Unsupported attribute readOnly
,D/SMSBackup( 3431): Got a database change event
,D/Process (  905): killProcessQuiet, pid=3013
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3443 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  905): Killing 3013:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/CalendarApplication( 3443): onCreate
D/ProviderChangeReceiver( 3443): ---------------------------------------------------
,D/ProviderChangeReceiver( 3443): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3443): start to updateAlertNotification!
W/ContextImpl( 3109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3458 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/AlertService( 3443): No fired or scheduled alerts
D/HtcAlertUtils( 3443): -- cancelReminderNotification --
D/HtcAlertUtils( 3443): broadcastExistReminder!
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  905): killProcessQuiet, pid=3051
,I/ActivityManager(  905): Killing 3051:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2939
,I/ActivityManager(  905): Recipient 3051
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3013
,I/MusicStore( 3458): Database version: 95
,W/ContextImpl( 3458): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3458): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3458): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3458): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3458): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3458, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 3458): Registered
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
I/MediaRouter( 3458): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (3458/10154)
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2393/10021)
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3480 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 3458): getSelectedRoute
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3458/10154)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3458, uid=10154, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42634e98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/Process (  905): killProcessQuiet, pid=3066
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 3066:com.htc.htccupd/u0a17 (adj 15): empty #17
D/PMS     (  905): releaseWL(42634e98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Recipient 3066
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3480): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3480): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3480): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3480): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3480): Preparing secondary program dexes.
V/DexLibLoader( 3480): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3480): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3480): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3480): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3480): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3480): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3480): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 3480): Dex already copied
D/OdexVerifier( 3480): Odex verification is skipped.
,V/DexLibLoader( 3480): Creating class loader
,V/DexLibLoader( 3480): Finished creating class loader
,V/DexLibLoader( 3480): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3480): Dex already copied
D/OdexVerifier( 3480): Odex verification is skipped.
,V/DexLibLoader( 3480): Creating class loader
,V/DexLibLoader( 3480): Finished creating class loader
,V/DexLibLoader( 3480): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3480): Dex already copied
D/OdexVerifier( 3480): Odex verification is skipped.
,V/DexLibLoader( 3480): Creating class loader
,V/DexLibLoader( 3480): Finished creating class loader
,V/DexLibLoader( 3480): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3480): Dex already copied
D/OdexVerifier( 3480): Odex verification is skipped.
,V/DexLibLoader( 3480): Creating class loader
,V/DexLibLoader( 3480): Finished creating class loader
,V/DexLibLoader( 3480): Verifying classes from secondary dexes.
,D/DexLibLoader( 3480): DexLibLoader.ensureDexLoaded took 131 ms
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/dalvikvm( 3480): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3480): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3480): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3480): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3480): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3480): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3480): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3081
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3081:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3081
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1386): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3500 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1386/10055)
D/AutoSetting( 1386): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1386): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1386): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1386): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1386): service - handleMessage() setting current location null
,D/AutoSetting( 1386): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1386): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1386/10055)
,D/MobileConnectivityChangeReceiver( 3500): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3500): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3500): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3500): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3515 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3124
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/fb4a(:<default>):UserScope( 3480): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  905): Killing 3124:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3500/10079)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3480): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3500/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3500/10079)
I/ActivityManager(  905): Recipient 3124
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(426cba70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426e3728): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):UserScope( 3480): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/CheckinService( 2171): Checkin interval check for package: unspecified last checkin: 1448018034658 min interval config: 0 actual interval: 2161363
I/CheckinService( 2171): Checking schedule, now: 1448020196024 next: 1448018064619
,I/CheckinService( 2171): active receiver: enabled
D/PMS     (  905): releaseWL(426cba70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,I/CheckinService( 2171): Preparing to send checkin request
,I/EventLogService( 2171): Accumulating logs since 1448018985797
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3480): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/Process (  905): killProcessQuiet, pid=3177
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3532 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3177:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,E/dalvikvm( 3480): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3480): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3480): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3480): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3480): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3480): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3480): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3480): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3480): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3480): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3480): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3480): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3480): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3480): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3480): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3480): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3480): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3480): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/CheckinRequestBuilder( 2171): Checkin reason type: 8 attempt count: 1
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@424925a8 mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1362
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2171): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,W/GAV2    ( 3532): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/BluetoothManagerService(  905): Sending off request.
D/BluetoothAdapterState( 1566): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1566): Setting state to 13
I/BluetoothAdapterState( 1566): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1566): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 1566): onBluetoothDisable()
,D/WifiManager( 3095): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
I/BluetoothAdapterState( 1566): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 1566): BTM_SetDiscoverability
I/bt-btm  ( 1566): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1566): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1566): br_edr_supported=0x0
I/bt-btm  ( 1566): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1566): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1566): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1566): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1566): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1566): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1566): BTM_SetConnectability
I/bt-btm  ( 1566): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1566): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1566): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 1566): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1566): adapterPropertyChangedCallback with type:7 len:4
,I/dalvikvm-heap( 3480): Grow heap (frag case) to 9.923MB for 39954-byte allocation
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothAdapterProperties( 1566): Scan Mode:20
E/BTIF_CORE( 1566): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1566): HAL bt_hal_cbacks->wake_state_changed_cb
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/BluetoothAdapterState( 1566): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1566): BTA_JvDeleteRecord
,D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
I/bt-btif ( 1566): BTA_JvDeleteRecord
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btif ( 1566): BTA_JvDeleteRecord
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btif ( 1566): BTA_JvDeleteRecord
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btif ( 1566): BTA_JvDeleteRecord
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btif ( 1566): BTA_JvDeleteRecord
I/bt-btif ( 1566): BTA_JvRfcommStopServer
D/bt-btm  ( 1566): BTM_FreeSCN 
E/BtOppRfcommListener( 1566): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/ActivityManager(  905): Recipient 3177
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: false pid=3095, uid=10396
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  905): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1355
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
,I/bt-btm  ( 1566): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:14
V/BluetoothSapService( 1566): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1566): BTM_SEC_CLR[14]: id 53
,D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1566): BTM_SEC_CLR[15]: id 54
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:12
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 12 -> 13
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1566): BTM_SEC_CLR[16]: id 55
,D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1566): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1566): bta_jv_rfcomm_stop_server
,I/bt-btm  ( 1566): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1566): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:8
,I/bt-btm  ( 1566): Write Extended Inquiry Response to controller
I/bt-btm  ( 1566): Write Extended Inquiry Response to controller
I/bt-btm  ( 1566): Write Extended Inquiry Response to controller
I/bt-btm  ( 1566): Write Extended Inquiry Response to controller
I/bt-btm  ( 1566): BTM_SetDiscoverability
I/bt-btm  ( 1566): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1566): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1566): br_edr_supported=0x0
I/bt-btm  ( 1566): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1566): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1566): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1566): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1566): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1566): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1566): BTM_SetConnectability
I/bt-btm  ( 1566): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1566): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1566): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1566): BTM_IsInquiryActive
I/bt-btm  ( 1566): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1566): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btm  ( 1566): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1566): BTM_FreeSCN 
I/bt-btm  ( 1566): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1566): AVRC_Close handle:0
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1566): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1566): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1566): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1566): GATT_Deregister gatt_if=3
,I/bt-att  ( 1566): GATT_Deregister gatt_if=4
,D/BluetoothRemoteDevices( 1566): Wake lock Aquired
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/PMS     (  905): acquireWL(426b3770): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1566 1002 null
V/BluetoothPbapReceiver( 1566): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,I/IntentController( 1114): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,V/BluetoothPbapReceiver( 1566): ***********state = 13
D/BluetoothMasReceiver( 1566): Bluetooth STATE CHANGED to 13
,V/BluetoothSapReceiver( 1566): SapReceiver onReceive 
V/BluetoothSapReceiver( 1566): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1566):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1566): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(4295d288): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3148 1000 null
W/ContextImpl( 3148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothPbapService( 1566): Pbap Service closeService in
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 3095): ****TEST TOOK:  5089  ms ****
I/jxcore-log( 3095): 
,W/ContextImpl( 3532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 3095): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3095): 
D/PMS     (  905): acquireWL(4262b0b0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1220 10029 null
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/PMS     (  905): releaseWL(4295d288): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1772): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41adc0a8
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): onDeInitialized
D/WirelessDisplayService(  905): getMirrorDisplayStatus:falsecurState:1
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/BluetoothAdapter( 1220): 1104905536: getState(). Returning 13
I/dalvikvm-heap( 3480): Grow heap (frag case) to 10.000MB for 79892-byte allocation
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 0
I/wpa_supplicant( 1132): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423e4940:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/WifiNative-wlan0(  905):    returned true
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42810e90): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3148 1000 null
D/PMS     (  905): acquireWL(4283ec38): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapter( 1220): 1104905536: getState(). Returning 13
I/LocationAgent( 3148): new LocationAgent instance!!
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19643 mDataStallAlarmIntent=PendingIntent{42321678: PendingIntentRecord{4231e208 android broadcastIntent}}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): cancelAllNotification
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3555 uid=10040 gids={50040, 3002, 3001}
D/PMS     (  905): releaseWL(4262b0b0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): getNotificationManager
D/WifiNative-wlan0(  905):    returned null
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/HtcTagManager( 3148): HtcTagManager construction complete
V/BluetoothPbapService( 1566): successfully stopped pbap service
V/BluetoothPbapService( 1566): Pbap Service closeService out
D/WifiStateMachine(  905): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
D/UsbnetStateTracker(  905): isAvailable+-
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 0
I/wpa_supplicant( 1132): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
V/BluetoothSapService( 1566): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1566): state: 13
D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  905): P2pDisablingState
D/WifiP2pService(  905): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): p2p socket connection lost
D/WifiP2pService(  905): P2pDisabledState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/BluetoothAdapter( 1566): 1101884952: getState(). Returning 13
,V/BluetoothSapService( 1566): Stopping SAP server process
,D/WifiNative-wlan0(  905):    returned true
D/BluetoothAdapter( 3148): 1102215288: getState(). Returning 13
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/BluetoothInputDevice( 3148): BluetoothInputDevice()
V/BluetoothSapService( 1566): Sap Service closeSapService in
V/BluetoothSapService( 1566): Close listen Socket : 
V/BluetoothSapService( 1566): Close rfcomm Socket : 
V/BluetoothSapService( 1566): Close sapd  Socket : 
,V/BluetoothSapReceiver( 1566): BluetoothSapReceiver deinit
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3148): 1102215288: getState(). Returning 13
D/BluetoothInputDevice( 3148): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3148): Bluetooth service connected
,W/BluetoothInputDevice( 3148): Proxy not attached to service
D/BluetoothPan( 3148): BluetoothPan()
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  905): set wifi.miracastlock to 0 for disconnect case
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  905): updateConnection
I/WifiDisplayController(  905): mConnectingDevice = null,  mDesiredDevice = null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1772): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1772):  + initPendingRequestAlarm: false, mContext = null, null
V/BluetoothSapService( 1566): successfully stopped Sap service
V/BluetoothSapService( 1566): Sap Service closeSapService out
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1772): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1772):  + mTag.getPrimaryDeviceList() = []
I/BtOppRfcommListener( 1566): stopping Accept Thread
,D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1772): deinit: 0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/BluetoothManagerService(  905): Message: MESSAGE_UNREGISTER_ADAPTER
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/BtOppRfcommListener( 1566): BluetoothSocket listen thread finished
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4295a018:true
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  905): convertEffect before=902
D/HtcEffectManager(  905): convertEffect after=902
D/BluetoothManagerService(  905): Registered receivers: 8
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1342): Read error: ssl=0x64a30160: I/O error during system call, Connection timed out
,I/dalvikvm-heap( 3480): Grow heap (frag case) to 10.082MB for 84664-byte allocation
,D/BluetoothAdapter( 3148): 1102215288: getState(). Returning 13
D/BluetoothPan( 3148): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3148): Bluetooth service connected
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x64a30160: I/O error during system call, Broken pipe
,D/BluetoothMap( 3148): Create BluetoothMap proxy object
I/WifiDisplayController(  905): updateConnection enter step 4
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiP2pService(  905): P2pDisabledState{ when=-4ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/WifiP2pService(  905): DefaultState{ when=-4ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/WifiDisplayController(  905): Failed to set WFD info with reason 2.
,D/PMS     (  905): acquireWL(42414738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1772): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1772): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1772): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1772): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1772): Exit IdleState
D/WifiNative-p2p0(  905): doBoolean: TERMINATE
W/WifiHW  (  905): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1132): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1132): TDLS: Tear down peers
,I/wpa_supplicant( 1132): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiNative-p2p0(  905):    returned true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
,V/BluetoothPbapService( 1566): Pbap Service onDestroy
V/BluetoothPbapService( 1566): Pbap Service closeService in
,V/BluetoothPbapService( 1566): Pbap Service closeService out
,I/QuickSettingBluetooth( 1114): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
V/BluetoothSapService( 1566): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b0f530
V/BluetoothSapService( 1566): Sap Service closeSapService in
V/BluetoothSapService( 1566): Close listen Socket : 
V/BluetoothSapService( 1566): Close rfcomm Socket : 
V/BluetoothSapService( 1566): Close sapd  Socket : 
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PhoneStatusBar( 1114): removeIcon slot=bluetooth index=12 viewIndex=0
D/libc    (  363): [NET] entry_id:4   entry:0xb870c2d8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb870c0f8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb870c428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb870c4f0  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/BluetoothSapService( 1566): Sap Service closeSapService out
,V/BluetoothSapService( 1566): ***onDestroyed***
I/dalvikvm-heap( 3480): Grow heap (frag case) to 10.094MB for 28144-byte allocation
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(425ad230): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1114): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1132): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1132): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1132): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7302bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1132):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1132): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1132): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2462
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WIFI_ICON( 1114): updateWifiState: WIFI_STATE_CHANGED disabled
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1342/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3500/10079)
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1132): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/PMS     (  905): releaseWL(425ad230): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1114): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,W/bt-btif ( 1566): ag scb idx 1 not allocated
,W/bt-btif ( 1566): ag scb idx 2 not allocated
E/bt-btif ( 1566): BTA AG is already disabled, ignoring ...
D/BluetoothManagerService(  905): registerStateChangeCallback+
,W/bt-l2cap( 1566): L2CAP - PSM: 0x0019 not found for deregistration
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/bt-l2cap( 1566): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1566): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1566): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1566): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1566): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  905): Registered receivers: 9
,E/BluetoothMap( 3148): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  905): registerStateChangeCallback+
I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3575 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  905): sending alarm PendingIntent{42380b38: PendingIntentRecord{4255e850 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54027, Int=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 10
,D/BluetoothSap( 3148): BluetoothSap() call bindService
,D/BluetoothPbap( 3148): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 11
D/BluetoothAdapter( 3148): 1102215288: getState(). Returning 13
D/BluetoothPbap( 3148): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3148): Bluetooth service connected
,D/LocalBluetoothProfileManager( 3148): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3148): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
,D/DockEventReceiver( 3148): finishStartingService: stopping service
,E/bt_userial_mct( 1566): userial_close userial_thread_created userial_running is 1 
D/PMS     (  905): releaseWL(42414738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
,D/WISPrService( 3148): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3148): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/HtcBtWidget_BTWidgetProvider( 3555): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3555): updateWidget(context) for widget: 
D/PMS     (  905): releaseWL(42810e90): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/WifiService(  905): New client listening to asynchronous messages
D/WISPrService( 3148): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3148): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1566): Shutdown
,D/BluetoothMasReceiver( 1566): Bluetooth STATE CHANGED to 13
,D/Process (  905): killProcessQuiet, pid=3191
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1772): Received state change = 13
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1772): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41adc0a8
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): deinitLeServices: null
I/ActivityManager(  905): Killing 3191:com.android.smith/u0a163 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3532/10151)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3191
,V/WebViewChromiumFactoryProvider( 3532): Binding Chromium to main looper Looper (main, tid 1) {41ab66d0}
,I/LibraryLoader( 3532): Expected native library version number "",actual native library version number ""
,I/chromium( 3532): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3532): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(427cba40): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/dalvikvm-heap( 3480): Grow heap (frag case) to 10.261MB for 75760-byte allocation
D/PMS     (  905): acquireWL(427cb890): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(427cba40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3597 uid=10091 gids={50091, 3003, 5012}
,E/AudioManagerAndroid( 3532): BLUETOOTH permission is missing!
D/WifiService(  905): New client listening to asynchronous messages
,D/Process (  905): killProcessQuiet, pid=3204
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426b7f88 u0 ReceiverList{4201b270 3480 com.facebook.katana/10027/u0 remote:422c8df0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426b7f88 u0 ReceiverList{4201b270 3480 com.facebook.katana/10027/u0 remote:422c8df0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4268b208 u0 ReceiverList{42003f08 3480 com.facebook.katana/10027/u0 remote:422258d8}}
,I/ActivityManager(  905): Killing 3204:com.google.android.youtube/u0a168 (adj 15): empty #17
D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Adreno-EGL( 3532): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3532): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3532): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3532): Local Branch: 
I/Adreno-EGL( 3532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3532): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3532):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,E/wpa_supplicant( 1132): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1132): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1132): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,I/NSApplication( 3532): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3532/10151)
,D/MdScBoot( 3575): [7b8.1.] 30@-124925 -> 40@-124956
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3532/10151)
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3626 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3299
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/PMS     (  905): acquireWL(426a2090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Killing 3299:com.android.vending/u0a74 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=3341
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  905): killProcessQuiet, pid=3382
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2171/10029)
D/PMS     (  905): releaseWL(426a2090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Killing 3341:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
I/ActivityManager(  905): Killing 3382:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3204
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.youtube (pid 3204): Died!
,I/ActivityManager(  905): Recipient 3382
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3299
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=0, operstate=6
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1132): nl80211: Unsubscribe mgmt frames handle 0xb7303718 (mode change)
I/wpa_supplicant( 1132): htc_wext_command_deinit +
I/wpa_supplicant( 1132): htc_wext_command_deinit -
E/wpa_supplicant( 1132): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1132): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1132): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1132): TDLS: Tear down peers
I/wpa_supplicant( 1132): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x62ae5930
I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x62ae5468
,W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,D/WifiStateMachine(  905): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  905):    returned false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3341
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/IntentController( 1114): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  905): WIFI Trun OFF
D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/Settings( 1220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
E/WifiStateMachine(  905): [MLHD] Error! unhandled message 6 { when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1114): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  905): acquireWL(423caef0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3148): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3148): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3480): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/dalvikvm( 1342): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.account.b.d.a
W/dalvikvm( 1342): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/account/b/d;
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3480): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/QuickSettingWifi( 1114): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
W/dalvikvm( 1342): VFY: unable to resolve virtual method 24: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 23: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3648 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/CustomizationManager( 3568): ====startRecUseTime====
D/htc.customization.log.level( 3568):  is 
,W/CustomizationLogLevel( 3568): Level value is invalid, use default level 2
,I/bt-btif ( 1566): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1566): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1566): Received stop request...Stopping profile...
D/BluetoothHeadset( 1240): Proxy object disconnected
D/BluetoothPhoneService( 1240): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1240): Proxy object disconnected
D/BluetoothHeadset(  905): Proxy object disconnected
D/BluetoothHeadset( 1114): Proxy object disconnected
I/QuickSettingMiniLite( 1114): btListener.disconnect:HEADSET
W/dalvikvm( 3648): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/A2dpService( 1566): Received stop request...Stopping profile...
D/A2dpStateMachine( 1566): doQuit
D/A2dpStateMachine( 1566): Exit Disconnected: -1
D/BluetoothA2dp(  905): Proxy object disconnected
D/BluetoothAdapterState( 1566): Stopping profile services that were post enabled
W/dalvikvm( 3648): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/HidService( 1566): Received stop request...Stopping profile...
I/MultiDex( 3648): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3648): install
,I/MultiDex( 3648): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,D/HealthService( 1566): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1566): Profile still running: com.android.bluetooth.hdp.HealthService
,I/MultiDex( 3648): loading existing secondary dex files
,I/MultiDex( 3648): load found 3 secondary dex files
W/BluetoothHeadsetServiceJni( 1566): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1566): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1566): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 1566): Received stop request...Stopping profile...
D/PanService( 1566): stop
,D/PanService( 1566): stop: mTetherAc send disconnect
,I/MultiDex( 3648): install done
,D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  905): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  905): BluetoothPAN Proxy object disconnected
,D/A2dpStateMachine( 1566): cleanup
,D/Avrcp   ( 1566): Unregistering previous receiver
,D/BtGatt.DebugUtils( 1566): handleDebugAction() action=null
D/BtGatt.GattService( 1566): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1566): stop()
D/BluetoothAdapterService( 1566): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1566): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1566): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1566): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1566): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1566): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1566): Cleaning up Bluetooth Health object
D/PanService( 1566): CMD_CHANNEL_DISCONNECTED
D/PanService( 1566): CMD_CHANNEL_DISCONNECTED call disconnected
,D/BluetoothAdapterService( 1566): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1566): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1566): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 1566): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1566): Setting state to 10
I/BluetoothAdapterState( 1566): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1566): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 1566): Entering OffState
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1114): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
D/BluetoothA2dp(  905): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  905): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3148): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3148): 
E/BluetoothPbap( 3148): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41b3c308
E/BluetoothPbap( 3148): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3148): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3148): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3148): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3148): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3148): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3148): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothPan( 3148): 
E/BluetoothPan( 3148): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41b34e70
E/BluetoothPan( 3148): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3148): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3148): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3148): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3148): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3148): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3148): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothSap( 3148): onBluetoothStateChange on: false
,D/BluetoothInputDevice( 3148): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3148): 
E/BluetoothInputDevice( 3148): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41b338d8
E/BluetoothInputDevice( 3148): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3148): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3148): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3148): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3148): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3148): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3148): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothMap( 3148): onBluetoothStateChange: up=false
W/dalvikvm( 3648): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
E/BluetoothMap( 3148): 
E/BluetoothMap( 3148): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b361f0
E/BluetoothMap( 3148): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3148): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3148): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3148): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3148): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3148): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3148): 	at dalvik.system.NativeStart.run(Native Method)
W/dalvikvm( 3648): VFY: unable to resolve instance field 46
,D/PMS     (  905): acquireWL(425ae4a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3626 10160 null
W/dalvikvm( 3648): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/BluetoothManagerService(  905): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1342): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cb57c0
D/BluetoothAdapter( 1342): onBluetoothServiceDown: done
D/BluetoothAdapter( 1220): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41dba1b0
D/BluetoothDevice( 1220): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1220): onBluetoothServiceDown: done
D/BluetoothAdapter( 1114): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ed0938
D/BluetoothAdapter( 1114): onBluetoothServiceDown: done
D/BluetoothAdapter( 3095): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ad15b8
D/BluetoothAdapter( 3095): onBluetoothServiceDown: done
D/BluetoothAdapter( 1253): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b88720
D/BluetoothAdapter( 1253): onBluetoothServiceDown: done
D/BluetoothAdapter(  905): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424925a8
D/BluetoothAdapter(  905): onBluetoothServiceDown: done
D/BluetoothAdapter( 1240): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d000a8
D/BluetoothAdapter( 1240): onBluetoothServiceDown: done
D/BluetoothAdapter( 1566): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ad5288
D/BluetoothDevice( 1566): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1566): onBluetoothServiceDown: done
D/BluetoothAdapter( 1772): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41adc978
D/BluetoothAdapter( 1772): onBluetoothServiceDown: done
D/BluetoothAdapter( 3148): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b282e0
D/BluetoothAdapter( 3148): onBluetoothServiceDown: done
,D/BluetoothManagerService(  905): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@424925a8 mBinding = false
,D/BluetoothManagerService(  905): Sending unbind request.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 13 -> 10
,V/JNIHelp ( 3648): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/IntentController( 1114): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NfcHandover( 1253): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/BluetoothAdapterService( 1566): Cleaning up adapter native....
,I/bt-btif ( 1566): HAL bt_hal_cbacks->thread_evt_cb
,D/BluetoothAdapterService( 1566): Done cleaning up adapter native....
,D/BluetoothAdapterService(1101866776)( 1566): ****onDestroy()********
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
D/PMS     (  905): releaseWL(426b3770): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
D/PMS     (  905): acquireWL(42815ca8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3626 10160 null
D/LocalBluetoothProfileManager( 3148): setBluetoothStateOff
D/HtcTagManager( 3148): stopProxy
W/BluetoothEventManager( 3148): unregister mProfileBroadcastReceiver fail
D/BluetoothAdapter( 1220): 1104905536: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1220): 1104905536: getState() :  mService = null. Returning STATE_OFF
,D/TetherPref( 3148): persistRestoreBluetoothState false
D/PMS     (  905): acquireWL(425ec038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1220 10029 null
D/PMS     (  905): releaseWL(425ae4a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/PMS     (  905): releaseWL(425ec038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/BtGatt.GattService( 1566): cleanup()
W/bt-btif ( 1566): GATTC Module not enabled/already disabled
W/bt-btif ( 1566): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 1566): Bluetooth STATE CHANGED to 10
D/PMS     (  905): acquireWL(4295f898): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3148 1000 null
,W/ContextImpl( 3148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothMasService( 1566): onDestroy: mIsEmailEnabled: true
,D/CustomizationManager( 3568):  Read ACC file spent 0.084 (s)
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 3568): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3568): Parsing tag item name = HTC__031
,D/HtcBtWidget_BTWidgetProvider( 3555): onBTStateChanged() for widget: 
V/CustomizationCIDLoader( 3568): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3568): Parsing tag category name = system
,D/DockEventReceiver( 3148): finishStartingService: stopping service
,I/CustomizationCIDLoader( 3568): Parsing tag category name = application
I/CustomizationCIDLoader( 3568): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3568): Parsing tag category name = AutomotiveHome
D/HtcBtWidget_BTWidgetProvider( 3555): updateWidget(context) for widget: 
,I/CustomizationCIDLoader( 3568): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3568): Parsing tag category name = ACC
D/PMS     (  905): releaseWL(4295f898): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  905): acquireWL(426d5478): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3148 1000 null
I/CustomizationCIDLoader( 3568): Parsing tag category name = Settings
D/CustomizationManager( 3568):  Read CID file spent 0.130 (s)
D/CustomizationManager( 3568):  All configurations done spent 0.130 (s)
W/BluetoothHeadset( 1114): Proxy not attached to service
,I/QuickSettingMiniLite( 1114): updateLiteState:no connect device!
W/HtcNativeFlag( 3568): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3568): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3568): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3568): Fail to get flag for type 'language', use default value: -1
D/PMS     (  905): releaseWL(426d5478): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1566): Bluetooth STATE CHANGED to 10
,D/BluetoothAdapter( 1114): 1104790904: getState() :  mService = null. Returning STATE_OFF
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1772): Received state change = 10
,I/QuickSettingBluetooth( 1114): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4259c860:true
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/LocationAgent( 3109): new LocationAgent instance!!
D/HtcTagManager( 3109): HtcTagManager construction complete
I/iu.SyncManager( 2171): SYNC; picasa accounts
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3109): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3109): BluetoothInputDevice(): Fake return onServiceConnected
D/BluetoothManagerService(  905): Registered receivers: 12
D/HidProfile( 3109): Bluetooth service connected
W/BluetoothInputDevice( 3109): Proxy not attached to service
D/BluetoothPan( 3109): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothPan( 3109): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3109): Bluetooth service connected
D/BluetoothMap( 3109): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
,E/BluetoothMap( 3109): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothSap( 3109): BluetoothSap() call bindService
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/PMS     (  905): releaseWL(42815ca8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  905): Killing 3394:com.htc.contacts/u0a44 (adj 15): empty #17
D/BluetoothManagerService(  905): Registered receivers: 15
D/Process (  905): killProcessQuiet, pid=3394
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/NetworkLogImpl( 2171): Loaded NetworkSpeedPredictor
,D/BluetoothPbap( 3109): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  905): Registered receivers: 16
D/BluetoothPbap( 3109): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3109): Bluetooth service connected
D/LocalBluetoothProfileManager( 3109): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3109): 1101973888: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3109): setBluetoothStateOff
,D/HtcTagManager( 3109): stopProxy
,W/BluetoothEventManager( 3109): unregister mProfileBroadcastReceiver fail
,I/ProviderInstaller( 3648): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
W/ContextImpl( 3109): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,D/Process (  905): killProcessQuiet, pid=2743
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  905): Killing 2743:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=3568, uid=2000 user=0
,W/dalvikvm( 3648): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 3648): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,D/AlertReceiver( 3443): beginStartingService
,W/dalvikvm( 3648): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 3648): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
D/Process (  905): killProcessQuiet, pid=3095
W/dalvikvm( 3648): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,W/dalvikvm( 3648): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/dalvikvm( 3648): Link of class 'Lcom/google/android/gms/common/h/c;' failed
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/PMS     (  905): acquireWL(426974d0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3443 10013 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  905): Killing 3095:com.example.hello/u0a396 (adj 0): stop com.example.hello
,W/ActivityManager(  905): Force removing ActivityRecord{425bf508 u0 com.example.hello/.MainActivity t2}: app died, no saved state
W/asset   (  905): Copying FileAsset 0x6377f0e0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 5 times.
,W/PackageSettings(  905): Skipping PackageSetting{4218c798 com.test.thalitest/10389} due to missing metadata
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  905): WIN DEATH: Window{4264f908 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Recipient 3394
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2743
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,D/NativeLibraryUtils( 3648): Install completed successfully. count=13 extracted=0
D/PMS     (  905): acquireWL(427c3598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(427c3598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1269): -onResume
,I/ConnectivityHelper( 1269): [getCurrentConnectionType] no network connection
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1269/10076)
D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/cutils-trace( 3568): Error opening trace file: No such file or directory (2)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
D/AlertService( 3443): start to updateAlertNotification!
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/dalvikvm-heap( 3626): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  371): CdmEngine::OpenSession
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  905):   Scheme: "mmsto"
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1324): Unsupported attribute readOnly
,W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3095 uid 10396
I/InputMethodManagerService(  905): Enable input method client, pid=1269
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2738511779
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
D/AlertService( 3443): No fired or scheduled alerts
,D/HtcAlertUtils( 3443): -- cancelReminderNotification --
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3458/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3500/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1550/10029)
,I/WVCdm   (  371): CdmEngine::CloseSession
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/HtcAlertUtils( 3443): broadcastExistReminder!
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3694 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(426974d0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,W/Netd    (  363): No subsystem found in netlink event
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
,W/AlertReceiver( 3443): stopSelfResult true
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
V/Tethering(  905): remove iface:wlan0
D/Tethering(  905): interfaceRemoved wlan0
W/WeatherRequest( 1114): request cur loc, but there is no sys cur
,E/Tethering(  905): attempting to remove unknown iface (wlan0), ignoring
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3710 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3694): can't get weather sync account
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,D/PMS     (  905): acquireWL(4293a598): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3710 10071 null
,D/PMS     (  905): acquireWL(4265c9f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3710 10071 null
,D/PMS     (  905): releaseWL(4293a598): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3725 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3710): update TASK shortcut>
W/WeatherRequest( 3694): request cur loc, but there is no sys cur
W/Settings( 3694): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SensorManager(  905): mEventCount = 300
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 12 17
,I/TodoTaskNotifyService( 3710): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/TodoTaskNotifyService( 3710): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/WorldClock.Global( 3725): isHtcDevice = true
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  905): releaseWL(4265c9f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/WorldClock.Global( 3725): isHtcDevice = true
,W/NotifyReceiver( 3710): stopSelfResult true
W/ContextImpl( 3109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3725): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3725): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3725): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1114): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3741 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/SQLiteLog( 1497): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1497): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.calendar/databases/calendar.db, handle = 0x5c9cbcd8
,E/DatabaseUtils( 1497): Writing exception to parcel
E/DatabaseUtils( 1497): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DatabaseUtils( 1497): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DatabaseUtils( 1497): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1642)
E/DatabaseUtils( 1497): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1355)
E/DatabaseUtils( 1497): 	at com.android.providers.calendar.HtcFilterImpl_google.do_Query_INSTANCES(HtcFilterImpl_google.java:219)
E/DatabaseUtils( 1497): 	at com.android.providers.calendar.HtcFilterImpl_google.handle_Query(HtcFilterImpl_google.java:62)
E/DatabaseUtils( 1497): 	at com.android.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:126)
E/DatabaseUtils( 1497): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DatabaseUtils( 1497): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DatabaseUtils( 1497): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/DatabaseUtils( 1497): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 1497): 	at dalvik.system.NativeStart.run(Native Method)
,W/dalvikvm( 3109): threadid=11: thread exiting with uncaught exception (group=0x41685e30)
E/AndroidRuntime( 3109): FATAL EXCEPTION: IntentService[HtcDndCommandService]
E/AndroidRuntime( 3109): Process: com.android.settings:remote, PID: 3109
E/AndroidRuntime( 3109): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3109): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 3109): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 3109): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:463)
E/AndroidRuntime( 3109): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/AndroidRuntime( 3109): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/AndroidRuntime( 3109): 	at com.android.settings.framework.core.sound.HtcDndUtils.getCalendarEvent(HtcDndUtils.java:310)
E/AndroidRuntime( 3109): 	at com.android.settings.framework.app.HtcDndCommandService.addCalendarTimeSlot(HtcDndCommandService.java:452)
E/AndroidRuntime( 3109): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleSlotData(HtcDndCommandService.java:511)
E/AndroidRuntime( 3109): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleEventTimer(HtcDndCommandService.java:530)
E/AndroidRuntime( 3109): 	at com.android.settings.framework.app.HtcDndCommandService.onHandleIntent(HtcDndCommandService.java:142)
E/AndroidRuntime( 3109): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3109): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3109): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  905): remove iface:p2p0
D/Tethering(  905): interfaceRemoved p2p0
,E/Tethering(  905): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,W/PackageManager(  905): Unable to load service info ResolveInfo{42623468 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.android.settings:remote
,D/Process (  905): killProcessQuiet, pid=3418
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  905): Killing 3418:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3418
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TimeService( 3741): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448020197813
,D/Process (  905): killProcessQuiet, pid=3431
,I/ActivityManager(  905): Killing 3431:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Recipient 3431
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4262f1f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2171 10029 null
,D/PMS     (  905): acquireWL(427f6a88): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426d6aa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426d6aa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2171): Checkin interval check for package: unspecified last checkin: 1448018034658 min interval config: 0 actual interval: 2163187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
D/PMS     (  905): releaseWL(4262f1f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  905): releaseWL(427f6a88): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
,E/SQLiteDatabase( 1342): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1342): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1342): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1342): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1342): 	at com.google.android.gms.playlog.store.d.b(SourceFile:280)
E/SQLiteDatabase( 1342): 	at com.google.android.gms.playlog.store.r.a(SourceFile:475)
E/SQLiteDatabase( 1342): 	at com.google.android.gms.playlog.service.WallClockChangedReceiver.onReceive(SourceFile:24)
E/SQLiteDatabase( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 1342): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 1342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 1342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1342): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 1342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 1342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 1342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 1342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 1342): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 1342): Couldn't open playlog.db for writing (will try read-only):
E/SQLiteOpenHelper( 1342): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1342): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1342): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1342): 	at com.google.android.gms.playlog.store.d.b(SourceFile:280)
E/SQLiteOpenHelper( 1342): 	at com.google.android.gms.playlog.store.r.a(SourceFile:475)
E/SQLiteOpenHelper( 1342): 	at com.google.android.gms.playlog.service.WallClockChangedReceiver.onReceive(SourceFile:24)
E/SQLiteOpenHelper( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteOpenHelper( 1342): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteOpenHelper( 1342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteOpenHelper( 1342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1342): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 1342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 1342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 1342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 1342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 1342): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 1342): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 1342): (14) os_unix.c:28969: (30) open(/data/data/com.google.android.gms/databases/playlog.db-shm) - 
E/SQLiteLog( 1342): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 1342): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.google.android.gms/databases/playlog.db, handle = 0x6641c140
I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3694): can't get weather sync account
,W/WeatherRequest( 3694): request cur loc, but there is no sys cur
,W/Settings( 3694): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 6 17
,E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448020197928.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/PMS     (  905): acquireWL(425bbd68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  905): releaseWL(425bbd68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=355245102
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,W/fb4a(:<default>):UserScope( 3480): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 3480): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8,
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
I/WVCdm   (  371): CdmEngine::CloseSession
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
W/Settings( 3648): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
W/FileUtils( 3648): Failed to chmod(/data/data/com.google.android.gms/app_fb): libcore.io.ErrnoException: chmod failed: ENOENT (No such file or directory)
W/FileUtils( 3648): Failed to chmod(/data/data/com.google.android.gms/app_fb): libcore.io.ErrnoException: chmod failed: ENOENT (No such file or directory)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (3648/10029)
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,I/CheckinRequestBuilder( 2171): Classify the device as Phone.
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
E/fb4a(:<default>):LocalFbBroadcastManager( 3480): Called registerBroadcastReceiver twice.
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
D/libc    ( 2171): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2171): [NET] getaddrinfo-,err=8
D/libc    ( 2171): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2171): [NET] getaddrinfo-, 1
D/libc    ( 2171): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b91a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET]Querying server xid =b91a (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  363): [NET]res_nsend:ECONNREFUSED
D/libc    (  363): [NET] -----res_nsend exit-1: xid=b91a, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2171): [NET] getaddrinfo_proxy-
E/CheckinTask( 2171): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
E/SharedPreferencesImpl( 2171): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
I/CheckinService( 2171): Checking schedule, now: 1448020198458 next: 1448020208455
I/CheckinService( 2171): active receiver: disabled
F/PackageManager(  905): Unable to backup user packages state file, current changes will be lost at reboot
E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1448020198460.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  905): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  905): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  905): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  905): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  905): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  905): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  905): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:12243)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:12090)
E/ErrorReport(  905): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1067)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  905): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  905): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 18 more
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024509
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024515
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028463
,D/PMS     (  905): releaseWL(426e3728): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3480/10027)
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,W/dalvikvm( 3480): threadid=19: thread exiting with uncaught exception (group=0x41685e30)
,E/ACRA    ( 3480): ACRA caught a SQLiteDiskIOException exception for com.facebook.katana. Building report.
E/fb4a(:<default>):ACRA( 3480): Handling exception for crash
E/fb4a(:<default>):ACRA( 3480): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/fb4a(:<default>):ACRA( 3480): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesDB$PreferenceDbTransaction.c(FbSharedPreferencesDB.java:229)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:125)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:59)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.content.AbstractContentProvider.applyBatch(AbstractContentProvider.java:270)
E/fb4a(:<default>):ACRA( 3480): 	at android.content.ContentProvider$Transport.applyBatch(ContentProvider.java:272)
E/fb4a(:<default>):ACRA( 3480): 	at android.content.ContentProviderClient.applyBatch(ContentProviderClient.java:377)
E/fb4a(:<default>):ACRA( 3480): 	at android.content.ContentResolver.applyBatch(ContentResolver.java:1250)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:886)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.i(FbSharedPreferencesImpl.java:771)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.c(FbSharedPreferencesImpl.java:89)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl$4.run(FbSharedPreferencesImpl.java:746)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.common.executors.SerialExecutorServiceImpl$Worker.run(SerialExecutorServiceImpl.java:59)
E/fb4a(:<default>):ACRA( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/fb4a(:<default>):ACRA( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/fb4a(:<default>):ACRA( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/fb4a(:<default>):ACRA( 3480): 	at java.lang.Thread.run(Thread.java:864)
,D/ACRA    ( 3480): Generating report file for crash
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
,E/ACRA    ( 3480): An error occurred while creating the report file ...
E/ACRA    ( 3480): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_acra-reports/1448020198655-SQLiteDiskIOException-1698515.temp_stacktrace: open failed: EROFS (Read-only file system)
E/ACRA    ( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ACRA    ( 3480): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
E/ACRA    ( 3480): 	at org.acra.ErrorReporter.handleExceptionInternal(ErrorReporter.java:1249)
E/ACRA    ( 3480): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1167)
E/ACRA    ( 3480): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1152)
E/ACRA    ( 3480): 	at org.acra.ErrorReporter.uncaughtException(ErrorReporter.java:999)
E/ACRA    ( 3480): 	at com.facebook.common.errorreporting.memory.MemoryDumpHandler.uncaughtException(MemoryDumpHandler.java:113)
E/ACRA    ( 3480): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/ACRA    ( 3480): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/ACRA    ( 3480): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ACRA    ( 3480): 	at libcore.io.Posix.open(Native Method)
E/ACRA    ( 3480): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ACRA    ( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ACRA    ( 3480): 	... 8 more
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,E/SQLiteDatabase( 3480): Failed to open database '/data/data/com.facebook.katana/databases/contacts_db2'.
E/SQLiteDatabase( 3480): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3480): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3480): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3480): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3480): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.i(AdvancedAbstractDatabaseSupplier.java:59)
E/SQLiteDatabase( 3480): 	at com.facebook.database.advancedsupplier.AdvancedAbstractDatabaseSupplier.c(AdvancedAbstractDatabaseSupplier.java:50)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider$ContactsTable.a(FbContactsContentProvider.java:194)
E/SQLiteDatabase( 3480): 	at com.facebook.database.provider.AbstractContentProviderTable.a(AbstractContentProviderTable.java:32)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.data.FbContactsContentProvider.a(FbContactsContentProvider.java:158)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3480): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3480): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3480): 	at com.facebook.contacts.iterator.ContactCursors.a(ContactCursors.java:140)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.ContactPresenceIterators.a(ContactPresenceIterators.java:38)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.m(PresenceManager.java:528)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.l(PresenceManager.java:524)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager.f(PresenceManager.java:83)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.a(PresenceManager.java:504)
E/SQLiteDatabase( 3480): 	at com.facebook.presence.PresenceManager$11.call(PresenceManager.java:501)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecuto,r.java:1112)
E/SQLiteDatabase( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3480): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3480): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 3480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3480): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64246dc8
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b48bd0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +

```
