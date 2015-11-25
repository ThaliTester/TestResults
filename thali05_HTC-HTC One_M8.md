#### Test 503880194bce128_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of main
E/SQLiteLog( 3520): (283) recovered 247 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/MediaProvider( 3520): bindService() MTP Service Connection.
D/MtpReceiver( 3520): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3520): [MTP][handleUsbState]-
D/MtpReceiver( 3520): [MTP][handleMessage]-
--------- beginning of system
I/ActivityManager(  907): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3578 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/MtpService( 3520): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpService( 3520): addStorageInternal without MtpServer
D/MtpService( 3520): [MTP][onCreate]-
I/ActionCombine( 3520): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/MtpService( 3520): [MTP] startForeground
D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 3520): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3520): TotalSize=1867208,MediaCacheLimit=6000
D/MtpService( 3520): starting MTP server in MTP mode
D/MtpService( 3520): addStorageInternal 65537 /storage/emulated/0
I/RemoteViews( 1122): apply : com.android.providers.media 0 7 1 36
D/PMS     (  907): acquireWL(18926e9f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1953 10025 null
D/MtpService( 3520): [checkStorageState] Storage state - mounted
D/MtpDatabase( 3520): [MTP][addStorage] iHostType =2
D/MtpService( 3520): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
I/RemoteViews( 1122): apply : com.android.providers.media 0 7 1 51
D/NGFLanguageMgr( 3433): LanguageFromSystem: language:en  country:gb
D/NGFLanguageMgr( 3433): language package name = preload_package
I/iu.UploadsManager( 1953): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
D/PluginProvider( 1412): apply Batch success
W/HtcWrapAdjustableCursorFactory( 3578): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 3578): onCreate
V/GetPrviateResource( 3578): GetPrviateResource
D/NGFService( 3433): load vocalizer language = British English
E/NGFService( 3433): registerObserver
I/iu.UploadsManager( 1953): End new media; added: 0, uploading: 0, time: 35 ms
D/NGFService( 3433): onCreate: Battery Level Remaining: 100%
D/NGFService( 3433): onStartCommand(): service start
D/NGFService( 3433): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3433): QuickCall
V/GetPrviateResource( 3578): GetPrviateResource
D/PMS     (  907): releaseWL(18926e9f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/MessageCustFlag( 3578): sense_version=6.0
D/BTAccessoryUtil( 3578): createReceiver
D/BTAccessoryUtil( 3578): registerReceiver return intent = null
D/MessageCustFlag( 3578): sku_id=99
D/HtcBuildUtils( 3578): getRATByHtcTelephonyCapability:1
W/SystemReader( 3578): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 3578): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 3578): onReceive()
D/NGFService( 3433): Elvis is initialization Success
D/NGFService( 3433): bElvisInitializeCompleted = true
D/NGFService( 3433): GrammarState = 0
D/NGFService( 3433): loadGrammar +++
D/NGFService( 3433): loadGrammar asr_grammar
D/ExchangePolicystatus( 3578): onReceive(): ACTION_BOOT_COMPLETED
I/NGFService( 3433): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3433): loadGrammar from cache
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishname.lst
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishartist.lst
D/PMS     (  907): acquireWL(1f521916): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3578 10067 null
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishplaylist.lst
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3433): Fail to open read-stream for file elvisBritish Englishgeneric.lst
D/MessageUtils( 3578): Text messaging allow status = allow
D/Messaging( 3578): EAS allow SMS !!!
D/ExchangePolicystatus( 3578): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3578): EAS allow SMS !!!
E/MediaScannerService( 3520): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3520): [handleMessage] --- Should not be here, ignore request. ----
V/SmsReceiverService( 3578): onStart: #1, @344424691
V/SmsReceiverService( 3578): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3578): isCbm: false
D/SmsReceiverService( 3578): isDiscard: false
D/SettingsManager( 3578): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2a65d657
V/SmsReceiverService( 3578): handleBootCompleted
W/NMT-OemFile( 3433): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3433): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
W/NMT-OemFile( 3433): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
W/ResourcesManager( 3578): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/NMT-OemFile( 3433): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3433): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3433): fopen(): Failed to open file clm.dat
I/ActivityManager(  907): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3617 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/AccFlag ( 1457): sku_id=99
D/SmsReceiverService( 3578): OutBoxSize = 0
D/SmsReceiverService( 3578): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3578): sku_id=99
W/NMT-OemFile( 3433): fopen(): Failed to open file daniel_userdct_eng.dat
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1457): sku_id=99
D/MessageCustFlag( 3578): sku_id=99
D/SmsReceiverService( 3578): sendFirstQueuedMessage end cnt> 0
D/SettingUtils( 3433): setProcessNormalFlag: true
D/NGFService( 3433): RebuildListener constraintList size 17
D/NGFService( 3433): RebuildListener: onComplete0
D/NGFService( 3433): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3433): switchScenario: htc_screen_140_19
D/NGFService( 3433): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3433): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3433): Loading grammar completed.
D/NGFService( 3433): update contact cache completed
D/SettingUtils( 3433): set Updatge Contact Cache: false
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishname.lst
I/[PluginManager]RegisterService( 1412): Notify Carousel that a new TabPlugin has been installed!
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishartist.lst
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishsong.lst
W/MediaScanner( 3520): Error opening directory '/oem/media/', skipping: No such file or directory.
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishalbum.lst
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishplaylist.lst
W/NMT     ( 3433): Fail to open read-stream for file serverBritish Englishgeneric.lst
D/SpaceBufferUtil( 3578): > createBufferFile()
D/SpaceBufferUtil( 3578): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 3578): < createBufferFile()
W/MediaScanner( 3520): Error opening directory '/oem/media/', skipping: No such file or directory.
D/MediaScanner( 3520):  prescan time: 200ms
D/MediaScanner( 3520):     scan time: 54ms
D/MediaScanner( 3520): postscan time: 0ms
D/MediaScanner( 3520):    total time: 254ms
D/MediaScanner( 3520): -----------------------------------------------------------------
D/MediaScanner( 3520): firstscan(media) time: 42ms
D/MediaScanner( 3520): secondscan(non-media) time: 8ms
D/MediaScanner( 3520):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Total]    File(Image+Video+Audio+Others) in database : 359
E/cutils-trace( 3635): Error opening trace file: No such file or directory (2)
I/dex2oat ( 3635): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/MediaProvider( 3520): [delete][97]
D/MediaProvider( 3520): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3520): [recoverParentNodes] - 0
D/MediaProvider( 3520): [update][15]
D/MediaScannerServiceEx( 3520): [scan] Recover Parent Node is finished!
D/PMS     (  907): releaseWL(1598d78e): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
E/MediaScannerServiceEx( 3520): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3520): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3520): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3520): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3520): [update][6]#0#
D/MediaProvider( 3520): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3520): [update][0]#0#
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3520): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3520): [update][10]#1#
D/MediaScannerServiceEx( 3520): [AliveExtStorageRows]-0, -1, 0, -1
D/PMS     (  907): acquireWL(1b8b9c84): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3520 10017 null
D/MediaScanner( 3520): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/Prism.ItemManager( 1494): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1494): loadItems() com.htc.launcher.pageview.WidgetManager@26dfee4c +
I/Prism.WidgetManager( 1494): onLoadItems() +
W/ResourcesManager( 1494): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1494): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Prism.WidgetManager( 1494): onLoadItems() -
I/Prism.ItemManager( 1494): loadItems() com.htc.launcher.pageview.WidgetManager@26dfee4c -
V/AlarmManager(  907): sending alarm PendingIntent{163a0c6d: PendingIntentRecord{2fceb0a2 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=37985, Int=0
D/PhoneApp( 1457): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1457): -- N1 =0
D/PhoneApp( 1457): -- N2 =0
D/PhoneApp( 1457): -- N3 =0
I/HtcModeClient( 3083): handler message = 4011
E/HtcModeClient( 3083): Check connection and retry 1 times.
I/dex2oat ( 3635): dex2oat took 972.150ms (threads: 4)
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): VersionName:             1.2.848061
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): VersionCode:             148001212
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3617): ApplicationMonitor {35ee21b0}: logBasicAppInfo(): BuildConfig.DEBUG:       false
I/PushClient( 3617): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
D/MediaScanner( 3520):  prescan time: 352ms
D/MediaScanner( 3520):     scan time: 599ms
D/MediaScanner( 3520): postscan time: 1ms
D/MediaScanner( 3520):    total time: 952ms
D/MediaScanner( 3520): -----------------------------------------------------------------
D/MediaScanner( 3520): firstscan(media) time: 489ms
D/MediaScanner( 3520): secondscan(non-media) time: 110ms
D/MediaScanner( 3520):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Total]    File(Image+Video+Audio+Others) in database : 1533
D/MediaProvider( 3520): [delete][6]
D/MediaProvider( 3520): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3644 uid=10079 gids={50079, 9997} abi=armeabi-v7a
D/MediaProvider( 3520): [recoverParentNodes] - 0
D/MediaProvider( 3520): [update][6]
D/MediaScannerServiceEx( 3520): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3520): [updateImage]+
I/ActivityManager(  907): Killing 3206:com.google.android.onetimeinitializer/u0a27 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3206
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/MediaScannerServiceEx( 3520): [updateImage]-0
I/ActivityManager(  907): Recipient 3206
D/Process (  907): killProcessQuiet, pid=3206
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10027/pid_3206/cgroup.procs: No such file or directory
D/PMS     (  907): releaseWL(1b8b9c84): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3520): [2] scan finished
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3520): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]+131073
I/art     (  907): Explicit concurrent mark sweep GC freed 19735(979KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.067ms total 71.914ms
D/SMSBackup( 3644): Got ACTION_BOOT_COMPLETED event
D/SMSBackup( 3644): setCheckAlarm
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/SMSBackup( 3644): Next check is scheduled at 60s from now
D/Process (  907): killProcessQuiet, pid=3232
I/ActivityManager(  907): Killing 3232:com.htc.video/u0a30 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/MediaProvider( 3520): [update][6]#1#
D/MediaProvider( 3520): [update][3]#0#
I/ActivityManager(  907): Recipient 3232
D/Process (  907): killProcessQuiet, pid=3232
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10030/pid_3232/cgroup.procs: No such file or directory
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1457, uid=1001, userID:0
D/MediaProvider( 3520): [update][38]#0#
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]--1, 0, 0
D/HtcBroadcastReceiver( 1457): onReceive: android.intent.action.BOOT_COMPLETED
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3520): Process mounted intent for unmounted storage: /storage/usb
I/ActivityManager(  907): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3662 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]+196609
I/art     (  472): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 212us total 11.536ms
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3520): [update][7]#1#
D/MediaProvider( 3520): [update][3]#0#
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 174us total 11.579ms
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 175us total 10.780ms
I/[AppShowMeDebug]BootCompletedReceiver( 3662): received boot complete
I/[AppShowMeDebug]BootCompletedReceiver( 3662): push flag is false, skip check
D/MediaProvider( 3520): [update][46]#0#
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]--1, 0, 0
I/ActivityManager(  907): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3681 uid=10087 gids={50087, 9997, 1007, 3003, 1028} abi=armeabi-v7a
D/Process (  907): killProcessQuiet, pid=2945
I/ActivityManager(  907): Killing 2945:com.google.android.partnersetup/u0a28 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Recipient 2945
D/Process (  907): killProcessQuiet, pid=2945
W/libprocessgroup(  907): failed to open /acct/uid_10028/pid_2945/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
E/MediaScannerServiceEx( 3520): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3520): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3520): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3520): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3520): [update][4]#0#
D/MediaProvider( 3520): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3520): [update][1]#0#
D/MyReportAgent( 3681): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3520): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3520): [update][11]#1#
D/MediaScannerServiceEx( 3520): [AliveExtStorageRows]-0, -1, 0, -1
D/PMS     (  907): acquireWL(18855c25): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3520 10017 null
D/MyReportAgent( 3681): DatabaseHelper [DatabaseHelper constructor]
D/MyReportAgent( 3681): PolicyStore [Init] Get cached policy bundle
D/MyReportAgent( 3681): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
D/MyReportAgent( 3681): ReportServiceHandler on boot complete event 
I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3702 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a
D/MediaScanner( 3520): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3681, uid=10087, userID:0
V/MyReportAgent( 3681): ReportServiceHandler unregister the PowerConnected Listener
I/ActivityManager(  907): Killing 3275:com.htc.csrecommend/u0a32 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3275
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  907): Recipient 3275
D/Process (  907): killProcessQuiet, pid=3275
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10032/pid_3275/cgroup.procs: No such file or directory
I/htcCheckinService(  907): htcCheckinProvider V2.1
D/htcCheckinService(  907): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  907): Checkin service onCreate()!
D/UpdaterAPK | UpdaterBootCompleteReceiver( 3702): onReceive() - start htcCheckinService
I/ActivityManager(  907): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.BootReceiver: pid=3722 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/htcCheckinService(  907): onStartCommand()
D/htcCheckinService(  907): onStartCommand() the action name = null
D/htcCheckinService(  907): InitThread start
D/Process (  907): killProcessQuiet, pid=2089
I/ActivityManager(  907): Killing 2089:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 2089
D/Process (  907): killProcessQuiet, pid=2089
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10025/pid_2089/cgroup.procs: No such file or directory
W/ResourceType( 3722): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/ResourcesManager( 3722): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3744 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
W/System.err( 3722): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 3722): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 3722): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
I/ActivityManager(  907): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=3762 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/WorldClock.Global( 3744): isHEPDevice = true
D/PMS     (  907): acquireWL(1618b57b): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3744 10096 null
W/ResourceType( 3762): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/ResourcesManager( 3762): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Tiber/HtcIrService( 3762): Created by Thread:1
I/ActivityManager(  907): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
D/Messaging( 3578): supportCMAS(SIE)/init? false/true
I/Tiber/PeelUtils( 3762): Create new PeelUtils
D/MmsConfig( 3578): networkCode: 
D/MmsConfig( 3578): SIE smsPri: null
D/MmsConfig( 3578): networkCode: 
W/WorldClock.AlarmService( 3744): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
I/WorldClock.AlarmUtils( 3744): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.Global( 3744): isHEPDevice = true
D/MmsConfig( 3578): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 3578): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3578): 
D/MmsAsyncWorkHandler( 3578): HM tk = 20001
D/ReportIndicatorCache( 3578): MSG_QUERY_REPORTS >>
I/WorldClock.AlarmUtils( 3744): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3744): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1122): receive(android.intent.action.ALARM_CHANGED,1,false)
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1457): sku_id=99
I/Tiber/PeelUtils( 3762): loadDB: load data from database
D/DraftCache( 3578): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3578): [DraftCache/1] refresh
D/DraftCache( 3578): [DraftCache/431] DraftCache.constructor
D/DraftCache( 3578): [DraftCache/431] refresh
D/DraftCache( 3578): [DraftCache/431] rebuildCache
D/MmsConfig( 3578): networkCode: 
I/Tiber/PeelUtils( 3762): loadDB(), room count : 0
I/HtcStatusBarManagerWrapper( 3762): glow:20
W/ContentService(  907): Observer android.database.IContentObserver$Stub$Proxy@3c886e2d is already registered.
I/Tiber/PeelUtils( 3762): loadDB: load updated data from database finished
I/Tiber/HtcIrService( 3762): Created by Thread:1 finished
D/MediaScanner( 3520):  prescan time: 92ms
D/MediaScanner( 3520):     scan time: 381ms
D/MediaScanner( 3520): postscan time: 1ms
D/MediaScanner( 3520):    total time: 474ms
D/MediaScanner( 3520): -----------------------------------------------------------------
D/MediaScanner( 3520): firstscan(media) time: 247ms
D/MediaScanner( 3520): secondscan(non-media) time: 134ms
D/MediaScanner( 3520):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3520):  [Total]    File(Image+Video+Audio+Others) in database : 1533
I/IntentController( 1122): receive(com.htc.intent.action.STATUS_BAR_GLOW,1,false)
D/Messaging( 3578): mNeedToUpdateDate2 start
D/Messaging( 3578): ViewCache CreatePreloadOnlyConversationList
W/ContentService(  907): Observer android.database.IContentObserver$Stub$Proxy@3b76cf62 is already registered.
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
I/ActivityManager(  907): Resuming delayed broadcast
W/ContextImpl(  907): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
I/Messaging( 3578): mccmnc> 
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
D/MmsSmsV2Provider( 1457):  slotId = -1000
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
W/ContextImpl( 3722): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
D/Messaging( 3578): mNeedToUpdateDate2: false
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/ContextImpl( 3722): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
D/Messaging( 3578): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
I/ActivityManager(  907): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3796 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/AntHalService(  907): onCreate() entered
D/JAntJava(  907): Calling nativeJAnt_Create
D/PMS     (  907): releaseWL(1618b57b): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
D/JAntJava(  907): create: nativeJAnt_Create returned success
D/AntHalService(  907): JAntJava create success
D/AntHalService(  907): onStartCommand() entered
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/Jerry   ( 1457): URI_DRAFT
D/DraftCache( 3578): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3578): [DraftCache/431] rebuildCache time: 6
D/DraftCache( 3578): [DraftCache/431] rebuildCache
I/PhoneStatusBar( 1122): glow(20,0,0)
D/Process (  907): killProcessQuiet, pid=3292
I/ActivityManager(  907): Killing 3292:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/Jerry   ( 1457): URI_DRAFT
D/MessageCustFlag( 3578): sense_version=6.0
D/Jerry   ( 3578): start to preload cursor >>>>>>>
D/DraftCache( 3578): hasDraft() = false mNeedNotifyChange = false
D/DraftCache( 3578): [DraftCache/431] rebuildCache time: 1
D/MmsAsyncWorkHandler( 3578): 
D/MmsAsyncWorkHandler( 3578): HM tk = 20002
D/MediaProvider( 3520): [delete][61]
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1457): sku_id=99
D/MediaProvider( 3520): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
I/ActivityManager(  907): Recipient 3292
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/PhoneStorageUtil( 3578): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3578): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3578): createReceiver
D/Messaging( 3578): ViewCache CreatePreload
D/Messaging( 3578): ViewCache CreatePreloadOnlyMultipleOpsList
D/MediaProvider( 3520): [recoverParentNodes] - 0
D/MediaProvider( 3520): [update][6]
D/MediaScannerServiceEx( 3520): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3520): [updateImage]+
D/Cust_MMSMS( 3578): _has_set_default_values_2=true
E/cutils-trace( 3741): Error opening trace file: No such file or directory (2)
D/MsgPreferenceUtils( 3578): def_index: 0
D/MsgPreferenceUtils( 3578): globalIndex = 1
D/MediaScannerServiceEx( 3520): [updateImage]-0
D/MsgPreferenceUtils( 3578): phone state: true
D/MsgPreferenceUtils( 3578): sd state: false
D/MsgPreferenceUtils( 3578): vIndex = 0
D/Process (  907): killProcessQuiet, pid=3292
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_3292/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/PMS     (  907): releaseWL(18855c25): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/AccFlag ( 1457): sku_id=99
D/MediaScannerServiceEx( 3520): [3] scan finished
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3520): Process mounted intent for unmounted storage: /storage/ext_sd
D/TelephUtils( 1457): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
V/MmsProvider( 1457): Update uri=content://mms, match=0
V/MmsProvider( 1457): selection=st=129 AND m_type!=134
D/Messaging( 3578): Reset downloading state: 0
V/MmsSystemEventReceiver( 3578): TransactionService is going to be woken up.
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]+131073
V/TransactionService( 3578): 1-Creating TransactionService
V/TransactionService( 3578): onStartCommand: 1
D/MmsSystemEventReceiver( 3578): unRegisterForConnectionStateChanges
V/TransactionService( 3578): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3578): Loading previous transactions.
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c288ac5:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 3722): 920472631: getState() :  mService = null. Returning STATE_OFF
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1457): device_type: 1
D/CustomizationManager( 3741): ====startRecUseTime====
D/htc.customization.log.level( 3741):  is 
W/CustomizationLogLevel( 3741): Level value is invalid, use default level 2
D/TransactionService( 3578): Force set service start id to 1
V/TransactionService( 3578): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3578): unRegisterForConnectionStateChanges
V/TransactionService( 3578): Destroying TransactionService
D/TransactionService( 3578): stopSelfResult: true, mLastHandledServiceId: 1
D/CIRControlWrapper( 3722): hasIrEmitter = true
D/PMS     (  907): acquireWL(30e94c1a): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 3722 10091 null
D/PMS     (  907): releaseWL(30e94c1a): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 null
I/Tiber/HtcIrService( 3762): onDestroy called
I/Tiber/PeelUtils( 3762): Stop CIR service...
D/Tiber/HtcIrService( 3762): If IR had killed, to remove temp data in videocenter_had_killed
I/ActivityManager(  907): Killing 2672:com.htc.contacts/u0a40 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2672
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  907): Recipient 2672
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3520): [update][51]#1#
D/MediaProvider( 3520): [update][3]#0#
V/TransactionService( 3578): 4-Handling incoming message: { when=-38ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MediaProvider( 3520): [update][41]#0#
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]--1, 0, 0
D/Process (  907): killProcessQuiet, pid=2672
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10040/pid_2672/cgroup.procs: No such file or directory
D/Process (  907): killProcessQuiet, pid=3309
I/ActivityManager(  907): Killing 3309:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3520): Process mounted intent for unmounted storage: /storage/usb
D/CustomizationManager( 3741):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__001
I/ActivityManager(  907): Recipient 3309
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__203
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__405
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__304
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 3741): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3741): Parsing tag category name = system
I/CustomizationCIDLoader( 3741): Parsing tag category name = application
I/CustomizationCIDLoader( 3741): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3741): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3741): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3741): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3741): Parsing tag category name = ACC
D/CustomizationManager( 3741):  Read CID file spent 0.096 (s)
D/CustomizationManager( 3741):  All configurations done spent 0.096 (s)
E/UpdateRequestReceiver( 3796): ignoring update request
E/ActTriggerJNI( 3741): open library fail.
E/MP-Decision( 2242): Update arg 2
D/Process (  907): killProcessQuiet, pid=3309
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10042/pid_3309/cgroup.procs: No such file or directory
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]+196609
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PMS     (  907): acquireHCC(1ea1834b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 907 1000 null
E/MP-Decision( 2242): Update arg 4
D/PMS     (  907): acquireHCC(17c7f128): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 907 1000 null
W/asset   (  907): Copying FileAsset 0xb9eb3fb8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  907): acquireWL(d030927): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
E/MP-Decision( 2242): Update arg "0 190 240 240".
E/MP-Decision( 2242): Update arg "0 75 400 400".
I/AnimationUtil(  907): isHTCRecent(HelloWorld/Recent screens.)/4
I/FeedHostManager( 1494): [onPause]
I/FeedProviderManager( 1494): onPause
I/FeedHostManager( 1494): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2c4dff83
I/SocialFeedProvider( 1494): +onPause
I/SocialFeedProvider( 1494): -onPause
D/HtcSystemUPManager(  907): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
D/MediaProvider( 3520): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3520): [update][4]#1#
D/MediaProvider( 3520): [update][3]#0#
E/UpdateRequestReceiver( 3796): ignoring update request
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3852 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/UpdateRequestReceiver( 3796): ignoring update request
E/UpdateRequestReceiver( 3796): ignoring update request
E/UpdateRequestReceiver( 3796): ignoring update request
D/StatusBarManagerService(  907): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
E/UpdateRequestReceiver( 3796): ignoring update request
D/MediaProvider( 3520): [update][63]#0#
W/asset   ( 3852): Copying FileAsset 0xb9ca58f0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/MediaScannerServiceEx( 3520): [disAliveExtStorageRows]--1, 0, 0
I/TrimMemoryManager( 1494): [trimMemory] 20
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3877 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
D/Process (  907): killProcessQuiet, pid=3328
I/ActivityManager(  907): Killing 3328:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Recipient 3328
D/Process (  907): killProcessQuiet, pid=3328
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10048/pid_3328/cgroup.procs: No such file or directory
I/DeviceManagement( 3877): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=3877 dbg=false s=true
I/DeviceManagement( 3877): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 3877): WorkflowService: Starting workflow service
I/DeviceManagement( 3877): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@b9f562d] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3877): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3877): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 3877): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3877): ModelRegistry: Loading model meta data from resources...
I/GoogleHttpClient( 1726): GMS http client unavailable, use old client
I/WebViewFactory( 3852): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/DeviceManagement( 3877): BackgroundController: *** Update after boot...
,I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3898 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 3852): Time to load native libraries: 2 ms (timestamps 9724-9726)
I/LibraryLoader( 3852): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3852): Binding Chromium to main looper Looper (main, tid 1) {394613d6}
,I/LibraryLoader( 3852): Expected native library version number "",actual native library version number ""
I/chromium( 3852): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3852): Initializing chromium process, singleProcess=true
,W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3852): ApplicationContext is null in ApplicationStatus
,W/chromium( 3852): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3852): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 3852): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3852): Build Date: 12/11/14 Thu
I/Adreno-EGL( 3852): Local Branch: 
I/Adreno-EGL( 3852): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 3852): Local Patches: NONE
I/Adreno-EGL( 3852): Reconstruct Branch: NOTHING
,I/htcbackup-core( 3898): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3877): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
,I/DeviceManagement( 3877): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,I/DeviceManagement( 3877): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/DeviceManagement( 3877): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,W/System.err(  907): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	,at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	,at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f11099c:true
D/BluetoothAdapter( 3852): 904798640: getState() :  mService = null. Returning STATE_OFF
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm,
I/DeviceManagement( 3877): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 3877): Perf: *** Cache update - start...
I/DeviceManagement( 3877): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3877): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3877): EnabledAppController: Enabled app scan is pending...
,I/DeviceManagement( 3877): Perf: Scan enabled apps - start...
,W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3852): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3852): CordovaWebView is running on device made by: HTC
,W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
,I/HtcModeClient( 3083): handler message = 4009
,I/HtcModeClient( 3083): start to setup the connection
,I/DeviceManagement( 3877): EnabledAppBuilder: Examining 267 installed apps for DM enabled apps...
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500050, versionName=6.5.838445
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031392, versionName=6.3.851500,
,W/ResourcesManager( 3877): Asset path '/system/framework/com.android.future.usb.accessory.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444606881, versionName=4.2.848011
,I/art     (  907): Explicit concurrent mark sweep GC freed 18347(917KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 972us total 65.011ms
,D/Atlas   ( 3852): Validating map...
,W/chromium( 3852): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/ResourcesManager( 3877): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001301, versionName=6.0.847523
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +705ms,
,I/InputMethodManager( 3852): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@176556e0, mServedView=org.apache.cordova.engine.SystemWebView{27de6d99 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1c6f785e
,W/ResourcesManager( 3877): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3877): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/InputMethodManagerService(  907): Disable input method client, pid=1494
D/StatusBarManagerService(  907): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  907): Enable input method client, pid=3852
,D/PMS     (  907): releaseWL(d030927): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/BindingManager( 3852): Cannot call determinedVisibility() - never saw a connection for the pid: 3852
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001280, versionName=6.5.847469,
,I/chromium( 3852): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/XT9_C   ( 1288): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1288): [T9_ReleaseBuffer] Reset LDB#0
,I/XT9_C   ( 1288): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1288): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/ResourceType( 3877): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, versionCode=250081396, versionName=2.7.845092
,W/ResourceType( 3877): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
,V/SmsReceiverService( 3578): updateNotificationAndShortcutStatus: 
,D/MessagingNotification( 3578): New incoming message, can't cancel notification now
,D/MessagingNotification( 3578): newMsgCnt: 0, false
,I/ActivityManager(  907): Killing 3350:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3350
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3350,
,D/JsMessageQueue( 3852): Set native->JS mode to OnlineEventsBridgeMode
I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001212, versionName=1.2.848061
,E/AndroidProtocolHandler( 3852): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/Process (  907): killProcessQuiet, pid=3350
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10050/pid_3350/cgroup.procs: No such file or directory
,D/PMS     (  907): releaseWL(1f521916): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715,
,W/ResourcesManager( 3877): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/jxcore_app_log( 3852): JniHelper::setJavaVM(0xb8be8b98), pthread_self() = -1176090544,
D/JX-Cordova( 3852): jxcore cordova android initializing
,W/ResourcesManager( 3877): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3877): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3877): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001186, versionName=2.2.821083,
,I/DeviceManagement( 3877): EnabledAppBuilder: Found 9 DM enabled apps.
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.videohub.ui
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,W/jxcore-log( 3852): Initializing JXcore engine
W/jxcore-log( 3852): JXcore engine is ready
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,W/jxcore-log( 3852): Starting JXcore engine
,I/DeviceManagement( 3877): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 3877): Perf: Scan enabled apps - complete: 567 ms
,I/DeviceManagement( 3877): Perf: *** Enabled app cache update - complete: 569 ms
,I/DeviceManagement( 3877): Perf: *** Config cache update - start...
,I/DeviceManagement( 3877): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3877): ConfigCacheController: *** Device manifest update is pending...
,I/DeviceManagement( 3877): ConfigCacheController: *** Sending device manifest...
,W/jxcore-log( 3852): Platform android,
W/jxcore-log( 3852): 
W/jxcore-log( 3852): Process ARCH arm
W/jxcore-log( 3852): 
I/art     ( 3877): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
I/art     ( 3877): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,I/jxcore-log( 3852): JXcore Cordova bridge is ready!,
I/jxcore-log( 3852): 
W/jxcore-log( 3852): JXcore engine is started
,W/System.err( 3877): Starting the internal HTTP client
,E/jxcore-log( 3852): >> HTC-HTC One_M8
E/jxcore-log( 3852): 
,I/jxcore-log( 3852): Total memory 1912020992
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): Free memory 163336192
I/jxcore-log( 3852): 
I/jxcore-log( 3852): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3852): 
I/jxcore-log( 3852): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): userPath [ 'www' ]
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): Size 1080 1776
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): Screen Brightness 142
I/jxcore-log( 3852): 
,E/jxcore-log( 3852): Dummy Error Log.
E/jxcore-log( 3852): 
,I/DeviceManagement( 3877): DeviceClientResource: Active network...
I/DeviceManagement( 3877):   No active network
,I/DeviceManagement( 3877): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 3877): BackgroundController: *** Network unavailable!
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=3877, uid=10105, userID:0
,I/DeviceManagement( 3877): Perf: *** Config cache update - complete: 254 ms
I/DeviceManagement( 3877): Perf: *** Cache update - complete: 824 ms
,I/DeviceManagement( 3877): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@b9f562d]
,I/DeviceManagement( 3877): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3877): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3877): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,W/Atfwd_Sendcmd(  480): AtCmdFwd service not published, waiting... retryCnt : 3
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,I/DeviceManagement( 3877): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 3877): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.backup
,I/DeviceManagement( 3877): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea]
,I/DeviceManagement( 3877): WorkflowService: Stopping workflow service
,I/ActivityManager(  907): Killing 3368:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3368
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3368
,D/Process (  907): killProcessQuiet, pid=3368
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10051/pid_3368/cgroup.procs: No such file or directory
,I/htcbackup-core( 3898): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/ActivityManager(  907): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/Process (  907): killProcessQuiet, pid=3386
I/ActivityManager(  907): Killing 3386:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  907): Recipient 3386
,D/Process (  907): killProcessQuiet, pid=3386
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_3386/cgroup.procs: No such file or directory
,D/Process (  907): killProcessQuiet, pid=3416
,I/ActivityManager(  907): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3973 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Killing 3416:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
,I/art     (  472): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 145us total 9.179ms
I/ActivityManager(  907): Recipient 3416
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 139us total 8.763ms
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 8.506ms
,D/Process (  907): killProcessQuiet, pid=3416
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10057/pid_3416/cgroup.procs: No such file or directory
,D/ResetNotifyBootCompleteReceiver( 1457): Receive bootcomplete intent,
,I/HtcCupdXmlParser( 3973): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3993 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 3973): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider,
D/AutoSetting( 1412): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1412): Util - check NLP state, Allowned:true, Enabled:true,
D/AutoSetting( 1412): Util - no network available!
D/AutoSetting( 1412): service - requestNLP() network is not available
,I/jxcore-log( 3852): getBuffer is called!!!!,
I/jxcore-log( 3852): 
,D/QXDM2SD:HtcNative( 1457): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true,
,I/HtcCupdXmlParser( 3973): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory),
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4013 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/AlarmManager(  907): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  907): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  907): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4030 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,D/Process (  907): killProcessQuiet, pid=3451
I/ActivityManager(  907): Killing 3451:com.htc.lmw/u0a61 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3451
,V/Settings:HtcSettingsApplication( 4013): [4013/4013] onCreate()
,W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
,D/Process (  907): killProcessQuiet, pid=3451
W/libprocessgroup(  907): failed to open /acct/uid_10061/pid_3451/cgroup.procs: No such file or directory
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4048 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/PMS     (  907): releaseHCC(1ea1834b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  907): releaseHCC(17c7f128): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/MP-Decision( 2242): Update arg 1
,I/ActivityManager(  907): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4065 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a,
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1afe9239
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2007d07e,
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@44e59df,
,I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.gsf,
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  907): [AlarmQueuing] add queuing package: jp.naver.line.android
,I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.orca,
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/ActivityManager(  907): Killing 3478:com.android.managedprovisioning/u0a66 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3478
W/ResourcesManager( 4065): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  907): Recipient 3478,
,D/HtcFingerPrintQuickLaunchProvider( 4048): -onCreate(),
,D/Process (  907): killProcessQuiet, pid=3478,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10066/pid_3478/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4065): Created com.android.providers.calendar.CalendarAlarmManager@394613d6(com.htc.providers.calendar.HtcCalendarProvider@2a65d657),
,D/CalendarProvider2( 4065): wait start:true,
,V/Settings:HtcSettingsApplication( 4048): [4048/4048] onCreate(),
,D/CalendarProvider2( 4065): wait end:false
,W/ContextImpl( 4048): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 4048): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4048): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4048): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4048): Cust_ConnectToPC   : spcsc>false
D/        ( 4048): Cust_ConnectToPC   : IPT>true
D/        ( 4048): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4048): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  907): Killing 1953:com.google.android.gms/u0a25 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=1953
E/SmartNS_Utility( 4048): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4048): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4048): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/SmartNS_Utility( 4048): setISNotification
,D/SmartNS_Utility( 4048): usb_cable_connect = 1
D/SmartNS_Utility( 4048): usb_denied = 0
,I/SmartNS_PSService( 4048): usb notificaiton:true
,E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  907): Recipient 1953
,D/Process (  907): killProcessQuiet, pid=1953
W/libprocessgroup(  907): failed to open /acct/uid_10025/pid_1953/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActionCombine( 4048): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4048): usb_cable_connect = 1
,I/ActionCombine( 1211): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4048): usb_denied = 0
I/SmartNS_PSService( 4048): usb notificaiton:true
D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1122): setHTCTheme(com.android.settings,true,33751145)
I/ActivityManager(  907): Killing 3617:com.htc.cs.pns/u0a74 (adj 15): empty #17
D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/Process (  907): killProcessQuiet, pid=3617
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/RemoteViews( 1122): apply : com.android.settings 3 9 1 36
,I/ActivityManager(  907): Recipient 3617
,I/RemoteViews( 1122): reapply : com.android.settings 0 36
,D/Process (  907): killProcessQuiet, pid=3617
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10074/pid_3617/cgroup.procs: No such file or directory
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  907): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/SmartDim(  907): Init customizeScreenOffDelayClass error
,E/MP-Decision( 2242): Update arg 2
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{d37b25c u0 ReceiverList{a778cf 907 system/1000/u0 local:3a07552e}}
,I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@38649330, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = Accelerometer Sensor,
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@38649330, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3,
W/SensorService(  907): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@6c4a3ec
W/SensorService(  907): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1aa7a126
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@38649330
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@38649330, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = CM36282 Proximity sensor
,W/SensorService(  907): pid=907, uid=1000,
W/SensorService(  907): Active sensors: size = 3
,W/SensorService(  907): Accelerometer Sensor (handle=0x00000000, connections=2)
,W/SensorService(  907): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@38649330, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@6c4a3ec
W/SensorService(  907): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1aa7a126
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@38649330
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  907): killProcessQuiet, pid=3644
I/ActivityManager(  907): Killing 3644:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  907): Recipient 3644
,D/Process (  907): killProcessQuiet, pid=3644
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10079/pid_3644/cgroup.procs: No such file or directory
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4110 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/MP-Decision( 2242): Update arg 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{1cc26eac u0 com.google.android.gms/.gcm.GcmService},
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4110, uid=10075, userID:0
,D/Finsky  ( 4110): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,D/Finsky  ( 4110): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  907): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4153 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,W/Settings( 4110): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 4110): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4153): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4153): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4110, uid=10075, userID:0,
,D/Volley  ( 4110): [548] DiskBasedCache.clear: Cache cleared.,
,D/Volley  ( 4110): [541] DiskBasedCache.clear: Cache cleared.
,I/MultiDex( 4153): VM with version 2.1.0 has multidex support,
I/MultiDex( 4153): install
I/MultiDex( 4153): VM has multidex support, MultiDex support library is disabled.
,D/Process (  907): killProcessQuiet, pid=3662
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4173 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Killing 3662:com.htc.showme/u0a85 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3662,
,D/Process (  907): killProcessQuiet, pid=3662,
,W/libprocessgroup(  907): failed to open /acct/uid_10085/pid_3662/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Finsky  ( 4110): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4110): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4110): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 4153): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/Finsky  ( 4110): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,W/ActivityThread( 4153): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4153): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1545c540: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4153): Installed default security provider GmsCore_OpenSSL
,I/art     (  907): Explicit concurrent mark sweep GC freed 12785(642KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 814us total 81.702ms
,W/ResourcesManager( 4173): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4173): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4173): VM with version 2.1.0 has multidex support
I/MultiDex( 4173): install
I/MultiDex( 4173): VM has multidex support, MultiDex support library is disabled.
,D/Process (  907): killProcessQuiet, pid=3681
I/ActivityManager(  907): Killing 3681:com.htc.feedback/u0a87 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3681
,D/Process (  907): killProcessQuiet, pid=3681
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10087/pid_3681/cgroup.procs: No such file or directory
,V/Finsky  ( 4110): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,I/CalendarProvider2( 4065): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4065): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  907): killProcessQuiet, pid=3702
I/ActivityManager(  907): Killing 3702:com.htc.updater/u0a88 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,V/JNIHelp ( 4173): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ActivityManager(  907): Recipient 3702
,W/ActivityThread( 4173): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4173): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@203b31e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4173): Installed default security provider GmsCore_OpenSSL
,D/Process (  907): killProcessQuiet, pid=3702
,W/libprocessgroup(  907): failed to open /acct/uid_10088/pid_3702/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  907): killProcessQuiet, pid=3744
I/ActivityManager(  907): Killing 3744:com.htc.android.worldclock/u0a96 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3744
,V/GLSUser ( 1726): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/Process (  907): killProcessQuiet, pid=3744
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10096/pid_3744/cgroup.procs: No such file or directory
,D/PMS     (  907): acquireWL(1ecce442): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1726 10025 null,
,V/GmsCoreStatsServiceLauncher( 4173): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) },
,I/NotificationStore( 1726): file does not exist: /data/data/com.google.android.gms/files/notification_data.dat,
,D/PMS     (  907): releaseWL(1ecce442): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1726): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,E/MP-Decision( 2242): Update arg 2
,W/InstanceID/Rpc( 4173): Found 10025
,D/FileApkUtils( 4173): Spent 20ms computing apk sha1.
,D/FileApkUtils( 4173): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4173): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4173): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4173): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/GmsModuleFndr( 4173): Beginning GMS chimera module scan
,W/asset   ( 4173): Copying FileAsset 0xb9d3eae8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/GmsModuleFndr( 4173): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/PMS     (  907): acquireWL(28318aaf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4173 10025 null
D/ChimeraCfgMgr( 4173): Beginning module configuration check
,D/ChimeraCfgMgr( 4173): Module APKs unchanged, check complete
,D/PMS     (  907): acquireWL(27b38ebc): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4173 10025 WorkSource{10025 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1726, uid=10025, userID:0
,D/PMS     (  907): acquireWL(2b56b99a): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4173 10025 WorkSource{10025 com.google.android.gms}
,E/MP-Decision( 2242): Update arg 1,
D/PMS     (  907): acquireWL(1bd479c1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4173 10025 null
,D/GCM     ( 4173): COMPAT: Multi user not supported,
,D/GCM     ( 1726): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,D/PMS     (  907): acquireWL(10e4f954): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4173 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  907): acquireWL(206df0fd): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4173 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  907): releaseWL(27b38ebc): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(28318aaf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  907): releaseWL(10e4f954): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 4173): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/PMS     (  907): acquireWL(3d4256c0): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,I/CheckinService( 4173): Disabling old GoogleServicesFramework version
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4173, uid=10025, userID:0
,I/GCoreUlr( 1683): DispatchingService.onCreate()
,D/SystemUpdateService( 4173): onCreate
I/ActivityManager(  907): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/PMS     (  907): acquireWL(343e8197): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,D/SystemUpdateService( 4173): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
I/ConfigService( 1726): onCreate
,I/ConfigFetchService( 4173): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,V/AuthZen ( 4173): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 4173): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
,D/PMS     (  907): acquireWL(2f674325): PARTIAL_WAKE_LOCK  Icing 0x1 4173 10025 WorkSource{10025 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4173, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4173, uid=10025, userID:0
,I/CheckinService( 4173): Checking schedule, now: 1448461027408 next: 1449027630934,
,I/CheckinService( 4173): active receiver: disabled,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4173, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4173, uid=10025, userID:0,
,I/SystemUpdateService( 4173): cancelUpdate (empty URL)
I/SystemUpdateService( 4173): active receiver: disabled
,I/GCoreUlr( 1683): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
,I/HtcModeClient( 3083): handler message = 4011,
E/HtcModeClient( 3083): Check connection and retry 2 times.
,W/System.err(  907): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21aa4152:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4173, uid=10025, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4173, uid=10025, userID:0
,W/BaseAppContext( 4173): Using Auth Proxy for data requests.
,D/PMS     (  907): releaseWL(2f674325): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,I/ConfigFetchService( 4173): service connected
,I/ActivityManager(  907): Resuming delayed broadcast
,I/GLSUser ( 4173): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 4173): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/PMS     (  907): releaseWL(206df0fd): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
,D/ChimeraCfgMgr( 4173): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConfigFetchService( 4173): ConfigApi connection successful.
I/AuthZen ( 4173): Fetching signing key...
D/ChimeraCfgMgr( 4173): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PMS     (  907): releaseWL(2b56b99a): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 4173): Signing key fetched successfully!
,W/BaseAppContext( 4173): Using Auth Proxy for data requests.,
I/Kids    ( 4173): [KidAccountFixer] No network connection
,I/AuthZen ( 4173): Starting Enrollment...
,D/SystemUpdateService( 4173): onDestroy
,D/AuthZen ( 4173): getting auth token. Attempt 0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1683, uid=10025, userID:0,
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4282 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/PMS     (  907): releaseWL(3d4256c0): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10025 com.google.android.gms}
,I/GLSActivity( 1726): [ac] getting account id,
,W/ResourcesManager( 4282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
W/art     ( 1726): Suspending all threads took: 6.347ms,
,I/art     ( 1726): Background sticky concurrent mark sweep GC freed 1462(96KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 9.109ms total 28.517ms,
,I/GLSUser ( 1726): [ChannelManager] Attempting to channel bind connection HttpClient.,
I/GLSUser ( 1726): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1726): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227,
,I/GLSUser ( 1726): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth,
I/GLSUser ( 1726): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1726): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1726): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AuthZen ( 4173): Error getting auth token
E/AuthZen ( 4173): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4173): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4173): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4173): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4173): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4173): Failed to do enrollment for account: thalitester@gmail.com,
E/AuthZen ( 4173): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4173): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4173): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4173): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4173): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4173): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4173): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 4173): Clearing transaction cache
,I/GCoreUlr( 1683): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  907): acquireWL(37312c75): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(37312c75): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1683): Unbound from all location providers,
,D/PMS     (  907): releaseWL(343e8197): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1683): DispatchingService.onDestroy()
,D/PMS     (  907): acquireWL(12f9c40a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(12f9c40a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/GCoreUlr( 1683): Unbound from all location providers
,D/PMS     (  907): acquireWL(17cfb47b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(17cfb47b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4282): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4282): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3578): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3578): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4282): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,I/Babel_SMS( 4282): MmsConfig.loadFromDatabase
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4282, uid=10120, userID:0
,E/Babel_SMS( 4282): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4282): MmsConfig.loadFromResources
,E/Babel_SMS( 4282): canonicalizeMccMnc: invalid mccmnc nullnull,
,I/Babel_SMS( 4282): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,W/Settings( 4282): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 4282): startup - clean
,I/Babel   ( 4282): deleted: false for 0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4282, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4282, uid=10120, userID:0
,W/VideoCapabilities( 4282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4282): Unsupported mime video/x-ms-wmv
,W/AudioCapabilities( 4282): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4282): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4282): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4282): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4282): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4282): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4282): onServiceConnected,
,W/Babel   ( 4282): Attempted to change video mute state without an active call.
,I/ActivityManager(  907): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4315 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/art     (  472): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 200us total 15.406ms
,I/art     (  472): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 202us total 12.865ms,
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 188us total 12.297ms,
,W/ResourcesManager( 4315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4315): Installed default security provider GmsCore_OpenSSL
,I/art     (  907): Explicit concurrent mark sweep GC freed 16006(914KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 16MB/24MB, paused 907us total 64.037ms,
,W/ResourcesManager( 4315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  907): Killing 3722:com.htc.videocenter/u0a91 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3722
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3722
,E/cutils-trace( 4343): Error opening trace file: No such file or directory (2)
,I/dex2oat ( 4343): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads547791776.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads547791776.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/Process (  907): killProcessQuiet, pid=3722,
W/libprocessgroup(  907): failed to open /acct/uid_10091/pid_3722/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/AlarmManager(  907): sending alarm PendingIntent{3cb4c1c8: PendingIntentRecord{14b1a261 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=43868, Int=259200000
,V/AlarmManager(  907): sending alarm PendingIntent{2721e186: PendingIntentRecord{e5681ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=44568, Int=0
,I/dex2oat ( 4343): dex2oat took 43.107ms (threads: 4),
,E/YouTube MDX( 4315): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 4315): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4315): [NET] android_getaddrinfofornet-, SUCCESS
,E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4315): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
,E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/Vold    (  364): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4315): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files,
,W/InstanceID/Rpc( 4315): Found 10025,
,E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  907): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4407 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  907): Killing 3762:com.htc.tiber2/u0a91 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3762
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3762,
,D/Process (  907): killProcessQuiet, pid=3762
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10091/pid_3762/cgroup.procs: No such file or directory
,D/LocationManagerService(  907): getProviders()=[passive, network],
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4407, uid=10089, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4407, uid=10089, userID:0,
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4437 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4407, uid=10089, userID:0
,E/WifiTrafficPoller(  907): ADD_CLIENT: 6,
,D/WifiService(  907): New client listening to asynchronous messages
,I/VelvetNetworkClient( 4407): Network connection not availble
,D/Process (  907): killProcessQuiet, pid=3796,
I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4463 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
I/ActivityManager(  907): Killing 3796:com.google.android.configupdater/u0a104 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3796,
,D/Process (  907): killProcessQuiet, pid=3796
W/libprocessgroup(  907): failed to open /acct/uid_10104/pid_3796/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  907): Killing 3898:com.htc.backup/u0a118 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3898
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3898,
,D/Process (  907): killProcessQuiet, pid=3898,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10118/pid_3898/cgroup.procs: No such file or directory
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4463): getAccountsCursor,
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  907): MONITOR_LOG
W/Settings:Agent(  907): name: bluetooth_on
W/Settings:Agent(  907): value: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1409
W/Settings:Agent(  907): Process.myUid(): 1000,
W/Settings:Agent(  907): ,
,W/Settings:Agent(  907): 
D/WifiService(  907): New client listening to asynchronous messages
W/System.err(  907): java.lang.Throwable: stack dump
D/WifiService(  907): setWifiEnabled: false pid=3852, uid=10380
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
W/System.err(  907): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
I/WifiService(  907): isSprintWifiRestricted(): false
W/System.err(  907): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,I/WifiService(  907): isMdmWifiRestricted(): false
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
E/WifiTrafficPoller(  907): ADD_CLIENT: 7
D/WifiManager( 3852): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
W/Settings:Agent(  907): MONITOR_LOG
W/Settings:Agent(  907): name: wifi_on
W/Settings:Agent(  907): value: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1269
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  907): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  907): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  907): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
,W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 5(ms)
I/jxcore-log( 3852): ****TEST TOOK:  5038  ms ****
I/jxcore-log( 3852): 
I/jxcore-log( 3852): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3852): 
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 4463): Error finding the version of the Email provider.....,
E/Gmail   ( 4463): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4463): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4463): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4463): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4463): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Gmail   ( 4463): getAccountsCursor
W/EmailMigration( 4463): We do not support migrating this version of the Email provider.,
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4463, uid=10115, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4463, uid=10115, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4463, uid=10115, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4463, uid=10115, userID:0
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4463, uid=10115, userID:0,
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=4509 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4463, uid=10115, userID:0,
I/Gmail   ( 4463): Observing account changes for notifications
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4463): (283) recovered 12 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4463, uid=10115, userID:0,
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4463, uid=10115, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4463, uid=10115, userID:0
E/ActivityThread( 4463): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2888ef09 that was originally bound here,
E/ActivityThread( 4463): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2888ef09 that was originally bound here
E/ActivityThread( 4463): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4463): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4463): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4463): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4463): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
,E/ActivityThread( 4463): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4463): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4463): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4463): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4463): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4463): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4463): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4463): 	at android.os.Looper.loop(Looper.java:155),
E/ActivityThread( 4463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  907): Unbind failed: could not find connection for android.os.BinderProxy@1c7b9315
,I/htcbackup-core( 4509): ModelRegistry: Loading model meta data from resources...,
,I/htcbackup-core( 4509): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
I/htcbackup-core( 4509): SuperSaverModeReceiver: going to send resume event
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4173): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/htcbackup-core( 4509): BackupRestoreManager: onHandleIntent,
I/DeviceManagement( 3877): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/htcbackup-core( 4509): BackupRestoreManager: resume
I/DeviceManagement( 3877): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup],
I/DeviceManagement( 3877): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced,
,I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced,
,I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4546 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4173, uid=10025, userID:0,
I/DeviceManagement( 3877): WorkflowService: Starting workflow service
I/DeviceManagement( 3877): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3877): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3877): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3877): SessionStateController: Checking invariants...
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1457): sku_id=99
,D/LocationInitializer( 4173): Restart initialization of location
,W/ResourcesManager( 4546): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4546): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 103
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4463, uid=10115, userID:0
D/AccFlag ( 1457): sku_id=99
,I/Gmail   ( 4463): getAccountsCursor
D/PMS     (  907): acquireWL(3e16dbc9): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1683 10025 null
I/GCoreUlr( 1683): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}]
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 96
D/AccFlag ( 1457): sku_id=99
I/GCoreUlr( 1683): DispatchingService.onCreate()
D/PMS     (  907): acquireWL(16ae9da6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4173 10025 null
,I/MultiDex( 4546): VM with version 2.1.0 has multidex support
,I/MultiDex( 4546): install
I/MultiDex( 4546): VM has multidex support, MultiDex support library is disabled.
D/PMS     (  907): acquireWL(30c5e3e7): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4173 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  907): releaseWL(16ae9da6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  907): releaseWL(30c5e3e7): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4577 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a,
,D/PMS     (  907): acquireWL(1902d783): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 107
D/AccFlag ( 1457): sku_id=99
V/JNIHelp ( 4546): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/cutils-trace( 4529): Error opening trace file: No such file or directory (2),
,W/ActivityThread( 4546): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4546): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1545c540: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4546): Installed default security provider GmsCore_OpenSSL
,D/CustomizationManager( 4529): ====startRecUseTime====,
D/htc.customization.log.level( 4529):  is 
W/CustomizationLogLevel( 4529): Level value is invalid, use default level 2
,I/art     (  907): Explicit concurrent mark sweep GC freed 11440(585KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.099ms total 60.707ms
,D/PMS     (  907): acquireWL(3f9168df): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1683 10025 null
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,D/PMS     (  907): acquireWL(394db3fb): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1683 10025 null
,I/DeviceManagement( 3877): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 3877): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,D/WearableService( 4546): callingUid 10025, callindPid: 4546
,D/PMS     (  907): acquireWL(20e4c18): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1683 10025 null
,E/MDM     ( 1683): [163] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  907): releaseWL(1c112593): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/SensorManager( 1683): registerListenerImpl: listener = com.google.android.location.collectionlib.cm@1c27d196, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 0, handler = Handler (com.google.android.location.collectionlib.ak) {ed42117}
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): enable: get sensor name = Accelerometer Sensor
W/SensorService(  907): pid=1683, uid=10025
,W/SensorService(  907): Active sensors: size = 3
W/SensorService(  907): Accelerometer Sensor (handle=0x00000000, connections=3)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@1c27d196, eanble = 1, strlen(mName) = 53
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 4
,W/SensorService(  907): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@6c4a3ec
W/SensorService(  907): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1aa7a126
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@38649330
W/SensorService(  907): Listener[3] = com.google.android.location.collectionlib.cm@1c27d196
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/GCoreUlr( 1683): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED
,D/PMS     (  907): acquireWL(2dd5e671): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1683 10025 null
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.backup
I/DeviceManagement( 3877): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea]
,I/DeviceManagement( 3877): WorkflowService: Stopping workflow service
,I/ActivityManager(  907): Killing 3955:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3955
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
I/htcbackup-core( 4509): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/ActivityManager(  907): Recipient 3955
,I/ImageRamCache( 4577): create image Cache, size: 31457280.
,I/ImageRamCache( 4577): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4577): create image Cache, size: 31457280.
,I/FeedSettings( 4577): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
,I/FeedSettings( 4577): GroupBudget 0.500000 0.380000
I/FeedSettings( 4577): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4577): changeLocale(): en_GB,
,D/CustomizationManager( 4529):  Read ACC file spent 0.087 (s),
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4529): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__203
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 4529): Parsing tag item name = HTC__304
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 4529): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 4529): full path : /system/customize/CID/HTC__032.xml
I/Prism.AllAppsOptionsMa_( 4577): loadSortType() with Custom
,I/CustomizationCIDLoader( 4529): Parsing tag category name = system
I/Prism.AllAppsOptionsMa_( 4577): loadGridSize() with Alternative
,I/CustomizationCIDLoader( 4529): Parsing tag category name = application
,I/CustomizationCIDLoader( 4529): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4529): Parsing tag category name = Settings
,I/CustomizationCIDLoader( 4529): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4529): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4529): Parsing tag category name = ACC
,D/CustomizationManager( 4529):  Read CID file spent 0.135 (s)
,D/CustomizationManager( 4529):  All configurations done spent 0.135 (s)
,E/ActTriggerJNI( 4529): open library fail.
,D/Process (  907): killProcessQuiet, pid=3955
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_3955/cgroup.procs: No such file or directory
,I/DeviceManagement( 3877): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 3877): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,D/CustomHighlightReceiver( 4577): [custom highlight] onReceive
,I/DeviceManagement( 3877): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/Gmail   ( 4463): master sync=false, engine sync=true
,I/DeviceManagement( 3877): WorkflowService: Starting workflow service,
,I/DeviceManagement( 3877): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea] args=[Bundle[mParcelledData.dataSize=132]],
I/DeviceManagement( 3877): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132],
D/CustomHighlightService( 4577): [custom highlight] onHandleIntent,
D/NewsDB  ( 4577): set custom highlight []
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4529, uid=2000 userid=0
,I/DeviceManagement( 3877): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,D/PMS     (  907): acquireWL(2b516d92): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1683 10025 null,
,I/GoogleURLConnFactory( 1683): Using platform SSLCertificateSocketFactory
D/WifiService(  907): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@11fa5363}
W/GoogleHttpClient( 1683): Ignoring unsupported parameter: http.conn-manager.max-per-route
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4615 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  907): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3852
I/ActivityManager(  907): Killing 3852:com.example.hello/u0a380 (adj 0): stop com.example.hello
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,D/CustomHighlightService( 4577): [custom highlight] set tags 
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,I/ActivityManager(  907): Recipient 3852
I/WindowState(  907): WIN DEATH: Window{35168d1b u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,W/PackageSettings(  907): Skipping PackageSetting{16b3b503 com.test.thalitest/10373} due to missing metadata
,D/PMS     (  907): releaseWL(3e16dbc9): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,W/ActivityManager(  907): Force removing ActivityRecord{388c0e41 u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,E/MP-Decision( 2242): Update arg "0 380 380 380".
,E/MP-Decision( 2242): Update arg "0 400 400 400".
,W/ActivityManager(  907): Spurious death for ProcessRecord{35b4c2bf 3852:com.example.hello/u0a380}, curProc for 3852: null
,I/ActivityManager(  907): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/DeviceManagement( 3877): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
,I/DeviceManagement( 3877): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,I/FeedHostManager( 1494): [onResume]
,I/FeedProviderManager( 1494): onResume
I/SocialFeedProvider( 1494): +onResume
I/SocialFeedProvider( 1494): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1494): -onResume
I/ConnectivityHelper( 1494): [getCurrentConnectionType] no network connection
,D/DotMatrix( 1211): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1211): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  907): acquireWL(1bfcd18d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/libc    ( 1683): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1683): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1683): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1683): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1683): [NET] android_getaddrinfo_proxy+
D/libc    ( 1683): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  460): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  460): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  460): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  460): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1683): [NET] android_getaddrinfo_proxy-, NODATA
,W/System.err( 1683): java.net.UnknownHostException: Unable to resolve host "www.google.com": No address associated with hostname
,I/Prism.ItemManager( 4577): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4577): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/System.err( 1683): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 1683): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 1683): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 1683): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 1683): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 1683): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
W/System.err( 1683): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
D/PMS     (  907): releaseWL(2dd5e671): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
W/System.err( 1683): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
W/System.err( 1683): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:933)
W/System.err( 1683): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:775)
W/System.err( 1683): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:676)
W/System.err( 1683): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:660)
W/System.err( 1683): 	at com.google.t.a.b.a.b.g(SourceFile:126)
W/System.err( 1683): 	at com.google.t.a.b.a.b.c(SourceFile:172)
,W/System.err( 1683): 	at com.google.aa.a.d.run(SourceFile:435)
W/System.err( 1683): 	at com.google.aa.a.c.c(SourceFile:232)
W/System.err( 1683): 	at com.google.aa.a.c.run(SourceFile:206)
W/System.err( 1683): 	at com.google.t.a.c.b.run(SourceFile:96)
W/System.err( 1683): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 1683): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 1683): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 1683): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
W/System.err( 1683): 	... 22 more
D/WifiService(  907): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@11fa5363}
D/PMS     (  907): releaseWL(2b516d92): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/StatusBarManagerService(  907): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
D/PMS     (  907): releaseWL(1bfcd18d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
D/AccTypeManager( 1615): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 1494): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1494): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/Gmail.LabelManager( 4463): Unable to get label ^i for account thalitester@gmail.com
E/Gmail   ( 4463): Couldn't find label: ^i
D/MessagingShortcutReceiver( 3578): keep hiding shortcut bubble
,D/AccTypeManager( 1615): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/MessagingShortcut( 3578): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3578): After query: 0
D/MessagingShortcut( 3578): mPresentUnreadCount: -1
D/StatusBarManagerService(  907): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
D/MessageUtils( 3578): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
,D/MessagingShortcut( 3578): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 3578): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1211): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1211): [EventService] reorderNotification, total:0
D/DotMatrix( 1211): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1211): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/PackageManager(  907): Unable to load service info ResolveInfo{235553bb com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  907): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
D/PhoneApp( 1457): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ExternalAccountType( 1615): Unsupported attribute readOnly
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4638 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.backup,
,I/DeviceManagement( 3877): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea]
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/DeviceManagement( 3877): WorkflowService: Stopping workflow service
,I/htcbackup-core( 4509): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/art     ( 1683): Explicit concurrent mark sweep GC freed 14779(786KB) AllocSpace objects, 4(64KB) LOS objects, 43% free, 5MB/9MB, paused 4.451ms total 90.750ms
E/htcbackup-core( 4509): DMConfiguredIntentService: Interupted <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]> 
E/htcbackup-core( 4509): BackupRestoreManager: Can not get DM configured
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3852 uid 10380
D/StatusBarManagerService(  907): swetImeWindowStatus vis=0 backDisposition=0,
I/InputMethodManagerService(  907): Enable input method client, pid=1494
,D/Process (  907): killProcessQuiet, pid=3973
,I/ActivityManager(  907): Killing 3973:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,W/ResourcesManager( 4638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/htcbackup-core( 4509): DMConfiguredIntentService: Config model load failed: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
W/htcbackup-core( 4509): DMConfiguredIntentService: reason null 
,I/ActivityManager(  907): Recipient 3973
,D/JobSchedulerService(  907): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  907): Explicit concurrent mark sweep GC freed 17064(1223KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.121ms total 240.882ms
,W/ResourcesManager(  907): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/asset   (  907): Copying FileAsset 0xb9eb0f00 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/GCoreUlr( 1683): WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4656 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
D/Process (  907): killProcessQuiet, pid=3973
W/libprocessgroup(  907): failed to open /acct/uid_10013/pid_3973/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  907): acquireWL(cdefcd1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1683 10025 WorkSource{10025 com.google.android.gms},
D/TodoTaskshortcut( 4638): update TASK shortcut>
D/TaskPersister(  907): removeObsoleteFile: deleting file=27_task.xml
,D/PMS     (  907): acquireWL(69f8336): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1726 10025 WorkSource{10025 com.google.android.gms},
I/DeviceManagement( 3877): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
D/PMS     (  907): releaseWL(cdefcd1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/DeviceManagement( 3877): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,D/libc    ( 1726): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1726): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1726): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1726): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1726): [NET] android_getaddrinfo_proxy+
D/libc    ( 1726): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  460): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  460): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
,D/libc    (  460): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/PMS     (  907): releaseWL(69f8336): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
D/libc    (  460): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1726): [NET] android_getaddrinfo_proxy-, NODATA,
I/DeviceManagement( 3877): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4677 uid=10037 gids={50037, 9997} abi=armeabi-v7a,
,I/DeviceManagement( 3877): WorkflowService: Starting workflow service
I/DeviceManagement( 3877): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3877): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3877): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/GCoreUlr( 1683): Unbound from all location providers
D/PMS     (  907): releaseWL(1902d783): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,D/MdScBootUi( 4615): [10a.1.2.] boot 99
,D/MdScBoot( 4615): [10a.1.] 30@-141649 -> 40
,D/Process (  907): killProcessQuiet, pid=4030
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4700 uid=10079 gids={50079, 9997} abi=armeabi-v7a
I/ActivityManager(  907): Killing 4030:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/art     (  472): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 148us total 9.282ms,
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 129us total 9.413ms
I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,I/ActivityManager(  907): Recipient 4030
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 143us total 8.755ms
,D/Process (  907): killProcessQuiet, pid=4030
W/libprocessgroup(  907): failed to open /acct/uid_10013/pid_4030/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/GCoreUlr( 1683): DispatchingService.onDestroy()
I/DeviceManagement( 3877): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): SessionStateController: Checking invariants...
,D/PMS     (  907): acquireWL(2d451610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1683 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(2d451610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1683): Unbound from all location providers
,V/AlarmManager(  907): sending alarm PendingIntent{a97c30e: PendingIntentRecord{2ae0812f com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448461031331, Int=0,
,D/SMSBackup( 4700): Got a database change event
,D/Process (  907): killProcessQuiet, pid=4065
I/ActivityManager(  907): Killing 4065:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
D/PMS     (  907): acquireWL(24d833c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1726 10025 WorkSource{10025 com.google.android.gms}
D/MdUtils ( 4615): [10a.1.2.] subId list: (0)r0 (s0)-1
,D/libc    ( 1726): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1726): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  907): releaseWL(24d833c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  907): Recipient 4065,
,I/DeviceManagement( 3877): ConfigManagerController: There is no cached content available: appID=com.htc.backup
,I/DeviceManagement( 3877): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2295c9ea]
,W/OpenGLRenderer( 1494): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/Process (  907): killProcessQuiet, pid=4065,
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10011/pid_4065/cgroup.procs: No such file or directory
,I/htcbackup-core( 4509): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3877): WorkflowService: Stopping workflow service
,E/htcbackup-core( 4509): DMConfiguredIntentService: Interupted <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]> 
E/htcbackup-core( 4509): BackupRestoreManager: Can not get DM configured
I/ActivityManager(  907): Killing 4013:com.android.settings:remote/1000 (adj 15): empty #17
I/htcbackup-core( 4509): DMConfiguredIntentService: Config model load failed: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
W/htcbackup-core( 4509): DMConfiguredIntentService: reason null 
,D/Process (  907): killProcessQuiet, pid=4013
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 4013
,D/Process (  907): killProcessQuiet, pid=4013
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4013/cgroup.procs: No such file or directory
,D/PMS     (  907): acquireWL(d0d9728): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4638 10072 null
,D/Process (  907): killProcessQuiet, pid=4089,
I/ActivityManager(  907): Killing 4089:com.android.smith/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
D/PMS     (  907): acquireWL(3c7bc41): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4638 10072 null
,I/ActivityManager(  907): Recipient 4089,
,D/Process (  907): killProcessQuiet, pid=4089
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4089/cgroup.procs: No such file or directory
,D/Process (  907): killProcessQuiet, pid=4048
I/ActivityManager(  907): Killing 4048:com.android.settings/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
E/SQLiteLog( 1726): (3850) statement aborts at 10: [DELETE FROM pending_ops WHERE _id = 634] disk I/O error
E/SQLiteDBG( 1726): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/ns.db, handle: 0xb9d27118
,I/ActivityManager(  907): Recipient 4048
,E/AndroidRuntime( 1726): FATAL EXCEPTION: main
E/AndroidRuntime( 1726): Process: com.google.process.gapps, PID: 1726
E/AndroidRuntime( 1726): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1726): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1726): 	at android.os.Looper.loop(Looper.java:155)
,E/AndroidRuntime( 1726): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/AndroidRuntime( 1726): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1726): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/AndroidRuntime( 1726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 1726): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
,E/AndroidRuntime( 1726): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:254)
E/AndroidRuntime( 1726): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
E/AndroidRuntime( 1726): 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
E/AndroidRuntime( 1726): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
E/AndroidRuntime( 1726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1726): 	... 9 more
,I/ActivityManager(  907): Killing 4153:com.google.android.gms:car/u0a25 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=4153
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 4153
,E/ActivityManager(  907): App crashed! Process: com.google.process.gapps,
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4048/cgroup.procs: No such file or directory
D/Process (  907): killProcessQuiet, pid=4048
W/libprocessgroup(  907): failed to open /acct/uid_10025/pid_4153/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
D/Process (  907): killProcessQuiet, pid=4153
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/MtpReceiver( 3520): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3520): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3520): [MTP][handleUsbState]+
,D/PMS     (  907): releaseWL(d0d9728): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4638): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4638): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4638): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4638): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4638): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4638): 	at android.os.Looper.loop(Looper.java:155)
,D/PMS     (  907): releaseWL(3c7bc41): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4638): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/iu.UploadsManager( 4173): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4731 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a
,D/MtpReceiver( 3520): [MTP][scanExternalVolumeIfNeed] scan external volume,
D/MtpReceiver( 3520): [MTP][handleUsbState]-
D/MtpReceiver( 3520): [MTP][handleMessage]-
D/MtpService( 3520): updating state; isCurrentUser=true, mMtpLocked=false
W/NotifyReceiver( 4638): stopSelfResult true
D/MtpDatabase( 3520): TotalSize=1867208,MediaCacheLimit=6000
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  907): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  907): 	... 5 more
,D/StatusBarManagerService(  907): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  907): hiding MENU key
D/MtpService( 3520): [isMtpConnected] connected: true
,I/iu.UploadsManager( 4173): End new media; added: 0, uploading: 0, time: 83 ms
,E/SQLiteDatabase( 4731): Failed to open database '/data/data/com.nero.android.htc.sync/databases/nccontentprovider.db'.
E/SQLiteDatabase( 4731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4731): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/SQLiteDatabase( 4731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 4731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5417)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4988)
E/SQLiteDatabase( 4731): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4923)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 4731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4731): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/SQLiteDatabase( 4731): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4731): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/SQLiteDatabase( 4731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 4731): FATAL EXCEPTION: main
E/AndroidRuntime( 4731): Process: com.nero.android.htc.sync, PID: 4731
E/AndroidRuntime( 4731): java.lang.RuntimeException: Unable to get provider com.nero.android.neroconnect.contentprovider.NCContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5420)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4988)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4923)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 4731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4731): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/AndroidRuntime( 4731): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4731): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/AndroidRuntime( 4731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 4731): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4731): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/AndroidRuntime( 4731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 4731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5417)
E/AndroidRuntime( 4731): 	... 11 more
E/ActivityManager(  907): App crashed! Process: com.nero.android.htc.sync
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
W/System.err(  907): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  907): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  907): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.Posix.open(Native Method)
W/System.err(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  907): 	... 12 more
W/System.err(  907): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
W/System.err(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  907): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  907): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.Posix.open(Native Method)
W/System.err(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  907): 	... 14 more
W/System.err(  907): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  907): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
W/System.err(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  907): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  907): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  907): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  907): 	at libcore.io.Posix.open(Native Method)
W/System.err(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  907): 	... 14 more
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448461031742.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  907): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  907): 	... 4 more
W/ActivityManager(  907): Can't addPackageDependency on system process
E/MediaScannerService( 3520): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3520): [handleMessage] --- Should not be here, ignore request. ----
I/ActivityManager(  907): Killing 4110:com.android.vending/u0a75 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4110
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
,I/ActivityManager(  907): Recipient 4110
,D/Process (  907): killProcessQuiet, pid=4110
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10075/pid_4110/cgroup.procs: No such file or directory
,E/MediaScannerServiceEx( 3520): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3520): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3520): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3520): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3520): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3520): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3520): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3520): [AliveExtStorageRows]+65537, 11223344
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{ba6d51c u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/Prism.ItemManager( 1494): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1494): loadItems() com.htc.launcher.pageview.WidgetManager@26dfee4c +
I/Prism.WidgetManager( 1494): onLoadItems() +
I/Prism.ItemManager( 4577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 4577): loadItems() com.htc.launcher.pageview.WidgetManager@1c0f394f +
I/Prism.WidgetManager( 4577): onLoadItems() +
,W/ResourcesManager( 1494): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/HtcModeClient( 3083): handler message = 4011,
,E/HtcModeClient( 3083): Check connection and retry 3 times.,
,W/ResourcesManager( 4577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1494): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
E/qdhwcomposer(  366): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  366): eventControl(0, 1) failed Operation not permitted
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
,E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,E/Prism.WidgetManager( 1494): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1494): onLoadItems() -
I/Prism.ItemManager( 1494): loadItems() com.htc.launcher.pageview.WidgetManager@26dfee4c -
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,W/ResourcesManager( 4577): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920,
,E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  366): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  366): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  366): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  366): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  366): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  366): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8,
E/qdoverlay(  366): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  366): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  366): hwc_set_primary: display commit fail for 0 dpy!
,I/Prism.WidgetManager( 4577): onLoadItems() -,
I/Prism.ItemManager( 4577): loadItems() com.htc.launcher.pageview.WidgetManager@1c0f394f -

```
