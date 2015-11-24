#### Test 50388019b17f598_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of main
I/[PluginManager]RegisterService( 1362): Notify Carousel that a new TabPlugin has been installed!
I/NMT     ( 3438): NMT version: 1.6.1-B006 REL
D/NGFService( 3438): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
D/NGFService( 3438): applyCurrentSystemLanguage +++
D/NGFService( 3438): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3438): LanguageFromSystem: language:en  country:gb
D/NGFService( 3438): Elvis language uses the language: 2
D/NGFService( 3438): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3438): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3438): bluetoothInitialize +++
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@141e4e53:true
D/BluetoothHeadset( 3438): BluetoothHeadset()
D/BluetoothManagerService(  908): registerStateChangeCallback+
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  908): Registered receivers: 7
D/BluetoothManagerService(  908): registerStateChangeCallback+
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  908): Registered receivers: 8
D/NGFService( 3438): cloud_init +++
D/NGFLanguageMgr( 3438): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
D/MediaScannerServiceEx( 3534): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3534): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
D/Process (  908): killProcessQuiet, pid=3206
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
--------- beginning of system
D/PMS     (  908): acquireWL(5e734cb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3534 10017 null
I/ActivityManager(  908): Killing 3206:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17
D/NGFService( 3438): elvisInitalize +++
I/ActivityManager(  908): Recipient 3206
D/NGFService( 3438): elvisInitalize lang = British English
D/NGFService( 3438): elvisInitalize: Freq Type:16000
D/NGFService( 3438): tts_init +++
D/NGFLanguageMgr( 3438): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
D/MtpReceiver( 3534): [MTP][handleUsbStateAsync]+
D/Process (  908): killProcessQuiet, pid=3206
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10023/pid_3206/cgroup.procs: No such file or directory
D/MtpReceiver( 3534): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3534): [MTP][handleUsbState]+
D/MediaScanner( 3534): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
D/NGFLanguageMgr( 3438): LanguageFromSystem: language:en  country:gb
D/NGFLanguageMgr( 3438): language package name = preload_package
I/ActivityManager(  908): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3585 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  908): Killing 1879:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=1879
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/MediaProvider( 3534): bindService() MTP Service Connection.
D/NGFService( 3438): load vocalizer language = British English
E/NGFService( 3438): registerObserver
I/ActivityManager(  908): Recipient 1879
E/SQLiteLog( 3534): (283) recovered 234 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/Process (  908): killProcessQuiet, pid=1879
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10011/pid_1879/cgroup.procs: No such file or directory
D/MtpReceiver( 3534): [MTP][scanExternalVolumeIfNeed] scan external volume
D/NGFService( 3438): onCreate: Battery Level Remaining: 100%
D/NGFService( 3438): onStartCommand(): service start
D/MtpReceiver( 3534): [MTP][handleUsbState]-
D/MtpReceiver( 3534): [MTP][handleMessage]-
D/MtpService( 3534): updating state; isCurrentUser=true, mMtpLocked=false
D/NGFService( 3438): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3438): QuickCall
D/MtpService( 3534): addStorageInternal without MtpServer
D/MtpService( 3534): [MTP][onCreate]-
I/ActionCombine( 3534): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
W/HtcWrapAdjustableCursorFactory( 3585): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 3585): onCreate
V/GetPrviateResource( 3585): GetPrviateResource
V/GetPrviateResource( 3585): GetPrviateResource
D/NGFService( 3438): Elvis is initialization Success
D/NGFService( 3438): bElvisInitializeCompleted = true
D/NGFService( 3438): GrammarState = 0
D/NGFService( 3438): loadGrammar +++
D/NGFService( 3438): loadGrammar asr_grammar
I/NGFService( 3438): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3438): loadGrammar from cache
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishname.lst
D/MtpService( 3534): [MTP] startForeground
W/NMT-OemFile( 3438): fopen(): Failed to open file sysdct.dat
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishartist.lst
D/MtpService( 3534): updating state; isCurrentUser=true, mMtpLocked=false
W/NMT-OemFile( 3438): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
D/PMS     (  908): acquireWL(267b67d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1959 10025 null
D/MtpDatabase( 3534): TotalSize=1867208,MediaCacheLimit=6000
D/DotMatrix( 1198): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 3534): starting MTP server in MTP mode
D/MtpService( 3534): addStorageInternal 65537 /storage/emulated/0
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishplaylist.lst
W/NMT-OemFile( 3438): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
D/MtpService( 3534): [checkStorageState] Storage state - mounted
D/MtpDatabase( 3534): [MTP][addStorage] iHostType =2
D/MtpService( 3534): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
W/NMT-OemFile( 3438): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3438): fopen(): Failed to open file sysdct.dat
I/RemoteViews( 1123): apply : com.android.providers.media 0 8 2 36
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT-OemFile( 3438): fopen(): Failed to open file clm.dat
I/RemoteViews( 1123): apply : com.android.providers.media 0 6 2 51
W/NMT     ( 3438): Fail to open read-stream for file elvisBritish Englishgeneric.lst
D/MessageCustFlag( 3585): sense_version=6.0
D/BTAccessoryUtil( 3585): createReceiver
D/BTAccessoryUtil( 3585): registerReceiver return intent = null
D/MessageCustFlag( 3585): sku_id=99
D/HtcBuildUtils( 3585): getRATByHtcTelephonyCapability:1
W/SystemReader( 3585): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 3585): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 3585): onReceive()
D/ExchangePolicystatus( 3585): onReceive(): ACTION_BOOT_COMPLETED
D/MessageUtils( 3585): Text messaging allow status = allow
D/Messaging( 3585): EAS allow SMS !!!
D/ExchangePolicystatus( 3585): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3585): EAS allow SMS !!!
W/NMT-OemFile( 3438): fopen(): Failed to open file daniel_userdct_eng.dat
D/SettingUtils( 3438): setProcessNormalFlag: true
D/NGFService( 3438): RebuildListener constraintList size 17
D/NGFService( 3438): RebuildListener: onComplete0
D/NGFService( 3438): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3438): switchScenario: htc_screen_140_19
D/NGFService( 3438): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3438): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3438): Loading grammar completed.
D/NGFService( 3438): update contact cache completed
D/SettingUtils( 3438): set Updatge Contact Cache: false
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishname.lst
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishartist.lst
I/ActivityManager(  908): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3622 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/PMS     (  908): acquireWL(9797233): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3585 10067 null
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishsong.lst
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishalbum.lst
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishplaylist.lst
W/NMT     ( 3438): Fail to open read-stream for file serverBritish Englishgeneric.lst
V/SmsReceiverService( 3585): onStart: #1, @606636561
V/SmsReceiverService( 3585): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3585): isCbm: false
D/SmsReceiverService( 3585): isDiscard: false
D/SettingsManager( 3585): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2f05e995
V/SmsReceiverService( 3585): handleBootCompleted
I/iu.UploadsManager( 1959): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
W/ResourcesManager( 3585): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/MediaScannerService( 3534): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3534): [handleMessage] --- Should not be here, ignore request. ----
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1413): sku_id=99
W/MediaScanner( 3534): Error opening directory '/oem/media/', skipping: No such file or directory.
W/MediaScanner( 3534): Error opening directory '/oem/media/', skipping: No such file or directory.
D/MediaScanner( 3534):  prescan time: 218ms
D/MediaScanner( 3534):     scan time: 31ms
D/MediaScanner( 3534): postscan time: 0ms
D/MediaScanner( 3534):    total time: 249ms
D/MediaScanner( 3534): -----------------------------------------------------------------
D/MediaScanner( 3534): firstscan(media) time: 19ms
D/MediaScanner( 3534): secondscan(non-media) time: 8ms
D/MediaScanner( 3534):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Total]    File(Image+Video+Audio+Others) in database : 359
D/SmsReceiverService( 3585): OutBoxSize = 0
D/SmsReceiverService( 3585): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3585): sku_id=99
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/AccFlag ( 1413): sku_id=99
D/MessageCustFlag( 3585): sku_id=99
I/iu.UploadsManager( 1959): End new media; added: 0, uploading: 0, time: 64 ms
D/PMS     (  908): releaseWL(267b67d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
E/cutils-trace( 3643): Error opening trace file: No such file or directory (2)
I/dex2oat ( 3643): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/SmsReceiverService( 3585): sendFirstQueuedMessage end cnt> 0
D/SpaceBufferUtil( 3585): > createBufferFile()
D/SpaceBufferUtil( 3585): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/MediaProvider( 3534): [delete][57]
D/SpaceBufferUtil( 3585): < createBufferFile()
D/MediaProvider( 3534): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3534): [recoverParentNodes] - 0
D/MediaProvider( 3534): [update][16]
D/MediaScannerServiceEx( 3534): [scan] Recover Parent Node is finished!
D/PMS     (  908): releaseWL(5e734cb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
E/MediaScannerServiceEx( 3534): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3534): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3534): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3534): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3534): [update][5]#0#
D/MediaProvider( 3534): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3534): [update][1]#0#
I/Prism.ItemManager( 1473): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1473): loadItems() com.htc.launcher.pageview.WidgetManager@372519a +
I/Prism.WidgetManager( 1473): onLoadItems() +
D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3534): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3534): [update][21]#1#
D/MediaScannerServiceEx( 3534): [AliveExtStorageRows]-0, -1, 0, -1
D/PMS     (  908): acquireWL(2fa49b69): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3534 10017 null
D/MediaScanner( 3534): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
W/ResourcesManager( 1473): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Prism.WidgetManager( 1473): onLoadItems() -
I/Prism.ItemManager( 1473): loadItems() com.htc.launcher.pageview.WidgetManager@372519a -
D/PhoneApp( 1413): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1413): -- N1 =0
D/PhoneApp( 1413): -- N2 =0
D/PhoneApp( 1413): -- N3 =0
I/dex2oat ( 3643): dex2oat took 755.590ms (threads: 4)
D/MediaScanner( 3534):  prescan time: 303ms
D/MediaScanner( 3534):     scan time: 387ms
D/MediaScanner( 3534): postscan time: 1ms
D/MediaScanner( 3534):    total time: 691ms
D/MediaScanner( 3534): -----------------------------------------------------------------
D/MediaScanner( 3534): firstscan(media) time: 290ms
D/MediaScanner( 3534): secondscan(non-media) time: 97ms
D/MediaScanner( 3534):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Total]    File(Image+Video+Audio+Others) in database : 1533
D/MediaProvider( 3534): [delete][11]
D/MediaProvider( 3534): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
D/MediaProvider( 3534): [recoverParentNodes] - 0
D/MediaProvider( 3534): [update][3]
D/MediaScannerServiceEx( 3534): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3534): [updateImage]+
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): VersionName:             1.2.848061
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): VersionCode:             148001212
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3622): ApplicationMonitor {197a2776}: logBasicAppInfo(): BuildConfig.DEBUG:       false
I/art     (  908): Explicit concurrent mark sweep GC freed 17271(868KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 887us total 56.432ms
D/MediaScannerServiceEx( 3534): [updateImage]-0
I/PushClient( 3622): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3653 uid=10079 gids={50079, 9997} abi=armeabi-v7a
D/PMS     (  908): releaseWL(2fa49b69): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3534): [2] scan finished
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3534): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]+131073
D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3534): [update][13]#1#
I/ActivityManager(  908): Killing 3231:com.google.android.onetimeinitializer/u0a27 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3231
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/MediaProvider( 3534): [update][3]#0#
I/ActivityManager(  908): Recipient 3231
,D/Process (  908): killProcessQuiet, pid=3231
W/libprocessgroup(  908): failed to open /acct/uid_10027/pid_3231/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/SMSBackup( 3653): Got ACTION_BOOT_COMPLETED event
D/SMSBackup( 3653): setCheckAlarm
D/SMSBackup( 3653): Next check is scheduled at 60s from now
I/ActivityManager(  908): Killing 3274:com.htc.video/u0a30 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3274
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/MediaProvider( 3534): [update][36]#0#
D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]--1, 0, 0
I/ActivityManager(  908): Recipient 3274
D/Process (  908): killProcessQuiet, pid=3274
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10030/pid_3274/cgroup.procs: No such file or directory
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3534): Process mounted intent for unmounted storage: /storage/usb
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1413, uid=1001, userID:0
D/HtcBroadcastReceiver( 1413): onReceive: android.intent.action.BOOT_COMPLETED
D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]+196609
D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3534): [update][4]#1#
D/MediaProvider( 3534): [update][2]#0#
I/ActivityManager(  908): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3671 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  473): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 140us total 9.621ms
I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 140us total 14.814ms
I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 9.086ms
I/[AppShowMeDebug]BootCompletedReceiver( 3671): received boot complete
I/[AppShowMeDebug]BootCompletedReceiver( 3671): push flag is false, skip check
D/MediaProvider( 3534): [update][69]#0#
D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]--1, 0, 0
I/ActivityManager(  908): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3692 uid=10087 gids={50087, 9997, 1007, 3003, 1028} abi=armeabi-v7a
D/Process (  908): killProcessQuiet, pid=3250
I/ActivityManager(  908): Killing 3250:com.google.android.partnersetup/u0a28 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  908): Recipient 3250
D/Process (  908): killProcessQuiet, pid=3250
W/libprocessgroup(  908): failed to open /acct/uid_10028/pid_3250/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
E/MediaScannerServiceEx( 3534): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3534): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3534): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3534): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3534): [update][3]#0#
D/MediaProvider( 3534): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3534): [update][1]#0#
D/MyReportAgent( 3692): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3534): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3534): [update][12]#1#
D/MyReportAgent( 3692): DatabaseHelper [DatabaseHelper constructor]
D/MyReportAgent( 3692): PolicyStore [Init] Get cached policy bundle
D/MediaScannerServiceEx( 3534): [AliveExtStorageRows]-0, -1, 0, -1
D/PMS     (  908): acquireWL(b047708): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3534 10017 null
D/MyReportAgent( 3692): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
D/MyReportAgent( 3692): ReportServiceHandler on boot complete event 
I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3712 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a
D/MediaScanner( 3534): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3692, uid=10087, userID:0
V/MyReportAgent( 3692): ReportServiceHandler unregister the PowerConnected Listener
D/Process (  908): killProcessQuiet, pid=3295
I/ActivityManager(  908): Killing 3295:com.htc.csrecommend/u0a32 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  908): Recipient 3295
E/cutils-trace( 3672): Error opening trace file: No such file or directory (2)
D/Process (  908): killProcessQuiet, pid=3295
W/libprocessgroup(  908): failed to open /acct/uid_10032/pid_3295/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/UpdaterAPK | UpdaterBootCompleteReceiver( 3712): onReceive() - start htcCheckinService
I/htcCheckinService(  908): htcCheckinProvider V2.1
D/htcCheckinService(  908): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  908): Checkin service onCreate()!
D/CustomizationManager( 3672): ====startRecUseTime====
D/htc.customization.log.level( 3672):  is 
W/CustomizationLogLevel( 3672): Level value is invalid, use default level 2
I/ActivityManager(  908): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.BootReceiver: pid=3742 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/htcCheckinService(  908): onStartCommand()
D/htcCheckinService(  908): onStartCommand() the action name = null
D/htcCheckinService(  908): InitThread start
D/Process (  908): killProcessQuiet, pid=3316
I/ActivityManager(  908): Killing 3316:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  908): Recipient 3316
D/CustomizationManager( 3672):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__203
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__405
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__304
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 3672): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 3672): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3672): Parsing tag category name = system
I/CustomizationCIDLoader( 3672): Parsing tag category name = application
I/CustomizationCIDLoader( 3672): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3672): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3672): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3672): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3672): Parsing tag category name = ACC
D/CustomizationManager( 3672):  Read CID file spent 0.106 (s)
D/CustomizationManager( 3672):  All configurations done spent 0.107 (s)
E/ActTriggerJNI( 3672): open library fail.
D/Process (  908): killProcessQuiet, pid=3316
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_3316/cgroup.procs: No such file or directory
W/ResourceType( 3742): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/ResourcesManager( 3742): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
E/MP-Decision( 2317): Update arg 2
W/asset   (  908): Copying FileAsset 0xb86fcbd8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  908): acquireHCC(183a9a03): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 908 1000 null
D/PMS     (  908): acquireHCC(d32ad80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 908 1000 null
E/MP-Decision( 2317): Update arg 4
D/PMS     (  908): acquireWL(5043ffe): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
E/MP-Decision( 2317): Update arg "0 190 240 240".
E/MP-Decision( 2317): Update arg "0 75 400 400".
I/FeedHostManager( 1473): [onPause]
I/FeedProviderManager( 1473): onPause
I/FeedHostManager( 1473): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3258a26e
I/SocialFeedProvider( 1473): +onPause
I/SocialFeedProvider( 1473): -onPause
I/AnimationUtil(  908): isHTCRecent(HelloWorld/Recent screens.)/5
D/HtcSystemUPManager(  908): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3763 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/HtcModeClient( 3113): handler message = 4011
E/HtcModeClient( 3113): Check connection and retry 1 times.
I/ActivityManager(  908): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3781 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
I/TrimMemoryManager( 1473): [trimMemory] 20
D/StatusBarManagerService(  908): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  908): hiding MENU key
V/AlarmManager(  908): sending alarm PendingIntent{1b16a462: PendingIntentRecord{348609f3 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=37879, Int=0
W/asset   ( 3763): Copying FileAsset 0xb769ed50 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/System.err( 3742): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 3742): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 3742): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
I/WebViewFactory( 3763): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3763): Time to load native libraries: 2 ms (timestamps 8002-8004)
I/LibraryLoader( 3763): Expected native library version number "",actual native library version number ""
I/WorldClock.Global( 3781): isHEPDevice = true
D/PMS     (  908): acquireWL(28d6c46b): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3781 10096 null
V/WebViewChromiumFactoryProvider( 3763): Binding Chromium to main looper Looper (main, tid 1) {9e5954c}
I/LibraryLoader( 3763): Expected native library version number "",actual native library version number ""
W/WorldClock.AlarmService( 3781): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
I/chromium( 3763): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/WorldClock.AlarmUtils( 3781): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994),
,I/ActivityManager(  908): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=3805 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/BrowserStartupController( 3763): Initializing chromium process, singleProcess=true,
W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring,
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
E/SysUtils( 3763): ApplicationContext is null in ApplicationStatus
W/ContextImpl(  908): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
W/chromium( 3763): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/WorldClock.Global( 3781): isHEPDevice = true,
W/chromium( 3763): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/AntHalService(  908): onCreate() entered
I/ActivityManager(  908): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3828 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a,
E/libEGL  ( 3763): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3763): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
D/JAntJava(  908): Calling nativeJAnt_Create
I/Adreno-EGL( 3763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 3763): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3763): Build Date: 12/11/14 Thu
I/Adreno-EGL( 3763): Local Branch: 
I/Adreno-EGL( 3763): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 3763): Local Patches: NONE
I/Adreno-EGL( 3763): Reconstruct Branch: NOTHING
,D/JAntJava(  908): create: nativeJAnt_Create returned success
D/AntHalService(  908): JAntJava create success
,D/MediaScanner( 3534):  prescan time: 112ms
D/MediaScanner( 3534):     scan time: 426ms
D/MediaScanner( 3534): postscan time: 1ms
,D/MediaScanner( 3534):    total time: 539ms
D/AntHalService(  908): onStartCommand() entered
D/MediaScanner( 3534): -----------------------------------------------------------------
D/MediaScanner( 3534): firstscan(media) time: 304ms
D/MediaScanner( 3534): secondscan(non-media) time: 122ms
D/MediaScanner( 3534):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3534):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3534):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3534):  [Total]    File(Image+Video+Audio+Others) in database : 1533
,I/WorldClock.AlarmUtils( 3781): Cancel any alarm from alarm manager,
I/WorldClock.AlarmUtils( 3781): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon,
I/IntentController( 1123): receive(android.intent.action.ALARM_CHANGED,1,false)
W/ResourceType( 3805): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
,W/ResourcesManager( 3805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  908): releaseWL(28d6c46b): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,I/ActivityManager(  908): Killing 2649:com.htc.contacts/u0a40 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=2649
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/Tiber/HtcIrService( 3805): Created by Thread:1
D/MediaProvider( 3534): [delete][40]
D/MediaProvider( 3534): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3534): [recoverParentNodes] - 0
D/MediaProvider( 3534): [update][5]
D/MediaScannerServiceEx( 3534): [scan] Recover Parent Node is finished!
I/Tiber/PeelUtils( 3805): Create new PeelUtils
D/MediaScannerServiceEx( 3534): [updateImage]+
I/ActivityManager(  908): Recipient 2649
I/Tiber/PeelUtils( 3805): loadDB: load data from database
I/HtcStatusBarManagerWrapper( 3805): glow:20
D/MediaScannerServiceEx( 3534): [updateImage]-0
,W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490),
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18c6f236:true
,D/BluetoothAdapter( 3763): 639010459: getState() :  mService = null. Returning STATE_OFF
,D/Process (  908): killProcessQuiet, pid=2649
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  908): failed to open /acct/uid_10040/pid_2649/cgroup.procs: No such file or directory
,I/IntentController( 1123): receive(com.htc.intent.action.STATUS_BAR_GLOW,1,false),
D/PMS     (  908): releaseWL(b047708): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,I/Tiber/PeelUtils( 3805): loadDB(), room count : 0,
,I/Tiber/PeelUtils( 3805): loadDB: load updated data from database finished
I/Tiber/HtcIrService( 3805): Created by Thread:1 finished
,D/MediaScannerServiceEx( 3534): [3] scan finished
,D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3534): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]+131073,
,E/UpdateRequestReceiver( 3828): ignoring update request,
,E/UpdateRequestReceiver( 3828): ignoring update request
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3742): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
,E/UpdateRequestReceiver( 3828): ignoring update request
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3742): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
,E/UpdateRequestReceiver( 3828): ignoring update request
,E/UpdateRequestReceiver( 3828): ignoring update request
,E/UpdateRequestReceiver( 3828): ignoring update request
,I/PhoneStatusBar( 1123): glow(20,0,0)
,D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3534): [update][31]#1#
,D/MediaProvider( 3534): [update][3]#0#
,W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring,
I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3874 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
D/Process (  908): killProcessQuiet, pid=3336
I/ActivityManager(  908): Killing 3336:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,D/Messaging( 3585): supportCMAS(SIE)/init? false/true
W/AwContents( 3763): onDetachedFromWindow called when already detached. Ignoring
D/MmsConfig( 3585): networkCode: 
D/MmsConfig( 3585): SIE smsPri: null
D/MmsConfig( 3585): networkCode: 
,D/MmsConfig( 3585): packageName: com.htc.vvm.att does not exist
D/Messaging( 3585): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 3585): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3585): 
D/MmsAsyncWorkHandler( 3585): HM tk = 20001
D/ReportIndicatorCache( 3585): MSG_QUERY_REPORTS >>
,D/SystemWebViewEngine( 3763): CordovaWebView is running on device made by: HTC
,I/ActivityManager(  908): Recipient 3336
,I/Messaging( 3585): mccmnc> 
,D/DraftCache( 3585): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3585): [DraftCache/1] refresh
,D/MmsConfig( 3585): networkCode: 
,D/Messaging( 3585): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 3585): sense_version=6.0
,D/Process (  908): killProcessQuiet, pid=3336
,W/libprocessgroup(  908): failed to open /acct/uid_10042/pid_3336/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Jerry   ( 3585): start to preload cursor >>>>>>>
W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 104
D/AccFlag ( 1413): sku_id=99
,D/DraftCache( 3585): [DraftCache/431] rebuildCache
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102,
D/MmsSmsV2Provider( 1413):  slotId = -1000
D/MmsSmsV2Provider( 1413): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,W/System.err(  908): java.lang.Throwable: stack dump
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 104
D/MmsSmsV2Provider( 1413):  slotId = -1000
,D/MmsSmsV2Provider( 1413): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2548b158:true
,D/PhoneStorageUtil( 3585): HtcWrapEnvironment.getSupportedStorages() >1
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/MmsSmsV2Provider( 1413):  slotId = -1000
D/BluetoothAdapter( 3742): 741070453: getState() :  mService = null. Returning STATE_OFF
,D/PhoneStorageUtil( 3585): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3585): createReceiver
,D/Messaging( 3585): ViewCache CreatePreload
D/Messaging( 3585): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/Jerry   ( 1413): URI_DRAFT
,D/DraftCache( 3585): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3585): [DraftCache/431] rebuildCache time: 1
D/MmsAsyncWorkHandler( 3585): 
D/MmsAsyncWorkHandler( 3585): HM tk = 20002
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/MmsSmsV2Provider( 1413):  slotId = -1000
D/MmsSmsV2Provider( 1413): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 3585): mNeedToUpdateDate2: false
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1413):  slotId = -1000
D/MmsSmsV2Provider( 1413): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 3585): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/AccFlag ( 1413): sku_id=99
D/TelephUtils( 1413): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 104
V/MmsProvider( 1413): Update uri=content://mms, match=0
V/MmsProvider( 1413): selection=st=129 AND m_type!=134
D/Cust_MMSMS( 3585): _has_set_default_values_2=true
D/Messaging( 3585): Reset downloading state: 0
V/MmsSystemEventReceiver( 3585): TransactionService is going to be woken up.
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1413): sku_id=99
D/CIRControlWrapper( 3742): hasIrEmitter = true
D/MsgPreferenceUtils( 3585): def_index: 0
,V/TransactionService( 3585): 1-Creating TransactionService
,D/MsgPreferenceUtils( 3585): globalIndex = 1
,D/MsgPreferenceUtils( 3585): phone state: true
D/MsgPreferenceUtils( 3585): sd state: false
D/MsgPreferenceUtils( 3585): vIndex = 0
,D/PMS     (  908): acquireWL(1abb975d): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 3742 10091 null
,D/PMS     (  908): releaseWL(1abb975d): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 null,
,V/TransactionService( 3585): onStartCommand: 1
D/MmsSystemEventReceiver( 3585): unRegisterForConnectionStateChanges
V/TransactionService( 3585): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3585): Loading previous transactions.
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 104
D/AccFlag ( 1413): device_type: 1
,D/Atlas   ( 3763): Validating map...
D/TransactionService( 3585): Force set service start id to 1
V/TransactionService( 3585): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3585): unRegisterForConnectionStateChanges
V/TransactionService( 3585): Destroying TransactionService,
D/TransactionService( 3585): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3585): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/chromium( 3763): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/DeviceManagement( 3874): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=3874 dbg=false s=true
,I/DeviceManagement( 3874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 3874): WorkflowService: Starting workflow service
,I/DeviceManagement( 3874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@2616869b] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3874): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3874): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 3874): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 3874): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3874): BackgroundController: *** Update after boot...
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/art     (  908): Explicit concurrent mark sweep GC freed 15255(750KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 956us total 76.961ms
,I/art     (  908): WaitForGcToComplete blocked for 44.060ms for cause HeapTrim
,I/InputMethodManager( 3763): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@82f1981, mServedView=org.apache.cordova.engine.SystemWebView{10995a26 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2a272667
,I/GoogleHttpClient( 1764): GMS http client unavailable, use old client
,I/InputMethodManagerService(  908): Disable input method client, pid=1473
D/StatusBarManagerService(  908): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  908): Enable input method client, pid=3763
,D/MediaProvider( 3534): [update][274]#0#
,D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]--1, 0, 0
,I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +708ms,
I/ActivityManager(  908): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3930 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3534): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]+196609
,D/PMS     (  908): releaseWL(5043ffe): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/BindingManager( 3763): Cannot call determinedVisibility() - never saw a connection for the pid: 3763,
,W/XT9_C   ( 1272): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
,I/XT9_C   ( 1272): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1272): [T9_ReleaseBuffer] Reset LDB#1,
D/XT9_C   ( 1272): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/chromium( 3763): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/MediaProvider( 3534): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,I/DeviceManagement( 3874): BackgroundController: Invariants are unchanged.
,D/MediaProvider( 3534): [update][54]#1#
,D/MediaProvider( 3534): [update][3]#0#,
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...,
,D/JsMessageQueue( 3763): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3763): Unable to open asset URL: file:///android_asset/www/jxcore.js,
,I/htcbackup-core( 3930): ModelRegistry: Loading model meta data from resources...,
,I/Tiber/HtcIrService( 3805): onDestroy called
,I/Tiber/PeelUtils( 3805): Stop CIR service...
D/Tiber/HtcIrService( 3805): If IR had killed, to remove temp data in videocenter_had_killed
,D/Process (  908): killProcessQuiet, pid=3353
I/ActivityManager(  908): Killing 3353:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3353
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,D/MediaProvider( 3534): [update][113]#0#
,D/MediaScannerServiceEx( 3534): [disAliveExtStorageRows]--1, 0, 0
,D/Process (  908): killProcessQuiet, pid=3353
W/libprocessgroup(  908): failed to open /acct/uid_10048/pid_3353/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/DeviceManagement( 3874): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/ActivityManager(  908): Killing 3371:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
I/DeviceManagement( 3874): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
D/Process (  908): killProcessQuiet, pid=3371
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/DeviceManagement( 3874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
I/DeviceManagement( 3874): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): Perf: *** Cache update - start...
I/DeviceManagement( 3874): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3874): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3874): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 3874): Perf: Scan enabled apps - start...
,I/ActivityManager(  908): Recipient 3371,
,D/jxcore_app_log( 3763): JniHelper::setJavaVM(0xb7616b98), pthread_self() = -1198993464,
D/JX-Cordova( 3763): jxcore cordova android initializing
,I/DeviceManagement( 3874): EnabledAppBuilder: Examining 267 installed apps for DM enabled apps...
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500050, versionName=6.5.838445,
,D/Process (  908): killProcessQuiet, pid=3371
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10050/pid_3371/cgroup.procs: No such file or directory
,W/jxcore-log( 3763): Initializing JXcore engine
W/jxcore-log( 3763): JXcore engine is ready,
,W/jxcore-log( 3763): Starting JXcore engine
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031392, versionName=6.3.851500,
,W/ResourcesManager( 3874): Asset path '/system/framework/com.android.future.usb.accessory.jar' does not exist or contains no resources.
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444606881, versionName=4.2.848011
,W/ResourcesManager( 3874): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001301, versionName=6.0.847523
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/jxcore-log( 3763): Platform android,
W/jxcore-log( 3763): 
W/jxcore-log( 3763): Process ARCH arm
W/jxcore-log( 3763): 
,W/ResourcesManager( 3874): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 3874): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/jxcore-log( 3763): JXcore Cordova bridge is ready!,
I/jxcore-log( 3763): 
W/jxcore-log( 3763): JXcore engine is started
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001280, versionName=6.5.847469,
,E/jxcore-log( 3763): >> HTC-HTC One_M8
E/jxcore-log( 3763): 
,W/ResourceType( 3874): ResTable_typeSpec entry count inconsistent: given 1, previously 1426,
I/jxcore-log( 3763): Total memory 1912020992,
I/jxcore-log( 3763): 
W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/jxcore-log( 3763): Free memory 162361344
I/jxcore-log( 3763): 
I/jxcore-log( 3763): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3763): 
,I/jxcore-log( 3763): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3763): 
I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, versionCode=250081396, versionName=2.7.845092
,I/jxcore-log( 3763): userPath [ 'www' ],
I/jxcore-log( 3763): 
,I/jxcore-log( 3763): Size 1080 1776
I/jxcore-log( 3763): 
,I/jxcore-log( 3763): Screen Brightness 142
I/jxcore-log( 3763): 
E/jxcore-log( 3763): Dummy Error Log.
E/jxcore-log( 3763): 
,W/ResourceType( 3874): ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001212, versionName=1.2.848061
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,W/ResourcesManager( 3874): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 3874): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3874): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001186, versionName=2.2.821083,
,I/DeviceManagement( 3874): EnabledAppBuilder: Found 9 DM enabled apps.,
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.videohub.ui
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns,
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 3874): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 3874): Perf: Scan enabled apps - complete: 499 ms
,I/DeviceManagement( 3874): Perf: *** Enabled app cache update - complete: 500 ms
,I/DeviceManagement( 3874): Perf: *** Config cache update - start...
,I/DeviceManagement( 3874): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3874): ConfigCacheController: *** Device manifest update is pending...
,I/DeviceManagement( 3874): ConfigCacheController: *** Sending device manifest...
,I/art     ( 3874): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,I/art     ( 3874): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,V/SmsReceiverService( 3585): updateNotificationAndShortcutStatus: ,
D/MessagingNotification( 3585): New incoming message, can't cancel notification now
D/MessagingNotification( 3585): newMsgCnt: 0, false
W/System.err( 3874): Starting the internal HTTP client
,D/Process (  908): killProcessQuiet, pid=3390
I/ActivityManager(  908): Killing 3390:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3390,
,I/DeviceManagement( 3874): DeviceClientResource: Active network...,
I/DeviceManagement( 3874):   No active network
,I/DeviceManagement( 3874): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 3874): BackgroundController: *** Network unavailable!
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=3874, uid=10105, userID:0
,I/DeviceManagement( 3874): Perf: *** Config cache update - complete: 211 ms
I/DeviceManagement( 3874): Perf: *** Cache update - complete: 712 ms
,I/DeviceManagement( 3874): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@2616869b]
,D/Process (  908): killProcessQuiet, pid=3390
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10051/pid_3390/cgroup.procs: No such file or directory
,D/PMS     (  908): releaseWL(9797233): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,I/DeviceManagement( 3874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3874): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3874): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,I/DeviceManagement( 3874): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 3874): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.backup
,I/DeviceManagement( 3874): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00]
,I/DeviceManagement( 3874): WorkflowService: Stopping workflow service
,I/ActivityManager(  908): Killing 3134:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=3134
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/htcbackup-core( 3930): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/jxcore-log( 3763): getBuffer is called!!!!
I/jxcore-log( 3763): 
,I/ActivityManager(  908): Recipient 3134
,I/ActivityManager(  908): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/Process (  908): killProcessQuiet, pid=3419,
I/ActivityManager(  908): Killing 3419:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  908): Recipient 3419
,D/Process (  908): killProcessQuiet, pid=3134
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_3134/cgroup.procs: No such file or directory
,D/PMS     (  908): releaseHCC(183a9a03): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  908): releaseHCC(d32ad80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/MP-Decision( 2317): Update arg 1
,D/Process (  908): killProcessQuiet, pid=3419
W/libprocessgroup(  908): failed to open /acct/uid_10057/pid_3419/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/HtcModeClient( 3113): handler message = 4009
,I/HtcModeClient( 3113): start to setup the connection
,I/ActivityManager(  908): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3980 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  908): Killing 3457:com.htc.lmw/u0a61 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3457
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/art     (  473): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 141us total 9.962ms
,I/ActivityManager(  908): Recipient 3457
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 169us total 10.555ms
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 163us total 11.386ms
,D/Process (  908): killProcessQuiet, pid=3457
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10061/pid_3457/cgroup.procs: No such file or directory
,D/ResetNotifyBootCompleteReceiver( 1413): Receive bootcomplete intent
,I/HtcCupdXmlParser( 3980): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4000 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 3980): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/HtcCupdXmlParser( 3980): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,D/QXDM2SD:HtcNative( 1413): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4020 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/AlarmManager(  908): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  908): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  908): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4037 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 3482:com.android.managedprovisioning/u0a66 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3482
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3482,
,V/Settings:HtcSettingsApplication( 4020): [4020/4020] onCreate()
,W/ContextImpl( 4020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
,D/Process (  908): killProcessQuiet, pid=3482
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10066/pid_3482/cgroup.procs: No such file or directory
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  908): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4072 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
,I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2826532c
,I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@5b101f5,
,I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1374ab8a
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  908): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.android.mail,
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
D/Process (  908): killProcessQuiet, pid=2083
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
I/ActivityManager(  908): Killing 2083:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
,W/ResourcesManager( 4072): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  908): Recipient 2083
,D/HtcFingerPrintQuickLaunchProvider( 4055): -onCreate()
,D/Process (  908): killProcessQuiet, pid=2083,
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10025/pid_2083/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4072): Created com.android.providers.calendar.CalendarAlarmManager@9e5954c(com.htc.providers.calendar.HtcCalendarProvider@2f05e995),
D/CalendarProvider2( 4072): wait start:true
,V/Settings:HtcSettingsApplication( 4055): [4055/4055] onCreate(),
W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,D/CalendarProvider2( 4072): wait end:false
D/TetherSettings( 4055): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4055): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4055): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4055): Cust_ConnectToPC   : spcsc>false
D/        ( 4055): Cust_ConnectToPC   : IPT>true
D/        ( 4055): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4055): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  908): Killing 1959:com.google.android.gms/u0a25 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=1959
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 1959,
,D/Process (  908): killProcessQuiet, pid=1959
,D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10025/pid_1959/cgroup.procs: No such file or directory
,E/SmartNS_Utility( 4055): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 4055): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4055): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 4055): setISNotification
D/SmartNS_Utility( 4055): usb_cable_connect = 1
D/SmartNS_Utility( 4055): usb_denied = 0
I/SmartNS_PSService( 4055): usb notificaiton:true
,E/WifiStateMachine(  908): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4055): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/ActionCombine( 1198): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/DotMatrix( 1198): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 4055): usb_cable_connect = 1
,D/SmartNS_Utility( 4055): usb_denied = 0
I/SmartNS_PSService( 4055): usb notificaiton:true
E/WifiStateMachine(  908): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1123): setHTCTheme(com.android.settings,true,33751145)
D/DotMatrix( 1198): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/Process (  908): killProcessQuiet, pid=3622
I/ActivityManager(  908): Killing 3622:com.htc.cs.pns/u0a74 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/RemoteViews( 1123): apply : com.android.settings 3 6 1 36
,I/ActivityManager(  908): Recipient 3622
,I/RemoteViews( 1123): reapply : com.android.settings 0 36,
,D/Process (  908): killProcessQuiet, pid=3622
,W/libprocessgroup(  908): failed to open /acct/uid_10074/pid_3622/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4098 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/SmartDim(  908): Init customizeScreenOffDelayClass error,
,E/MP-Decision( 2317): Update arg 2,
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{3457a3eb u0 ReceiverList{5570b3a 908 system/1000/u0 local:8075265}}
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2bf739cf, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = Accelerometer Sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2bf739cf, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20073492
W/SensorService(  908): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b8f2ae7
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@2bf739cf
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2bf739cf, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 3
W/SensorService(  908): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2bf739cf, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20073492
W/SensorService(  908): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b8f2ae7
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@2bf739cf
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  908): killProcessQuiet, pid=3653,
I/ActivityManager(  908): Killing 3653:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  908): Recipient 3653
,D/Process (  908): killProcessQuiet, pid=3653
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10079/pid_3653/cgroup.procs: No such file or directory
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4119 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Atfwd_Sendcmd(  481): AtCmdFwd service not published, waiting... retryCnt : 3
,E/MP-Decision( 2317): Update arg 1
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4119, uid=10075, userID:0,
,D/Finsky  ( 4119): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,D/Finsky  ( 4119): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  908): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4158 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,W/Settings( 4119): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 4119): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4158): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4158): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4119, uid=10075, userID:0,
,I/MultiDex( 4158): VM with version 2.1.0 has multidex support
,I/MultiDex( 4158): install
I/MultiDex( 4158): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4158): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4158): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4158): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1150e386: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4158): Installed default security provider GmsCore_OpenSSL
,I/art     (  908): Explicit concurrent mark sweep GC freed 12991(678KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 16MB/24MB, paused 817us total 76.195ms
,D/Volley  ( 4119): [541] DiskBasedCache.clear: Cache cleared.,
D/Volley  ( 4119): [548] DiskBasedCache.clear: Cache cleared.
,D/Process (  908): killProcessQuiet, pid=3671,
I/ActivityManager(  908): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4195 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  908): Killing 3671:com.htc.showme/u0a85 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3671
,D/Process (  908): killProcessQuiet, pid=3671,
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10085/pid_3671/cgroup.procs: No such file or directory
,D/Finsky  ( 4119): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4119): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4119): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 4195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4119): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 4195): VM with version 2.1.0 has multidex support
,I/MultiDex( 4195): install
I/MultiDex( 4195): VM has multidex support, MultiDex support library is disabled.
,D/AutoSetting( 1362): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1362): Util - check NLP state, Allowned:true, Enabled:true
D/AutoSetting( 1362): Util - no network available!
D/AutoSetting( 1362): service - requestNLP() network is not available
,I/ActivityManager(  908): Killing 3692:com.htc.feedback/u0a87 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3692
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3692,
,D/Process (  908): killProcessQuiet, pid=3692
W/libprocessgroup(  908): failed to open /acct/uid_10087/pid_3692/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/Finsky  ( 4119): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/JNIHelp ( 4195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/CalendarProvider2( 4072): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4072): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  908): killProcessQuiet, pid=3712
,I/ActivityManager(  908): Killing 3712:com.htc.updater/u0a88 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3712
,W/ActivityThread( 4195): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3512ccd4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4195): Installed default security provider GmsCore_OpenSSL
,D/Process (  908): killProcessQuiet, pid=3712
W/libprocessgroup(  908): failed to open /acct/uid_10088/pid_3712/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  908): killProcessQuiet, pid=3781
I/ActivityManager(  908): Killing 3781:com.htc.android.worldclock/u0a96 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  908): Recipient 3781
,D/Process (  908): killProcessQuiet, pid=3781,
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10096/pid_3781/cgroup.procs: No such file or directory
,V/GLSUser ( 1764): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/PMS     (  908): acquireWL(31664690): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1764 10025 null
,V/GmsCoreStatsServiceLauncher( 4195): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,E/MP-Decision( 2317): Update arg 2
,I/NotificationStore( 1764): System rebooted after Notification storage file was last written,
I/NotificationStore( 1764): Deleting the file
,D/PMS     (  908): releaseWL(31664690): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1764): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4195): Found 10025
,D/FileApkUtils( 4195): Spent 20ms computing apk sha1.,
,D/FileApkUtils( 4195): Module already staged or being staged:chimera-modules/MapsModule.apk
,E/MP-Decision( 2317): Update arg 1
,I/art     ( 4195): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4195): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4195): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/PMS     (  908): acquireWL(2454ae9a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4195 10025 null
,I/art     ( 1764): Explicit concurrent mark sweep GC freed 6097(365KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 3MB/5MB, paused 291us total 22.410ms
,D/GmsModuleFndr( 4195): Beginning GMS chimera module scan,
,W/asset   ( 4195): Copying FileAsset 0xb876e1e0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.,
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1764, uid=10025, userID:0,
,D/PMS     (  908): acquireWL(2a5d73cb): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4195 10025 WorkSource{10025 com.google.android.gms},
,D/GmsModuleFndr( 4195): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
D/ChimeraCfgMgr( 4195): Beginning module configuration check
,D/ChimeraCfgMgr( 4195): Module APKs unchanged, check complete,
,D/PMS     (  908): acquireWL(84eb2c1): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4195 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  908): acquireWL(1a2b4654): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4195 10025 null,
,D/PMS     (  908): acquireWL(cd2b9fd): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4195 10025 WorkSource{10025 com.google.android.gms},
D/GCM     ( 4195): COMPAT: Multi user not supported
,D/GCM     ( 1764): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/PMS     (  908): acquireWL(c95f8f9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4195 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  908): releaseWL(2a5d73cb): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  908): releaseWL(2454ae9a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  908): releaseWL(cd2b9fd): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 4195): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/PMS     (  908): acquireWL(1790bec): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1697 10025 WorkSource{10025 com.google.android.gms},
I/CheckinService( 4195): Disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4195, uid=10025, userID:0,
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4195, uid=10025, userID:0
,I/GCoreUlr( 1697): DispatchingService.onCreate()
,D/SystemUpdateService( 4195): onCreate
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4195, uid=10025, userID:0,
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
,D/SystemUpdateService( 4195): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0,
I/ConfigService( 1764): onCreate
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4195, uid=10025, userID:0,
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4195, uid=10025, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4195, uid=10025, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4195, uid=10025, userID:0,
,I/ConfigFetchService( 4195): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,V/AuthZen ( 4195): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 4195): Handling event: android.intent.action.BOOT_COMPLETED,
,D/PMS     (  908): acquireWL(ffc04ee): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1697 10025 WorkSource{10025 com.google.android.gms},
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4195, uid=10025, userID:0
W/BaseAppContext( 4195): Using Auth Proxy for data requests.
,I/GCoreUlr( 1697): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/art     ( 4195): Suspending all threads took: 8.756ms
,I/art     ( 4195): Background sticky concurrent mark sweep GC freed 9473(837KB) AllocSpace objects, 16(256KB) LOS objects, 21% free, 4MB/5MB, paused 10.830ms total 42.072ms
,D/PMS     (  908): acquireWL(c1ded23): PARTIAL_WAKE_LOCK  Icing 0x1 4195 10025 WorkSource{10025 com.google.android.gms}
,I/GLSUser ( 4195): [ChannelManager] Attempting to channel bind connection HttpClient.,
,W/System.err(  908): java.lang.Throwable: stack dump
,W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22ef67d9:true
,I/CheckinService( 4195): Checking schedule, now: 1448385992697 next: 1448950570425
,I/CheckinService( 4195): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4195, uid=10025, userID:0
,I/ConfigFetchService( 4195): service connected
,I/SystemUpdateService( 4195): cancelUpdate (empty URL),
I/SystemUpdateService( 4195): active receiver: disabled,
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4195, uid=10025, userID:0
,D/PMS     (  908): releaseWL(c95f8f9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
,I/GLSUser ( 4195): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/PMS     (  908): releaseWL(c1ded23): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,D/ConfigFetchService( 4195): ConfigApi connection successful.
,D/PMS     (  908): releaseWL(84eb2c1): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
D/SystemUpdateService( 4195): onDestroy
I/ActivityManager(  908): Resuming delayed broadcast
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1697, uid=10025, userID:0,
,D/ChimeraCfgMgr( 4195): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 4195): Fetching signing key...
,I/AuthZen ( 4195): Signing key fetched successfully!
,D/ChimeraCfgMgr( 4195): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,W/BaseAppContext( 4195): Using Auth Proxy for data requests.,
,I/AuthZen ( 4195): Starting Enrollment...
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4298 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AuthZen ( 4195): getting auth token. Attempt 0
,I/Kids    ( 4195): [KidAccountFixer] No network connection
,I/GLSActivity( 1764): [ac] getting account id,
,D/PMS     (  908): releaseWL(1790bec): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10025 com.google.android.gms}
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 13260(802KB) AllocSpace objects, 4(64KB) LOS objects, 43% free, 5MB/9MB, paused 5.298ms total 59.891ms
,I/GLSUser ( 1764): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1764): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1764): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227,
,W/ResourcesManager( 4298): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1764): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1764): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1764): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1764): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/AuthZen ( 4195): Error getting auth token
E/AuthZen ( 4195): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4195): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4195): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4195): Failed to do enrollment for account: thalitester@gmail.com
,E/AuthZen ( 4195): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4195): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4195): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GCoreUlr( 1697): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]},
D/a       ( 4195): Opening database auth.proximity.permit_store...
,D/PMS     (  908): acquireWL(1bf93f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1697 10025 WorkSource{10025 com.google.android.gms},
D/PMS     (  908): releaseWL(1bf93f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/GCoreUlr( 1697): Unbound from all location providers
D/PMS     (  908): releaseWL(ffc04ee): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,D/AuthZenTransactionCache( 4195): Initialized cache in: /data/data/com.google.android.gms/files,
D/AuthZenTransactionCache( 4195): Clearing transaction cache
,I/GCoreUlr( 1697): DispatchingService.onDestroy()
,D/PMS     (  908): acquireWL(221093f1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1697 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  908): releaseWL(221093f1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1697): Unbound from all location providers
,D/PMS     (  908): acquireWL(2b889bd6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(2b889bd6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4298): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4298): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3585): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/MmsCustomizationProvider( 3585): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,I/Babel_SMS( 4298): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml,
I/Babel_SMS( 4298): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4298): canonicalizeMccMnc: invalid mccmnc ,
,I/Babel_SMS( 4298): MmsConfig.loadFromResources
,E/Babel_SMS( 4298): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4298): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4298, uid=10120, userID:0
,W/Settings( 4298): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4298): startup - clean,
,I/Babel   ( 4298): deleted: false for 0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0,
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4298, uid=10120, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4298, uid=10120, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4298, uid=10120, userID:0
,W/VideoCapabilities( 4298): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4298): Unsupported mime video/x-ms-wmv
,W/AudioCapabilities( 4298): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4298): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4298): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4298): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4298): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4298): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4298): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4298): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4298): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 4298): onServiceConnected,
,W/Babel   ( 4298): Attempted to change video mute state without an active call.
,I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4331 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  473): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 132us total 9.559ms
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 165us total 10.231ms,
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 171us total 11.207ms
,I/art     (  908): Explicit concurrent mark sweep GC freed 17677(971KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 16MB/24MB, paused 795us total 65.586ms
,I/HtcModeClient( 3113): handler message = 4011,
E/HtcModeClient( 3113): Check connection and retry 2 times.
,W/ResourcesManager( 4331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1764): Explicit concurrent mark sweep GC freed 7690(425KB) AllocSpace objects, 2(32KB) LOS objects, 50% free, 3MB/7MB, paused 476us total 31.596ms
,V/JNIHelp ( 4331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4331): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4331): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 4331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/cutils-trace( 4360): Error opening trace file: No such file or directory (2)
,I/dex2oat ( 4360): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads229115837.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads229115837.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 4331): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 4331): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4331): [NET] android_getaddrinfofornet-, SUCCESS
,I/dex2oat ( 4360): dex2oat took 59.444ms (threads: 4),
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4331): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4331): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4331): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4331): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4331): Found 10025,
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4331): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,I/ActivityManager(  908): Killing 3742:com.htc.videocenter/u0a91 (adj 15): empty #17,
D/Process (  908): killProcessQuiet, pid=3742
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3742,
,D/Process (  908): killProcessQuiet, pid=3742,
W/libprocessgroup(  908): failed to open /acct/uid_10091/pid_3742/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  908): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4414 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  908): Killing 3828:com.google.android.configupdater/u0a104 (adj 15): empty #17,
D/Process (  908): killProcessQuiet, pid=3828
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3828,
,D/Process (  908): killProcessQuiet, pid=3828
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
W/libprocessgroup(  908): failed to open /acct/uid_10104/pid_3828/cgroup.procs: No such file or directory
,D/LocationManagerService(  908): getProviders()=[passive, network],
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4445 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4414, uid=10089, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4414, uid=10089, userID:0
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{306eeeca u0 com.google.android.gms/.gcm.GcmService}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4414, uid=10089, userID:0
,I/ActivityManager(  908): Killing 3805:com.htc.tiber2/u0a91 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=3805
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  908): Recipient 3805,
,E/WifiTrafficPoller(  908): ADD_CLIENT: 6
D/WifiService(  908): New client listening to asynchronous messages
,I/VelvetNetworkClient( 4414): Network connection not availble
,D/Process (  908): killProcessQuiet, pid=3805,
W/libprocessgroup(  908): failed to open /acct/uid_10091/pid_3805/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4474 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  908): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  908): MONITOR_LOG
W/Settings:Agent(  908): name: bluetooth_on
W/Settings:Agent(  908): value: 0
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1090
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  908): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  908): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  908): 
D/WifiService(  908): New client listening to asynchronous messages
W/Settings:Agent(  908): << traceCallingStack(): 0(ms)
D/BluetoothManagerService(  908): Message: MESSAGE_DISABLE
E/WifiTrafficPoller(  908): ADD_CLIENT: 7
,D/WifiManager( 3763): setWifiEnabled: Base Package Name=com.example.hello, uid=10380,
W/Settings:Agent(  908): MONITOR_LOG
D/WifiService(  908): setWifiEnabled: false pid=3763, uid=10380
W/Settings:Agent(  908): name: wifi_on
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings:Agent(  908): value: 0
I/WifiService(  908): isSprintWifiRestricted(): false
W/Settings:Agent(  908): >> traceCallingStack()
I/WifiService(  908): isMdmWifiRestricted(): false
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1574
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
,W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  908): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  908): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  908): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
,W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 4(ms)
I/jxcore-log( 3763): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 3763): 
I/jxcore-log( 3763): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3763): 
,W/LocationOracleImpl( 4414): Best location was null,
,I/WebViewFactory( 4414): Loading com.google.android.webview version 44.0.2403.90 (code 240309000),
,I/LibraryLoader( 4414): Time to load native libraries: 1 ms (timestamps 4175-4176),
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
,W/art     ( 4414): Attempt to remove local handle scope entry from IRT, ignoring,
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/art     ( 4414): Attempt to remove local handle scope entry from IRT, ignoring
,D/Process (  908): killProcessQuiet, pid=3930,
I/ActivityManager(  908): Killing 3930:com.htc.backup/u0a118 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3930
,I/Gmail   ( 4474): getAccountsCursor,
,E/cutils-trace( 4492): Error opening trace file: No such file or directory (2)
,D/Process (  908): killProcessQuiet, pid=3930,
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10118/pid_3930/cgroup.procs: No such file or directory
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GAV2    ( 4474): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,D/CustomizationManager( 4492): ====startRecUseTime====,
D/htc.customization.log.level( 4492):  is 
W/CustomizationLogLevel( 4492): Level value is invalid, use default level 2
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 4474): Error finding the version of the Email provider.....
E/Gmail   ( 4474): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4474): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4474): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4474): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4474): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4474): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4474): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4474): We do not support migrating this version of the Email provider.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4474, uid=10115, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4474, uid=10115, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4474, uid=10115, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4474, uid=10115, userID:0
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4474): getAccountsCursor,
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4474, uid=10115, userID:0,
,I/ActivityManager(  908): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=4541 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4474, uid=10115, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4474, uid=10115, userID:0
,I/Gmail   ( 4474): Observing account changes for notifications
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/CustomizationManager( 4492):  Read ACC file spent 0.052 (s),
,D/CIDMapFileReader( 4492): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__203,
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__304
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 4492): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__016
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 4492): Parsing tag item name = HTC__K18
,D/CIDMapFileReader( 4492): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 4492): full path : /system/customize/CID/HTC__032.xml
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4474, uid=10115, userID:0,
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4474, uid=10115, userID:0
,E/ActivityThread( 4474): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@117064f1 that was originally bound here
E/ActivityThread( 4474): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@117064f1 that was originally bound here
E/ActivityThread( 4474): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4474): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4474): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4474): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4474): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4474): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4474): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4474): 	,at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4474): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4474): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4474): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4474): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4474): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4474): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  908): Unbind failed: could not find connection for android.os.BinderProxy@38556ff7
,I/CustomizationCIDLoader( 4492): Parsing tag category name = system
,I/CustomizationCIDLoader( 4492): Parsing tag category name = application
E/SQLiteLog( 4474): (283) recovered 12 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/CustomizationCIDLoader( 4492): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4492): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4492): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4492): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4492): Parsing tag category name = ACC
,D/CustomizationManager( 4492):  Read CID file spent 0.126 (s)
D/CustomizationManager( 4492):  All configurations done spent 0.126 (s)
,I/htcbackup-core( 4541): ModelRegistry: Loading model meta data from resources...
,E/ActTriggerJNI( 4492): open library fail.
,I/htcbackup-core( 4541): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
,I/htcbackup-core( 4541): SuperSaverModeReceiver: going to send resume event
,D/GCM     ( 1764): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1764): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4195): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/htcbackup-core( 4541): BackupRestoreManager: onHandleIntent
,I/htcbackup-core( 4541): BackupRestoreManager: resume
,D/PackageManager(  908): deletePackageAsUser: pkg=com.example.hello, pid=4492, uid=2000 userid=0,
,I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced,
I/ActivityManager(  908): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4579 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Process (  908): killProcessQuiet, pid=3763
I/ActivityManager(  908): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 3763:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/DeviceManagement( 3874): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 ,
,I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced
,I/ActivityManager(  908): Recipient 3763,
D/WifiService(  908): Client connection lost with reason: 4
,I/WindowState(  908): WIN DEATH: Window{2f1f4c59 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  908): Skipping PackageSetting{1d433aa1 com.test.thalitest/10373} due to missing metadata,
,I/DeviceManagement( 3874): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup],
,I/DeviceManagement( 3874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,W/ActivityManager(  908): Force removing ActivityRecord{2d222ab2 u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,E/MP-Decision( 2317): Update arg "0 380 380 380".
E/MP-Decision( 2317): Update arg "0 400 400 400".
,W/ActivityManager(  908): Spurious death for ProcessRecord{1d76d5fc 3763:com.example.hello/u0a380}, curProc for 3763: null
,I/ActivityManager(  908): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/DeviceManagement( 3874): WorkflowService: Starting workflow service
,I/DeviceManagement( 3874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3874): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,I/DeviceManagement( 3874): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,W/ResourcesManager( 4579): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4579): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4195, uid=10025, userID:0
D/DotMatrix( 1198): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1198): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  908): acquireWL(7cb72da): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1697 10025 WorkSource{10025 com.google.android.gms},
,D/DotMatrix( 1198): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  908): releaseWL(7cb72da): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
I/FeedHostManager( 1473): [onResume]
W/ResourcesManager( 1413): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/FeedProviderManager( 1473): onResume
I/SocialFeedProvider( 1473): +onResume
I/SocialFeedProvider( 1473): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1473): -onResume
I/ConnectivityHelper( 1473): [getCurrentConnectionType] no network connection
,I/MultiDex( 4579): VM with version 2.1.0 has multidex support
,I/MultiDex( 4579): install,
,I/MultiDex( 4579): VM has multidex support, MultiDex support library is disabled.
,I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/StatusBarManagerService(  908): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  908): hiding MENU key
,D/AccTypeManager( 1576): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/Prism.ItemManager( 1473): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1473): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4474, uid=10115, userID:0
,D/PhoneApp( 1413): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 3763 uid 10380
I/Gmail   ( 4474): getAccountsCursor
D/StatusBarManagerService(  908): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  908): Enable input method client, pid=1473
D/AccTypeManager( 1576): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 102
,D/AccFlag ( 1413): sku_id=99,
,V/JNIHelp ( 4579): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBarManagerService(  908): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  908): hiding MENU key
,D/LocationInitializer( 4195): Restart initialization of location,
W/PackageManager(  908): Unable to load service info ResolveInfo{643ba8c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  908): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1413): sku_id=99
,W/System  ( 4579): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1150e386: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
,W/ActivityThread( 4579): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ProviderInstaller( 4579): Installed default security provider GmsCore_OpenSSL
,E/ExternalAccountType( 1576): Unsupported attribute readOnly,
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4612 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,D/WearableService( 4579): callingUid 10025, callindPid: 4579,
,D/JobSchedulerService(  908): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager(  908): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TaskPersister(  908): removeObsoleteFile: deleting file=27_task.xml
,E/MDM     ( 1697): [162] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  908): Explicit concurrent mark sweep GC freed 26757(1691KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 16MB/25MB, paused 1.206ms total 266.980ms,
I/art     (  908): WaitForGcToComplete blocked for 168.067ms for cause Explicit
,I/ImageRamCache( 4612): create image Cache, size: 31457280.
,I/ImageRamCache( 4612): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4612): create image Cache, size: 31457280.
,I/FeedSettings( 4612): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false,
I/FeedSettings( 4612): GroupBudget 0.500000 0.380000
I/FeedSettings( 4612): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4612): changeLocale(): en_GB
,W/asset   (  908): Copying FileAsset 0xb890a460 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Prism.AllAppsOptionsMa_( 4612): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4612): loadGridSize() with Alternative
,I/art     (  908): Explicit concurrent mark sweep GC freed 2483(120KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 916us total 68.496ms
,D/CustomHighlightReceiver( 4612): [custom highlight] onReceive
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,I/DeviceManagement( 3874): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/GCoreUlr( 1697): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}],
I/Gmail   ( 4474): master sync=false, engine sync=true,
,I/GCoreUlr( 1697): DispatchingService.onCreate(),
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65,
D/PMS     (  908): acquireWL(3afd4729): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4195 10025 null
D/AccFlag ( 1413): sku_id=99,
,D/PMS     (  908): acquireWL(3c3bfaae): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4195 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  908): releaseWL(3afd4729): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  908): releaseWL(3c3bfaae): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
D/CustomHighlightService( 4612): [custom highlight] onHandleIntent
,D/NewsDB  ( 4612): set custom highlight []
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4636 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
,D/TelephUtils( 1413): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 104
D/AccFlag ( 1413): sku_id=99
,D/PMS     (  908): acquireWL(3c7ef04f): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1697 10025 WorkSource{10025 com.google.android.gms},
,D/CustomHighlightService( 4612): [custom highlight] set tags ,
,I/ActivityManager(  908): Killing 3962:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3962
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.backup
,I/DeviceManagement( 3874): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00]
E/Gmail.LabelManager( 4474): Unable to get label ^i for account thalitester@gmail.com
,E/Gmail   ( 4474): Couldn't find label: ^i
,I/ActivityManager(  908): Recipient 3962
,I/htcbackup-core( 4541): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_3962/cgroup.procs: No such file or directory
D/Process (  908): killProcessQuiet, pid=3962
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/DeviceManagement( 3874): WorkflowService: Stopping workflow service
,I/ActivityManager(  908): Killing 3980:com.htc.htccupd/u0a13 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=3980
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 3980
,D/MessagingShortcutReceiver( 3585): keep hiding shortcut bubble
,D/Process (  908): killProcessQuiet, pid=3980
W/libprocessgroup(  908): failed to open /acct/uid_10013/pid_3980/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/MessagingShortcut( 3585): updateMsgShortcut, msg count> -1,
,D/MessagingShortcut( 3585): After query: 0
D/MessagingShortcut( 3585): mPresentUnreadCount: -1
D/MessageUtils( 3585): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3585): setMsgShortcutDrawable> 0, false
,I/DeviceManagement( 3874): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 3874): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup],
I/GCoreUlr( 1697): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED
I/DeviceManagement( 3874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4657 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
,D/MessagingShortcut( 3585): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1198): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/DeviceManagement( 3874): WorkflowService: Starting workflow service
D/DotMatrix( 1198): [EventService] reorderNotification, total:0
D/DotMatrix( 1198): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1198): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
I/DeviceManagement( 3874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3874): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3874): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,W/OpenGLRenderer( 1473): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...
I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4676 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 4474): getAccountsCursor,
,V/GLSActivity( 1764): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Gmail   ( 4474): master sync=false, engine sync=true,
,W/ResourcesManager( 4676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Gmail.LabelManager( 4474): Unable to get label ^i for account thalitester@gmail.com,
E/Gmail   ( 4474): Couldn't find label: ^i
,D/TodoTaskshortcut( 4676): update TASK shortcut>,
,D/MdScBoot( 4636): [720.1.] 30@-172615 -> 40,
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm,
,D/MdScBootUi( 4636): [720.1.2.] boot 99,
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4699 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,I/DeviceManagement( 3874): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
I/DeviceManagement( 3874): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3874): SessionStateController: Checking invariants...,
D/MdUtils ( 4636): [720.1.2.] subId list: (0)r0 (s0)-1,
,I/GCoreUlr( 1697): WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/DeviceManagement( 3874): ConfigManagerController: There is no cached content available: appID=com.htc.backup,
I/DeviceManagement( 3874): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00]
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4718 uid=10079 gids={50079, 9997} abi=armeabi-v7a
D/Process (  908): killProcessQuiet, pid=4037
I/ActivityManager(  908): Killing 4037:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  908): Recipient 4037,
I/art     (  473): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 139us total 16.496ms
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 8.455ms,
,I/art     (  473): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 8.528ms,
,I/htcbackup-core( 4541): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
D/Process (  908): killProcessQuiet, pid=4037
W/libprocessgroup(  908): failed to open /acct/uid_10013/pid_4037/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  908): acquireWL(3d3e9c5b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1697 10025 WorkSource{10025 com.google.android.gms}
E/htcbackup-core( 4541): DMConfiguredIntentService: Interupted <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]> 
E/htcbackup-core( 4541): BackupRestoreManager: Can not get DM configured
I/DeviceManagement( 3874): WorkflowService: Stopping workflow service
,D/PMS     (  908): releaseWL(2472e4c7): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
E/SQLiteDatabase( 4657): Failed to open database '/data/user/0/com.htc.mobiledata/databases/mobiledata.db'.
E/SQLiteDatabase( 4657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4657): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4657): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:461)
E/SQLiteDatabase( 4657): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:51)
E/SQLiteDatabase( 4657): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4657): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4657): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 4657): 	at android.os.Binder.execTransact(Binder.java:454)
,E/SQLiteOpenHelper( 4657): Couldn't open mobiledata.db for writing (will try read-only):
E/SQLiteOpenHelper( 4657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 4657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4657): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4657): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:461)
E/SQLiteOpenHelper( 4657): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:51)
E/SQLiteOpenHelper( 4657): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 4657): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 4657): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 4657): 	at android.os.Binder.execTransact(Binder.java:454)
D/PMS     (  908): releaseWL(3d3e9c5b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/htcbackup-core( 4541): DMConfiguredIntentService: Config model load failed: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
W/htcbackup-core( 4541): DMConfiguredIntentService: reason null 
W/SQLiteOpenHelper( 4657): Opened mobiledata.db in read-only mode
D/Process (  908): killProcessQuiet, pid=4072
I/ActivityManager(  908): Killing 4072:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 4072,
,D/Process (  908): killProcessQuiet, pid=4072
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  908): failed to open /acct/uid_10011/pid_4072/cgroup.procs: No such file or directory
,D/SMSBackup( 4718): Got a database change event
,I/ActivityManager(  908): Killing 4020:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4020
,D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  908): Recipient 4020
,D/Process (  908): killProcessQuiet, pid=4020
,W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_4020/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/GCoreUlr( 1697): Unbound from all location providers
,I/DeviceManagement( 3874): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
I/DeviceManagement( 3874): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
D/PMS     (  908): releaseWL(3c7ef04f): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
E/SharedPreferencesImpl( 1697): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
D/PMS     (  908): acquireWL(3b40a337): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4676 10072 null
I/DeviceManagement( 3874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,D/Process (  908): killProcessQuiet, pid=4098,
I/ActivityManager(  908): Killing 4098:com.android.smith/1000 (adj 15): empty #17
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PMS     (  908): acquireWL(1fca70a4): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4676 10072 null
,I/ActivityManager(  908): Recipient 4098
,D/Process (  908): killProcessQuiet, pid=4098,
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_4098/cgroup.procs: No such file or directory
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/DeviceManagement( 3874): WorkflowService: Starting workflow service,
I/DeviceManagement( 3874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3874): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
D/PMS     (  908): releaseWL(3b40a337): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/DeviceManagement( 3874): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,E/TodoTaskNotifyService( 4676): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4676): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4676): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4676): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4676): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4676): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  908): releaseWL(1fca70a4): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4676): stopSelfResult true
,I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,E/SQLiteLog( 1764): (3850) statement aborts at 10: [DELETE FROM pending_ops WHERE _id = 609] disk I/O error
,E/SQLiteDBG( 1764): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/ns.db, handle: 0xb87aaf00
,D/MtpReceiver( 3534): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3534): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3534): [MTP][handleUsbState]+
,E/AndroidRuntime( 1764): FATAL EXCEPTION: main
E/AndroidRuntime( 1764): Process: com.google.process.gapps, PID: 1764
E/AndroidRuntime( 1764): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1764): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1764): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1764): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1764): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1764): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/AndroidRuntime( 1764): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1764): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/AndroidRuntime( 1764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 1764): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1764): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1764): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1764): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1764): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1764): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1764): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:254)
E/AndroidRuntime( 1764): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
E/AndroidRuntime( 1764): 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
E/AndroidRuntime( 1764): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
E/AndroidRuntime( 1764): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1764): 	... 9 more
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4743 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a
,E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
D/MtpReceiver( 3534): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3534): [MTP][handleUsbState]-
D/MtpReceiver( 3534): [MTP][handleMessage]-
,D/MtpService( 3534): updating state; isCurrentUser=true, mMtpLocked=false,
,E/DropBoxManagerService(  908): Can't write: system_app_crash
,E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  908): 	... 5 more
,E/SQLiteLog( 3874): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3874): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0xb8706ef8
,D/StatusBarManagerService(  908): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  908): hiding MENU key
D/MtpDatabase( 3534): TotalSize=1867208,MediaCacheLimit=6000
,I/DeviceManagement( 3874): ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,D/MtpService( 3534): [isMtpConnected] connected: true
I/DeviceManagement( 3874): DMConfigController: Ignoring exception fetching DM Core config: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
I/DeviceManagement( 3874): SessionStateController: Checking invariants...
,I/GCoreUlr( 1697): DispatchingService.onDestroy()
,D/PMS     (  908): acquireWL(3f115aca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1697 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  908): releaseWL(3f115aca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1697): Unbound from all location providers
,E/SQLiteLog( 3874): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3874): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0xb8706ef8
,E/DeviceManagement( 3874): ServiceWorkflow: Uncaught throwable,
E/DeviceManagement( 3874): java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/DeviceManagement( 3874): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
E/DeviceManagement( 3874): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
E/DeviceManagement( 3874): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/DeviceManagement( 3874): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/DeviceManagement( 3874): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/DeviceManagement( 3874): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/DeviceManagement( 3874): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/DeviceManagement( 3874): 	,at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/DeviceManagement( 3874): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/DeviceManagement( 3874): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/DeviceManagement( 3874): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/DeviceManagement( 3874): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
,E/DeviceManagement( 3874): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DeviceManagement( 3874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DeviceManagement( 3874): 	at android.os.Looper.loop(Looper.java:155)
E/DeviceManagement( 3874): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4743): Failed to open database '/data/data/com.nero.android.htc.sync/databases/nccontentprovider.db'.
E/SQLiteDatabase( 4743): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4743): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4743): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/SQLiteDatabase( 4743): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 4743): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5417)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4988)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4923),
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 4743): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4743): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/SQLiteDatabase( 4743): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4743): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4743): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/SQLiteDatabase( 4743): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,E/AndroidRuntime( 4743): FATAL EXCEPTION: main
E/AndroidRuntime( 4743): Process: com.nero.android.htc.sync, PID: 4743
E/AndroidRuntime( 4743): java.lang.RuntimeException: Unable to get provider com.nero.android.neroconnect.contentprovider.NCContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5420)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4988)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4923)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 4743): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4743): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/AndroidRuntime( 4743): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4743): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4743): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/AndroidRuntime( 4743): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 4743): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/AndroidRuntime( 4743): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/AndroidRuntime( 4743): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 4743): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 4743): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5417)
E/AndroidRuntime( 4743): 	... 11 more
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
E/DeviceManagement( 3874): ServiceWorkflow: java.lang.IllegalStateException: message=[Cannot perform this operation because there is no current transaction.]
I/DeviceManagement( 3874): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c3bcf00]
E/ActivityManager(  908): App crashed! Process: com.nero.android.htc.sync
W/System.err(  908): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
I/ActivityManager(  908): Killing 4055:com.android.settings/1000 (adj 15): empty #17
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  908): 	... 12 more
,I/DeviceManagement( 3874): WorkflowService: Stopping workflow service
I/htcbackup-core( 4541): ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: java.lang.IllegalStateException: message=[Cannot perform this operation because there is no current transaction.]
E/htcbackup-core( 4541): DMConfiguredIntentService: Interupted java.lang.IllegalStateException: java.lang.IllegalStateException: message=[Cannot perform this operation because there is no current transaction.] 
E/htcbackup-core( 4541): BackupRestoreManager: Can not get DM configured
D/Process (  908): killProcessQuiet, pid=4055
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/htcbackup-core( 4541): DMConfiguredIntentService: Config model load failed: java.lang.IllegalStateException: java.lang.IllegalStateException: message=[Cannot perform this operation because there is no current transaction.]
W/htcbackup-core( 4541): DMConfiguredIntentService: some other failure java.lang.IllegalStateException: message=[Cannot perform this operation because there is no current transaction.] 
,W/System.err(  908): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  908): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  908): 	... 14 more
,I/ActivityManager(  908): Recipient 4055
,E/MediaScannerService( 3534): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3534): [handleMessage] --- Should not be here, ignore request. ----
,W/System.err(  908): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
,W/System.err(  908): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  908): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  908): 	... 14 more
,D/Process (  908): killProcessQuiet, pid=4055
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_4055/cgroup.procs: No such file or directory
,I/ActivityManager(  908): Killing 4158:com.google.android.gms:car/u0a25 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=4158
D/Process (  908): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  908): Recipient 4158,
,D/Process (  908): killProcessQuiet, pid=4158,
D/Process (  908): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  908): failed to open /acct/uid_10025/pid_4158/cgroup.procs: No such file or directory,
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information,
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448385996647.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  908): 	... 4 more
W/ActivityManager(  908): Can't addPackageDependency on system process
,E/MediaScannerServiceEx( 3534): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3534): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3534): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3534): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3534): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3534): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3534): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3534): [AliveExtStorageRows]+65537, 11223344
,V/AlarmManager(  908): sending alarm PendingIntent{3a750eff: PendingIntentRecord{26a344cc com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=42590, Int=259200000
,V/AlarmManager(  908): sending alarm PendingIntent{54e062a: PendingIntentRecord{36959c1b com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448385996887, Int=0
,E/SQLiteDatabase( 4195): Failed to open database '/data/data/com.google.android.gms/databases/iu.upload.db'.
E/SQLiteDatabase( 4195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.autobackup.ax.getReadableDatabase(SourceFile:55)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.autobackup.af.g(SourceFile:614)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.autobackup.af.<init>(SourceFile:192)
E/SQLiteDatabase( 4195): 	,at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:49)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/SQLiteDatabase( 4195): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/SQLiteDatabase( 4195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4195): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4195): Couldn't open iu.upload.db for writing (will try read-only):
E/SQLiteOpenHelper( 4195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 4195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.autobackup.ax.getReadableDatabase(SourceFile:55)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.autobackup.af.g(SourceFile:614)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.autobackup.af.<init>(SourceFile:192)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:49)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
,E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/SQLiteOpenHelper( 4195): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/SQLiteOpenHelper( 4195): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4195): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 4195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4195): Opened iu.upload.db in read-only mode
,I/iu.UploadsManager( 4195): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/Prism.ItemManager( 1473): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1473): loadItems() com.htc.launcher.pageview.WidgetManager@372519a +
I/Prism.WidgetManager( 1473): onLoadItems() +
,E/AndroidRuntime( 4195): FATAL EXCEPTION: IntentService[MediaMonitorIntentService]
E/AndroidRuntime( 4195): Process: com.google.android.gms, PID: 4195
E/AndroidRuntime( 4195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 4195): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4195): 	,at com.google.android.libraries.social.autobackup.ax.getWritableDatabase(SourceFile:48)
E/AndroidRuntime( 4195): 	at com.google.android.libraries.social.autobackup.af.a(SourceFile:307)
E/AndroidRuntime( 4195): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/AndroidRuntime( 4195): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/AndroidRuntime( 4195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4195): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  908): 	... 5 more
,W/ResourcesManager(  908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1473): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/qdhwcomposer(  367): hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Operation not permitted
E/SurfaceFlinger(  367): eventControl(0, 0) failed Operation not permitted
,E/Prism.WidgetManager( 1473): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1473): onLoadItems() -
I/Prism.ItemManager( 1473): loadItems() com.htc.launcher.pageview.WidgetManager@372519a -
,E/SQLiteLog( 1473): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error
,E/SQLiteDBG( 1473): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb86d64e0
,E/AndroidRuntime( 1473): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1473): Process: com.htc.launcher, PID: 1473
E/AndroidRuntime( 1473): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1473): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1473): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1473): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1473): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1473): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1473): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1473): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1473): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1473): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1473): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1473): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1473): 	at android.os.Looper.loop(Looper.java:155)
,E/AndroidRuntime( 1473): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.htc.launcher
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  908): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  908): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,W/System.err(  908): 	... 12 more
,W/System.err(  908): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
,W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
,W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  908): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
,W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  908): 	... 14 more
,W/System.err(  908): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
,W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  908): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
W/System.err(  908): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
,W/System.err(  908): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  908): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/ActivityManager(  908):   Force finishing activity com.htc.launcher/.Launcher
W/System.err(  908): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err(  908): 	at libcore.io.Posix.open(Native Method)
W/System.err(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  908): 	... 14 more
D/PMS     (  908): acquireWL(31537b85): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1448385997298.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  908): 	... 4 more
I/FeedHostManager( 1473): [onPause]
I/FeedProviderManager( 1473): onPause
I/FeedHostManager( 1473): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3258a26e
I/SocialFeedProvider( 1473): +onPause
I/SocialFeedProvider( 1473): -onPause
,D/HtcSystemUPManager(  908): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,I/ActivityManager(  908): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0,
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,I/OrientationManager( 1473): [release]
I/Prism.IndicatorPagedVi_( 1473): IndicatorPagedView.nCapability with type count = 1 and capability = 20
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
,E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
,E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  367): MdpCtrl close error in unset

```
