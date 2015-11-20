#### Test 50388019aa1a16d_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of main
D/Process (  907): killProcessQuiet, pid=3489
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
--------- beginning of system
W/libprocessgroup(  907): failed to open /acct/uid_10027/pid_3489/cgroup.procs: No such file or directory
D/MediaProvider( 3846): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 3846): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3846): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3846): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3846): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3846): [MP][DEBUG] Storage State: removed
D/MediaScannerReceiver( 3846): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
D/MediaProviderUtils( 3846): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
D/MediaProviderUtils( 3846): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
E/SQLiteLog( 3846): (283) recovered 18 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal
D/PluginProvider( 1547): Begin Apply Batch
E/PluginProvider( 1547): conflict when insert feature, ignored
D/NGFLanguageMgr( 3761): LanguageFromSystem: language:en  country:gb
D/NGFLanguageMgr( 3761): language package name = preload_package
W/NMT     ( 3761): Fail to open read-stream for file generic.lst
D/MediaScannerServiceEx( 3846): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3846): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
D/MtpReceiver( 3846): [MTP][handleUsbStateAsync]+
D/PMS     (  907): acquireWL(2a1d0070): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3846 10017 null
D/MtpReceiver( 3846): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3846): [MTP][handleUsbState]+
I/NMT     ( 3761): NMT version: 1.6.1-B006 REL
D/NGFService( 3761): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
I/ActivityManager(  907): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3902 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/NGFService( 3761): applyCurrentSystemLanguage +++
D/MediaProvider( 3846): bindService() MTP Service Connection.
D/NGFService( 3761): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3761): LanguageFromSystem: language:en  country:gb
D/NGFService( 3761): Elvis language uses the language: 2
D/NGFService( 3761): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3761): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3761): bluetoothInitialize +++
D/MtpReceiver( 3846): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3846): [MTP][handleUsbState]-
D/MtpReceiver( 3846): [MTP][handleMessage]-
D/MtpService( 3846): updating state; isCurrentUser=true, mMtpLocked=false
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@136965a0:true
D/MtpService( 3846): addStorageInternal without MtpServer
D/BluetoothHeadset( 3761): BluetoothHeadset()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 8
D/MtpService( 3846): [MTP][onCreate]-
D/MediaScanner( 3846): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
I/ActionCombine( 3846): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 9
D/NGFService( 3761): cloud_init +++
D/NGFLanguageMgr( 3761): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
D/MtpService( 3846): [MTP] startForeground
D/DotMatrix( 1203): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 3846): updating state; isCurrentUser=true, mMtpLocked=false
D/PMS     (  907): acquireWL(359aacd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2065 10025 null
D/MtpDatabase( 3846): TotalSize=1867208,MediaCacheLimit=6000
D/MtpService( 3846): starting MTP server in MTP mode
E/SQLiteLog( 3846): (283) recovered 181 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
D/MtpService( 3846): addStorageInternal 65537 /storage/emulated/0
D/MtpService( 3846): [checkStorageState] Storage state - mounted
D/NGFService( 3761): elvisInitalize +++
I/RemoteViews( 1124): apply : com.android.providers.media 0 16 1 36
D/MtpDatabase( 3846): [MTP][addStorage] iHostType =2
D/MtpService( 3846): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
W/HtcWrapAdjustableCursorFactory( 3902): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/NGFService( 3761): elvisInitalize lang = British English
D/NGFService( 3761): elvisInitalize: Freq Type:16000
D/NGFService( 3761): tts_init +++
D/NGFLanguageMgr( 3761): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
D/MessageFrequencyProvider( 3902): onCreate
I/RemoteViews( 1124): apply : com.android.providers.media 0 17 1 51
V/GetPrviateResource( 3902): GetPrviateResource
V/GetPrviateResource( 3902): GetPrviateResource
I/iu.UploadsManager( 2065): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
D/MessageCustFlag( 3902): sense_version=6.0
D/BTAccessoryUtil( 3902): createReceiver
D/BTAccessoryUtil( 3902): registerReceiver return intent = null
D/MessageCustFlag( 3902): sku_id=99
D/HtcBuildUtils( 3902): getRATByHtcTelephonyCapability:1
W/SystemReader( 3902): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 3902): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 3902): onReceive()
D/ExchangePolicystatus( 3902): onReceive(): ACTION_BOOT_COMPLETED
D/PMS     (  907): acquireWL(1d3f2ffc): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3902 10067 null
D/MessageUtils( 3902): Text messaging allow status = allow
D/Messaging( 3902): EAS allow SMS !!!
D/ExchangePolicystatus( 3902): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3902): EAS allow SMS !!!
V/SmsReceiverService( 3902): onStart: #1, @1001879297
V/SmsReceiverService( 3902): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3902): isCbm: false
D/SmsReceiverService( 3902): isDiscard: false
D/SettingsManager( 3902): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1eaae785
V/SmsReceiverService( 3902): handleBootCompleted
W/ResourcesManager( 3902): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/MediaScannerService( 3846): [onStartCommand] --- Should not be here, redirect request. ----
I/ActivityManager(  907): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3938 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/MediaScannerService( 3846): [handleMessage] --- Should not be here, ignore request. ----
I/iu.UploadsManager( 2065): End new media; added: 0, uploading: 0, time: 81 ms
D/PMS     (  907): releaseWL(359aacd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/AccFlag ( 1445): sku_id=99
D/NGFLanguageMgr( 3761): LanguageFromSystem: language:en  country:gb
D/NGFLanguageMgr( 3761): language package name = preload_package
D/PluginProvider( 1547): apply Batch success
W/MediaScanner( 3846): Error opening directory '/oem/media/', skipping: No such file or directory.
I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1487): loadItems() com.htc.launcher.pageview.WidgetManager@14fbeb22 +
I/Prism.WidgetManager( 1487): onLoadItems() +
D/NGFService( 3761): load vocalizer language = British English
E/NGFService( 3761): registerObserver
W/MediaScanner( 3846): Error opening directory '/oem/media/', skipping: No such file or directory.
D/SmsReceiverService( 3902): OutBoxSize = 0
D/NGFService( 3761): onCreate: Battery Level Remaining: 100%
D/NGFService( 3761): onStartCommand(): service start
D/SmsReceiverService( 3902): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3902): sku_id=99
D/NGFService( 3761): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3761): QuickCall
D/BluetoothHeadset( 3761): Proxy object connected
D/NGFService( 3761): BluetoothHeadset onServiceConnected: main
D/BluetoothAdapter( 3761): 588056832: getState(). Returning 12
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/AccFlag ( 1445): sku_id=99
W/NGFService( 3761): Headset deviceList = 0
D/BluetoothA2dp( 3761): Proxy object connected
D/NGFService( 3761): BluetoothA2dp onServiceConnected: main
D/BluetoothAdapter( 3761): 588056832: getState(). Returning 12
W/NGFService( 3761): A2dp deviceList = 0
W/ResourcesManager( 1487): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/MessageCustFlag( 3902): sku_id=99
D/MediaScanner( 3846):  prescan time: 172ms
D/MediaScanner( 3846):     scan time: 70ms
D/MediaScanner( 3846): postscan time: 0ms
D/MediaScanner( 3846):    total time: 242ms
D/MediaScanner( 3846): -----------------------------------------------------------------
D/MediaScanner( 3846): firstscan(media) time: 31ms
D/MediaScanner( 3846): secondscan(non-media) time: 35ms
D/MediaScanner( 3846):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Total]    File(Image+Video+Audio+Others) in database : 359
I/HtcModeClient( 3312): handler message = 4011
E/HtcModeClient( 3312): Check connection and retry 1 times.
D/SmsReceiverService( 3902): sendFirstQueuedMessage end cnt> 0
W/NMT-OemFile( 3761): fopen(): Failed to open file sysdct.dat
D/SpaceBufferUtil( 3902): > createBufferFile()
D/SpaceBufferUtil( 3902): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
W/NMT-OemFile( 3761): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
D/SpaceBufferUtil( 3902): < createBufferFile()
W/NMT-OemFile( 3761): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
W/NMT-OemFile( 3761): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3761): fopen(): Failed to open file sysdct.dat
D/NGFService( 3761): Elvis is initialization Success
D/NGFService( 3761): bElvisInitializeCompleted = true
D/NGFService( 3761): GrammarState = 0
D/NGFService( 3761): loadGrammar +++
D/NGFService( 3761): loadGrammar asr_grammar
I/NGFService( 3761): GrammarDepot contains a valid Elvis Grammar0
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishname.lst
D/NGFService( 3761): loadGrammar from cache
W/NMT-OemFile( 3761): fopen(): Failed to open file clm.dat
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishartist.lst
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishplaylist.lst
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3761): Fail to open read-stream for file elvisBritish Englishgeneric.lst
W/NMT-OemFile( 3761): fopen(): Failed to open file daniel_userdct_eng.dat
E/cutils-trace( 3958): Error opening trace file: No such file or directory (2)
I/dex2oat ( 3958): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/[PluginManager]RegisterService( 1547): Notify Carousel that a new TabPlugin has been installed!
D/MediaProvider( 3846): [delete][96]
D/MediaProvider( 3846): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/SettingUtils( 3761): setProcessNormalFlag: true
D/NGFService( 3761): RebuildListener constraintList size 17
D/NGFService( 3761): RebuildListener: onComplete0
D/NGFService( 3761): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3761): switchScenario: htc_screen_140_19
D/NGFService( 3761): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3761): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3761): Loading grammar completed.
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishname.lst
D/NGFService( 3761): update contact cache completed
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishartist.lst
D/SettingUtils( 3761): set Updatge Contact Cache: false
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishsong.lst
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishalbum.lst
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishplaylist.lst
W/NMT     ( 3761): Fail to open read-stream for file serverBritish Englishgeneric.lst
I/art     (  907): Explicit concurrent mark sweep GC freed 15531(815KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.875ms total 73.905ms
W/ResourcesManager( 1487): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/MediaProvider( 3846): [recoverParentNodes] - 0
D/MediaProvider( 3846): [update][66]
D/MediaScannerServiceEx( 3846): [scan] Recover Parent Node is finished!
D/PMS     (  907): releaseWL(2a1d0070): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
E/MediaScannerServiceEx( 3846): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3846): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3846): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3846): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3846): [update][6]#0#
D/MediaProvider( 3846): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3846): [update][4]#0#
D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3846): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3846): [update][17]#1#
D/MediaScannerServiceEx( 3846): [AliveExtStorageRows]-0, -1, 0, -1
D/PMS     (  907): acquireWL(2b1c5cda): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3846 10017 null
D/MediaScanner( 3846): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
E/Prism.WidgetManager( 1487): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1487): onLoadItems() -
I/Prism.ItemManager( 1487): loadItems() com.htc.launcher.pageview.WidgetManager@14fbeb22 -
E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=87
E/WifiTrafficPoller(  907): notifying of data activity 1
D/WIFI_ICON( 1124): WifiActivity: 1
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/AlarmManager(  907): sending alarm PendingIntent{29fa250b: PendingIntentRecord{84d4fe8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=39575, Int=0
D/PhoneApp( 1445): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1445): -- N1 =0
D/PhoneApp( 1445): -- N2 =0
D/PhoneApp( 1445): -- N3 =0
E/cutils-trace( 3964): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3964): ====startRecUseTime====
D/htc.customization.log.level( 3964):  is 
W/CustomizationLogLevel( 3964): Level value is invalid, use default level 2
D/CustomizationManager( 3964):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__203
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__405
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__304
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 3964): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 3964): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3964): Parsing tag category name = system
I/CustomizationCIDLoader( 3964): Parsing tag category name = application
I/CustomizationCIDLoader( 3964): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3964): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3964): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3964): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3964): Parsing tag category name = ACC
D/CustomizationManager( 3964):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3964):  All configurations done spent 0.088 (s)
E/ActTriggerJNI( 3964): open library fail.
E/MP-Decision( 2321): Update arg 2
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
E/MP-Decision( 2321): Update arg 4
D/PMS     (  907): acquireHCC(cb3e601): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 907 1000 null
W/asset   (  907): Copying FileAsset 0xb9532bd8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  907): acquireHCC(1e736ca6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 907 1000 null
E/MP-Decision( 2321): Update arg "0 190 240 240".
D/PMS     (  907): acquireWL(3f77e13d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
E/MP-Decision( 2321): Update arg "0 75 400 400".
I/AnimationUtil(  907): isHTCRecent(HelloWorld/Recent screens.)/6
I/FeedHostManager( 1487): [onPause]
I/FeedProviderManager( 1487): onPause
I/FeedHostManager( 1487): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@8e8a69b
I/SocialFeedProvider( 1487): +onPause
I/SocialFeedProvider( 1487): -onPause
D/HtcSystemUPManager(  907): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3978 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService(  907): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
D/PMS     (  907): releaseWL(186b22d2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
W/asset   ( 3978): Copying FileAsset 0xb91dd748 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1487): [trimMemory] 20
I/WebViewFactory( 3978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3978): Time to load native libraries: 24 ms (timestamps 185-209)
I/LibraryLoader( 3978): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3978): Binding Chromium to main looper Looper (main, tid 1) {2d8914fc}
I/LibraryLoader( 3978): Expected native library version number "",actual native library version number ""
I/chromium( 3978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3978): Initializing chromium process, singleProcess=true
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3978): ApplicationContext is null in ApplicationStatus
W/chromium( 3978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3978): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 3978): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3978): Build Date: 12/11/14 Thu
I/Adreno-EGL( 3978): Local Branch: 
I/Adreno-EGL( 3978): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 3978): Local Patches: NONE
I/Adreno-EGL( 3978): Reconstruct Branch: NOTHING
I/dex2oat ( 3958): dex2oat took 980.902ms (threads: 4)
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8809d30:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 3978): 600868072: getState(). Returning 12
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): VersionName:             1.2.848061
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): VersionCode:             148001212
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3938): ApplicationMonitor {1f2629a6}: logBasicAppInfo(): BuildConfig.DEBUG:       false
I/PushClient( 3938): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4019 uid=10079 gids={50079, 9997} abi=armeabi-v7a
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  907): Killing 3506:com.htc.android.mail:sync/u0a65 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3506
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  907): Recipient 3506
W/AwContents( 3978): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3978): CordovaWebView is running on device made by: HTC
W/Atfwd_Sendcmd(  482): AtCmdFwd service not published, waiting... retryCnt : 3
D/Process (  907): killProcessQuiet, pid=3506
W/libprocessgroup(  907): failed to open /acct/uid_10065/pid_3506/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3978): Attempt to remove local handle scope entry from IRT, ignoring
D/SMSBackup( 4019): Got ACTION_BOOT_COMPLETED event
D/SMSBackup( 4019): setCheckAlarm
D/SMSBackup( 4019): Next check is scheduled at 60s from now
D/Process (  907): killProcessQuiet, pid=3550
I/ActivityManager(  907): Killing 3550:com.htc.video/u0a30 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
E/WifiDataStallTracker(  907): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=46} preTxRxSum={txSum=43 rxSum=46}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
D/WifiDataStallTracker(  907): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/ActivityManager(  907): Recipient 3550
E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=89
D/MediaScanner( 3846):  prescan time: 505ms
D/MediaScanner( 3846):     scan time: 577ms
D/MediaScanner( 3846): postscan time: 1ms
D/MediaScanner( 3846):    total time: 1083ms
D/MediaScanner( 3846): -----------------------------------------------------------------
D/MediaScanner( 3846): firstscan(media) time: 477ms
D/MediaScanner( 3846): secondscan(non-media) time: 100ms
D/MediaScanner( 3846):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Total]    File(Image+Video+Audio+Others) in database : 1533
D/Process (  907): killProcessQuiet, pid=3550
W/libprocessgroup(  907): failed to open /acct/uid_10030/pid_3550/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1445, uid=1001, userID:0
D/HtcBroadcastReceiver( 1445): onReceive: android.intent.action.BOOT_COMPLETED
D/Atlas   ( 3978): Validating map...
D/MediaProvider( 3846): [delete][19]
D/MediaProvider( 3846): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3846): [recoverParentNodes] - 0
D/MediaProvider( 3846): [update][4]
D/MediaScannerServiceEx( 3846): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3846): [updateImage]+
D/MediaScannerServiceEx( 3846): [updateImage]-0
I/ActivityManager(  907): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=4044 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/PMS     (  907): releaseWL(2b1c5cda): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3846): [2] scan finished
W/chromium( 3978): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3846): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]+131073
D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3846): [update][11]#1#
D/MediaProvider( 3846): [update][3]#0#
I/[AppShowMeDebug]BootCompletedReceiver( 4044): received boot complete
I/[AppShowMeDebug]BootCompletedReceiver( 4044): push flag is false, skip check
I/InputMethodManager( 3978): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@48b2271, mServedView=org.apache.cordova.engine.SystemWebView{28224856 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@112730d7
I/ActivityManager(  907): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=4066 uid=10087 gids={50087, 9997, 1007, 3003, 1028} abi=armeabi-v7a
D/Process (  907): killProcessQuiet, pid=3573
I/ActivityManager(  907): Killing 3573:com.htc.csrecommend/u0a32 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/art     (  474): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 144us total 11.013ms
I/InputMethodManagerService(  907): Disable input method client, pid=1487
D/StatusBarManagerService(  907): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  907): Enable input method client, pid=3978
W/XT9_C   ( 1297): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1297): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1297): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1297): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 135us total 9.592ms
I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 139us total 9.062ms
I/ActivityManager(  907): Recipient 3573
W/BindingManager( 3978): Cannot call determinedVisibility() - never saw a connection for the pid: 3978
D/MediaProvider( 3846): [update][82]#0#
D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]--1, 0, 0
I/chromium( 3978): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3978): Set native->JS mode to OnlineEventsBridgeMode
D/PMS     (  907): releaseWL(3f77e13d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/Process (  907): killProcessQuiet, pid=3573
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10032/pid_3573/cgroup.procs: No such file or directory
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +774ms
D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3846): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]+196609
E/AndroidProtocolHandler( 3978): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3846): [update][6]#1#
,D/MyReportAgent( 4066): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/MediaProvider( 3846): [update][5]#0#
,D/MyReportAgent( 4066): DatabaseHelper [DatabaseHelper constructor]
,D/MyReportAgent( 4066): PolicyStore [Init] Get cached policy bundle
,D/MyReportAgent( 4066): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
,D/MyReportAgent( 4066): ReportServiceHandler on boot complete event ,
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4088 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=4066, uid=10087, userID:0
,V/MyReportAgent( 4066): ReportServiceHandler unregister the PowerConnected Listener
,D/Process (  907): killProcessQuiet, pid=3593,
I/ActivityManager(  907): Killing 3593:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,D/MediaProvider( 3846): [update][55]#0#,
,D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]--1, 0, 0
,I/ActivityManager(  907): Recipient 3593
,D/Process (  907): killProcessQuiet, pid=3593
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_3593/cgroup.procs: No such file or directory
,E/MediaScannerServiceEx( 3846): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3846): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3846): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3846): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3846): [update][3]#0#
,D/MediaProvider( 3846): [IsTableExist] Table:files_65537, result:false
,D/MediaProvider( 3846): [update][1]#0#
,D/jxcore_app_log( 3978): JniHelper::setJavaVM(0xb8132b98), pthread_self() = -1187388408
D/JX-Cordova( 3978): jxcore cordova android initializing
,D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3846): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3846): [update][11]#1#,
,D/MediaScannerServiceEx( 3846): [AliveExtStorageRows]-0, -1, 0, -1,
D/PMS     (  907): acquireWL(1bf46e53): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3846 10017 null
,D/MediaScanner( 3846): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,D/UpdaterAPK | UpdaterBootCompleteReceiver( 4088): onReceive() - start htcCheckinService
,I/htcCheckinService(  907): htcCheckinProvider V2.1
D/htcCheckinService(  907): htcCheckinService() the mIsServiceRunning = true
,I/htcCheckinService(  907): Checkin service onCreate()!
,W/jxcore-log( 3978): Initializing JXcore engine
,W/jxcore-log( 3978): JXcore engine is ready
W/jxcore-log( 3978): Starting JXcore engine
I/ActivityManager(  907): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.BootReceiver: pid=4111 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/htcCheckinService(  907): onStartCommand()
D/htcCheckinService(  907): onStartCommand() the action name = null
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/htcCheckinService(  907): InitThread start,
,D/Process (  907): killProcessQuiet, pid=2145,
I/ActivityManager(  907): Killing 2145:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  907): Recipient 2145
,D/Process (  907): killProcessQuiet, pid=2145
W/libprocessgroup(  907): failed to open /acct/uid_10025/pid_2145/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/ResourceType( 4111): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
,W/ResourcesManager( 4111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/jxcore-log( 3978): Platform android
W/jxcore-log( 3978): 
W/jxcore-log( 3978): Process ARCH arm
W/jxcore-log( 3978): 
,D/Messaging( 3902): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 3902): networkCode: 
D/MmsConfig( 3902): SIE smsPri: null
D/MmsConfig( 3902): networkCode: 
,D/MmsConfig( 3902): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3902): startAsyncQueryReports ---,
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4135 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
,D/Messaging( 3902): mNeedToUpdateDate2 start
,D/MmsAsyncWorkHandler( 3902): 
D/MmsAsyncWorkHandler( 3902): HM tk = 20001
D/ReportIndicatorCache( 3902): MSG_QUERY_REPORTS >>
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1445): sku_id=99
D/DraftCache( 3902): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 3902): [DraftCache/1] refresh
D/MmsConfig( 3902): networkCode: 
D/DraftCache( 3902): [DraftCache/476] rebuildCache
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/Jerry   ( 1445): URI_DRAFT
D/Messaging( 3902): mNeedToUpdateDate2: false
I/jxcore-log( 3978): JXcore Cordova bridge is ready!
I/jxcore-log( 3978): 
W/jxcore-log( 3978): JXcore engine is started
,D/DraftCache( 3902): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3902): [DraftCache/476] rebuildCache time: 6
D/MmsAsyncWorkHandler( 3902): 
D/MmsAsyncWorkHandler( 3902): HM tk = 20002,
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1445): sku_id=99,
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/AccFlag ( 1445): sku_id=99,
,W/System.err( 4111): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 4111): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 4111): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,D/Messaging( 3902): ViewCache CreatePreloadOnlyConversationList,
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
,D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,I/Messaging( 3902): mccmnc> 
D/MessageCustFlag( 3902): sense_version=6.0
D/Jerry   ( 3902): start to preload cursor >>>>>>>
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
D/MmsSmsV2Provider( 1445):  slotId = -1000
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3902): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/PhoneStorageUtil( 3902): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3902): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/Messaging( 3902): ViewCache CreatePreload
,D/Messaging( 3902): ViewCache CreatePreloadOnlyMultipleOpsList
D/PhoneStorageUtil( 3902): createReceiver
,E/jxcore-log( 3978): >> HTC-HTC One_M8
E/jxcore-log( 3978): 
,I/jxcore-log( 3978): Total memory 1912020992
I/jxcore-log( 3978): 
D/TelephUtils( 1445): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 96,
,V/MmsProvider( 1445): Update uri=content://mms, match=0
V/MmsProvider( 1445): selection=st=129 AND m_type!=134
I/jxcore-log( 3978): Free memory 154365952
I/jxcore-log( 3978): 
I/jxcore-log( 3978): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3978): 
I/jxcore-log( 3978): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3978): 
D/Messaging( 3902): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3902): TransactionService is going to be woken up.
,V/TransactionService( 3902): 1-Creating TransactionService
,I/jxcore-log( 3978): userPath [ 'www' ]
I/jxcore-log( 3978): 
D/Cust_MMSMS( 3902): _has_set_default_values_2=true
D/MsgPreferenceUtils( 3902): def_index: 0
D/MsgPreferenceUtils( 3902): globalIndex = 1
D/MsgPreferenceUtils( 3902): phone state: true
D/MsgPreferenceUtils( 3902): sd state: false
D/MsgPreferenceUtils( 3902): vIndex = 0
V/TransactionService( 3902): onStartCommand: 1
D/MmsSystemEventReceiver( 3902): unRegisterForConnectionStateChanges
V/TransactionService( 3902): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/jxcore-log( 3978): Size 1080 1776
I/jxcore-log( 3978): 
V/TransactionService( 3902): Loading previous transactions.
I/jxcore-log( 3978): Screen Brightness 142
I/jxcore-log( 3978): 
E/jxcore-log( 3978): Dummy Error Log.
E/jxcore-log( 3978): 
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1445): device_type: 1
,D/TransactionService( 3902): Force set service start id to 1,
V/TransactionService( 3902): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3902): unRegisterForConnectionStateChanges
V/TransactionService( 3902): Destroying TransactionService
D/TransactionService( 3902): stopSelfResult: true, mLastHandledServiceId: 1
,I/WorldClock.Global( 4135): isHEPDevice = true,
,D/PMS     (  907): acquireWL(26074a5a): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4135 10096 null
,I/HtcModeClient( 3312): handler message = 4009,
I/HtcModeClient( 3312): start to setup the connection
,I/ActivityManager(  907): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
,I/WorldClock.Global( 4135): isHEPDevice = true,
,V/TransactionService( 3902): 4-Handling incoming message: { when=-40ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/WorldClock.AlarmService( 4135): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference,
,I/WorldClock.AlarmUtils( 4135): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  907): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=4180 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  907): Resuming delayed broadcast
,I/WorldClock.AlarmUtils( 4135): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4135): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl(  907): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
I/IntentController( 1124): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/ActivityManager(  907): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4198 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a,
,D/AntHalService(  907): onCreate() entered
,D/PMS     (  907): releaseWL(26074a5a): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,D/Process (  907): killProcessQuiet, pid=3525
,I/ActivityManager(  907): Killing 3525:com.google.android.partnersetup/u0a28 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/JAntJava(  907): Calling nativeJAnt_Create
,W/ResourceType( 4180): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
,D/JAntJava(  907): create: nativeJAnt_Create returned success
D/AntHalService(  907): JAntJava create success
,W/ResourcesManager( 4180): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  907): Recipient 3525
,I/Tiber/HtcIrService( 4180): Created by Thread:1
,I/Tiber/PeelUtils( 4180): Create new PeelUtils
,I/HtcStatusBarManagerWrapper( 4180): glow:20,
,I/Tiber/PeelUtils( 4180): loadDB: load data from database,
,D/AntHalService(  907): onStartCommand() entered
,D/Process (  907): killProcessQuiet, pid=3525
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10028/pid_3525/cgroup.procs: No such file or directory
,I/IntentController( 1124): receive(com.htc.intent.action.STATUS_BAR_GLOW,1,false),
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4111): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
,I/Tiber/PeelUtils( 4180): loadDB(), room count : 0
,I/Tiber/PeelUtils( 4180): loadDB: load updated data from database finished,
I/Tiber/HtcIrService( 4180): Created by Thread:1 finished
,W/ContextImpl( 4111): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,I/PhoneStatusBar( 1124): glow(20,0,0),
,I/art     (  907): Explicit concurrent mark sweep GC freed 17461(846KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 893us total 63.909ms,
,E/UpdateRequestReceiver( 4198): ignoring update request,
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5,
,E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=91
E/UpdateRequestReceiver( 4198): ignoring update request
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{13c99a44 u0 ReceiverList{ec1ef57 4111 com.htc.videocenter/10091/u0 remote:2d8ef0d6}}
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f614462:true
E/UpdateRequestReceiver( 4198): ignoring update request
D/BluetoothAdapter( 4111): 1042968043: getState(). Returning 12
,E/UpdateRequestReceiver( 4198): ignoring update request,
,E/UpdateRequestReceiver( 4198): ignoring update request,
,E/UpdateRequestReceiver( 4198): ignoring update request,
,D/CIRControlWrapper( 4111): hasIrEmitter = true
,D/PMS     (  907): acquireWL(50c29f3): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 4111 10091 null,
,D/PMS     (  907): releaseWL(50c29f3): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 null,
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4234 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 3618:com.htc.contacts/u0a40 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3618
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  907): Recipient 3618
,E/WifiStateMachine(  907): handleMessage: E msg.what=131155,
E/WifiStateMachine(  907): processMsg: ConnectedState
E/WifiStateMachine(  907):  ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=5.3, 0.0, 0.0  rx=11.1 bcn=0 [on:0 tx:0 rx:0 period:2971] from screen [on:0 period:616237482] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  907): processMsg: L2ConnectedState
,E/WifiStateMachine(  907):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=5.3, 0.0, 0.0  rx=11.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616237483] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  907):  get link layer stats 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,D/MediaScanner( 3846):  prescan time: 124ms
D/MediaScanner( 3846):     scan time: 569ms
D/MediaScanner( 3846): postscan time: 3ms
D/MediaScanner( 3846):    total time: 696ms
,D/MediaScanner( 3846): -----------------------------------------------------------------
D/MediaScanner( 3846): firstscan(media) time: 455ms
D/MediaScanner( 3846): secondscan(non-media) time: 114ms
D/MediaScanner( 3846):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3846):  [Total]    File(Image+Video+Audio+Others) in database : 1533
,D/Process (  907): killProcessQuiet, pid=3618,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10040/pid_3618/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  907): fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  907): fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
E/WifiConfigStore(  907): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-53 "NG7005g"WPA_PSK
,E/WifiStateMachine(  907): calculateWifiScore freq=5220 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.65 txretriesrate=0.00 rxrate=8.03 userTriggerdPenalty0
E/WifiStateMachine(  907):  good link -> stuck count =0
E/WifiStateMachine(  907):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  907):  isHighRSSI       ---> score=61
I/Tiber/HtcIrService( 4180): onDestroy called
,I/Tiber/PeelUtils( 4180): Stop CIR service...
D/Tiber/HtcIrService( 4180): If IR had killed, to remove temp data in videocenter_had_killed
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  907): handleMessage: X
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiWatchdogStateMachine(  907): RSSI current: 3 new: -54, 3
I/ActivityManager(  907): Killing 3642:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3642
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,D/MediaProvider( 3846): [delete][17]
,D/MediaProvider( 3846): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,I/ActivityManager(  907): Recipient 3642
,D/MediaProvider( 3846): [recoverParentNodes] - 0
,D/MediaProvider( 3846): [update][4]
D/MediaScannerServiceEx( 3846): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3846): [updateImage]+
,D/MediaScannerServiceEx( 3846): [updateImage]-0
,I/ActivityManager(  907): Killing 3659:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3659
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3659
,D/Process (  907): killProcessQuiet, pid=3642,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10042/pid_3642/cgroup.procs: No such file or directory
,D/Process (  907): killProcessQuiet, pid=3659,
D/PMS     (  907): releaseWL(1bf46e53): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10048/pid_3659/cgroup.procs: No such file or directory
D/MediaScannerServiceEx( 3846): [3] scan finished
D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3846): Process mounted intent for unmounted storage: /storage/ext_sd,
D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]+131073
,I/DeviceManagement( 4234): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=4234 dbg=false s=true,
,D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3846): [update][5]#1#
,I/DeviceManagement( 4234): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,D/MediaProvider( 3846): [update][4]#0#,
I/DeviceManagement( 4234): WorkflowService: Starting workflow service
,I/DeviceManagement( 4234): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@3650e0b] args=[Bundle[EMPTY_PARCEL]],
I/DeviceManagement( 4234): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4234): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4234): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 4234): ModelRegistry: Loading model meta data from resources...,
I/GoogleHttpClient( 1809): GMS http client unavailable, use old client
,I/DeviceManagement( 4234): BackgroundController: *** Update after boot...
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4257 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DeviceManagement( 4234): SessionStateController: Checking invariants...
,I/jxcore-log( 3978): getBuffer is called!!!!
I/jxcore-log( 3978): 
,D/MediaProvider( 3846): [update][62]#0#
,D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]--1, 0, 0
,D/MediaProviderUtils( 3846): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3846): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3846): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3846): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3846): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3846): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
D/MediaProvider( 3846): [update][17]#1#
,D/MediaProvider( 3846): [update][2]#0#,
,I/htcbackup-core( 4257): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4234): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4234): SessionStateController: Checking invariants...,
,I/DeviceManagement( 4234): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
I/DeviceManagement( 4234): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,D/MediaProvider( 3846): [update][87]#0#
,D/MediaScannerServiceEx( 3846): [disAliveExtStorageRows]--1, 0, 0
,I/DeviceManagement( 4234): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/DeviceManagement( 4234): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/PMS     (  907): releaseHCC(cb3e601): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  907): releaseHCC(1e736ca6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
E/MP-Decision( 2321): Update arg 1
,I/DeviceManagement( 4234): Perf: *** Cache update - start...,
I/DeviceManagement( 4234): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4234): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4234): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4234): Perf: Scan enabled apps - start...
,I/DeviceManagement( 4234): EnabledAppBuilder: Examining 268 installed apps for DM enabled apps...,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500050, versionName=6.5.838445,
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031392, versionName=6.3.851500
,W/ResourcesManager( 4234): Asset path '/system/framework/com.android.future.usb.accessory.jar' does not exist or contains no resources.
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444606881, versionName=4.2.848011
,W/ResourcesManager( 4234): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001301, versionName=6.0.847523
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4234): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4234): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001280, versionName=6.5.847469,
,W/ResourceType( 4234): ResTable_typeSpec entry count inconsistent: given 1, previously 1426,
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, versionCode=250081396, versionName=2.7.845092
,W/ResourceType( 4234): ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001212, versionName=1.2.848061,
,V/SmsReceiverService( 3902): updateNotificationAndShortcutStatus: ,
,D/MessagingNotification( 3902): New incoming message, can't cancel notification now,
D/MessagingNotification( 3902): newMsgCnt: 0, false
,I/ActivityManager(  907): Killing 3679:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3679
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3679
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Process (  907): killProcessQuiet, pid=3679
,W/libprocessgroup(  907): failed to open /acct/uid_10050/pid_3679/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  907): releaseWL(1d3f2ffc): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,W/ResourcesManager( 4234): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4234): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4234): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4234): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001186, versionName=2.2.821083,
,I/DeviceManagement( 4234): EnabledAppBuilder: Found 9 DM enabled apps.,
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity,
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.videohub.ui
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns,
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 4234): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 4234): Perf: Scan enabled apps - complete: 475 ms
,I/DeviceManagement( 4234): Perf: *** Enabled app cache update - complete: 476 ms
I/DeviceManagement( 4234): Perf: *** Config cache update - start...
,I/DeviceManagement( 4234): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4234): ConfigCacheController: *** Updating stale config cache entries...
,I/DeviceManagement( 4234): ConfigCacheController: *** Update config cache: updating 0 entries...
,I/DeviceManagement( 4234): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4234): AlarmController: Scheduling TTL alarm for: 2015.11.21 at 12:50:06.501 CET (due to: com.htc.launcher)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4234, uid=10105, userID:0
,I/DeviceManagement( 4234): Perf: *** Config cache update - complete: 11 ms
I/DeviceManagement( 4234): Perf: *** Cache update - complete: 488 ms
I/DeviceManagement( 4234): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@3650e0b]
I/DeviceManagement( 4234): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13a2e0b9] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4234): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,I/DeviceManagement( 4234): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4234): SessionStateController: Checking invariants...
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=91
E/WifiTrafficPoller(  907): notifying of data activity 0
D/WIFI_ICON( 1124): WifiActivity: 0
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/DeviceManagement( 4234): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 4234): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13a2e0b9]
I/DeviceManagement( 4234): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Killing 3696:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3696
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3696,
,D/Process (  907): killProcessQuiet, pid=3696
W/libprocessgroup(  907): failed to open /acct/uid_10051/pid_3696/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  907): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,D/Process (  907): killProcessQuiet, pid=3716,
I/ActivityManager(  907): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4309 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Killing 3716:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3716
,D/Process (  907): killProcessQuiet, pid=3716,
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_3716/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/ResetNotifyBootCompleteReceiver( 1445): Receive bootcomplete intent,
,I/HtcCupdXmlParser( 4309): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory),
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4329 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 4309): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,D/AutoSetting( 1547): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1547): Util - check NLP state, Allowned:true, Enabled:true
,D/AutoSetting( 1547): service - mHandler: request location update
,D/LocationManagerService(  907): request 15e7fe99 network Request[POWER_LOW network requested=+1s0ms fastest=+1s0ms] from com.htc.sense.hsp(10054),
,D/LocationManagerService(  907): provider request: network ProviderRequest[ON interval=+1s0ms]
V/GmsNetworkLocationProvi( 1769): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 1000
V/GmsNetworkLocationProvi( 1769): SET-REQUEST
D/PMS     (  907): acquireWL(6b0355e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 WorkSource{10054 com.htc.sense.hsp}
V/GmsNetworkLocationProvi( 1769): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 20000
,D/PMS     (  907): releaseWL(6b0355e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
,D/PMS     (  907): acquireWL(2dfd8d3f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 WorkSource{10054 com.htc.sense.hsp}
,D/WifiService(  907): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@13b8860c}
,E/WifiStateMachine(  907): handleMessage: E msg.what=131143
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
E/WifiStateMachine(  907): processMsg: ConnectedState
E/WifiStateMachine(  907):  ConnectedState !CMD_START_SCAN 10025 1 ic=1 proc(ms):0 dur:274 rssi=-54 f=5220 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=8.0 list=2462,5220 [on:0 tx:0 rx:0 period:1293] from screen [on:0 period:616238788]
E/WifiStateMachine(  907): processMsg: L2ConnectedState
E/WifiStateMachine(  907):  L2ConnectedState !CMD_START_SCAN 10025 1 ic=1 proc(ms):1 dur:274 rssi=-54 f=5220 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=8.0 list=2462,5220 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616238789]
E/WifiStateMachine(  907): WifiStateMachine CMD_START_SCAN source 10025 txSuccessRate=2.65 rxSuccessRate=8.03 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-54
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
,D/wpa_supplicant( 1369): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1369): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1369): wpa_supplicant_scan enter
D/wpa_supplicant( 1369): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1369): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1369): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1369): WPS:  * Request Type
D/wpa_supplicant( 1369): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1369): WPS:  * UUID-E
D/wpa_supplicant( 1369): WPS:  * Primary Device Type
D/wpa_supplicant( 1369): WPS:  * RF Bands (3)
D/wpa_supplicant( 1369): WPS:  * Association State
,D/wpa_supplicant( 1369): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1369): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1369): WPS:  * Manufacturer
D/wpa_supplicant( 1369): WPS:  * Model Name
D/wpa_supplicant( 1369): WPS:  * Model Number
D/wpa_supplicant( 1369): WPS:  * Device Name
D/wpa_supplicant( 1369): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1369): P2P: * P2P IE header
D/wpa_supplicant( 1369): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1369): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1369): wlan0: Add radio work 'scan'@0xb8226158
D/wpa_supplicant( 1369): wlan0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1369): wlan0: Starting radio work 'scan'@0xb8226158 after 0.000023 second wait
D/wpa_supplicant( 1369): wlan0: nl80211: scan request
D/wpa_supplicant( 1369): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1369): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1369): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1369): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1369): wlan0: Own scan request started a scan in 0.000061 seconds
I/wpa_supplicant( 1369): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  907): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  907): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  907): [1,448,020,217,542 ms] noteScanStartWorkSource{10054} uid 10025
E/WifiStateMachine(  907): handleMessage: X
,I/HtcCupdXmlParser( 4309): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,D/QXDM2SD:HtcNative( 1445): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/AlarmManager(  907): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  907): [AlarmQueuing] post alarm-list load task,
I/AlarmManager(  907): [AlarmQueuing] init alarm queuing list
,I/art     (  474): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 141us total 10.941ms,
,I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 8.935ms,
,I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 129us total 9.102ms
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4379 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 3744:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=3744
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 3744,
,V/Settings:HtcSettingsApplication( 4362): [4362/4362] onCreate(),
,W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
,D/Process (  907): killProcessQuiet, pid=3744
W/libprocessgroup(  907): failed to open /acct/uid_10057/pid_3744/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1d3d9dd3
,I/ActivityManager(  907): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4418 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1d84ad10
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2898c009
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  907): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  907): killProcessQuiet, pid=3778
I/ActivityManager(  907): Killing 3778:com.htc.lmw/u0a61 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,D/HtcFingerPrintQuickLaunchProvider( 4401): -onCreate()
I/ActivityManager(  907): Recipient 3778
W/ResourcesManager( 4418): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Process (  907): killProcessQuiet, pid=3778
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  907): failed to open /acct/uid_10061/pid_3778/cgroup.procs: No such file or directory
I/CalendarProvider2( 4418): Created com.android.providers.calendar.CalendarAlarmManager@2d8914fc(com.htc.providers.calendar.HtcCalendarProvider@1eaae785)
,D/CalendarProvider2( 4418): wait start:true,
,V/Settings:HtcSettingsApplication( 4401): [4401/4401] onCreate(),
,W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 ,
,D/CalendarProvider2( 4418): wait end:false
,D/TetherSettings( 4401): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4401): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4401): Cust_ConnectToPC   : Modem_Link>false,
D/        ( 4401): Cust_ConnectToPC   : spcsc>false
D/        ( 4401): Cust_ConnectToPC   : IPT>true
,D/        ( 4401): Cust_ConnectToPC   : Singel_USB>false
,D/Process (  907): killProcessQuiet, pid=3803,
I/ActivityManager(  907): Killing 3803:com.android.managedprovisioning/u0a66 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,W/Settings( 4401): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/ActivityManager(  907): Recipient 3803
,D/Process (  907): killProcessQuiet, pid=3803
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10066/pid_3803/cgroup.procs: No such file or directory
,E/SmartNS_Utility( 4401): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4401): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4401): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 4401): setISNotification
,D/SmartNS_Utility( 4401): usb_cable_connect = 1
,D/SmartNS_Utility( 4401): usb_denied = 0
,I/SmartNS_PSService( 4401): usb notificaiton:true,
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4401): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4401): usb_cable_connect = 1
,D/SmartNS_Utility( 4401): usb_denied = 0
I/SmartNS_PSService( 4401): usb notificaiton:true
,E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1203): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1124): reapply : com.android.settings 1 36
,D/Process (  907): killProcessQuiet, pid=2065
I/ActivityManager(  907): Killing 2065:com.google.android.gms/u0a25 (adj 15): empty #17
D/DotMatrix( 1203): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/RemoteViews( 1124): reapply : com.android.settings 0 36
,I/ActivityManager(  907): Recipient 2065,
,D/Process (  907): killProcessQuiet, pid=2065
W/libprocessgroup(  907): failed to open /acct/uid_10025/pid_2065/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  907): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/SmartDim(  907): Init customizeScreenOffDelayClass error,
,E/MP-Decision( 2321): Update arg 2
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{2805babe u0 ReceiverList{2074bd79 907 system/1000/u0 local:1ee57a40}}
,I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@1fdd7972, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = Accelerometer Sensor
W/SensorService(  907): pid=907, uid=1000,
,W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1fdd7972, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1dbd531a
W/SensorService(  907): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@76d7027
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@1fdd7972
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@1fdd7972, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 3
W/SensorService(  907): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1fdd7972, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1dbd531a
W/SensorService(  907): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@76d7027
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@1fdd7972
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  907): killProcessQuiet, pid=3938
I/ActivityManager(  907): Killing 3938:com.htc.cs.pns/u0a74 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=92
E/WifiTrafficPoller(  907): notifying of data activity 1
,D/WIFI_ICON( 1124): WifiActivity: 1
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  907): Recipient 3938
,D/Process (  907): killProcessQuiet, pid=3938
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10074/pid_3938/cgroup.procs: No such file or directory
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4463 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/art     (  907): Explicit concurrent mark sweep GC freed 15173(837KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 16MB/25MB, paused 1.420ms total 90.343ms
,E/MP-Decision( 2321): Update arg 1
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4463, uid=10075, userID:0
,D/Finsky  ( 4463): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4463): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  907): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4502 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 4463): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 4463): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4502): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4502): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4463, uid=10075, userID:0,
,I/MultiDex( 4502): VM with version 2.1.0 has multidex support,
I/MultiDex( 4502): install
I/MultiDex( 4502): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 4463): [586] DiskBasedCache.clear: Cache cleared.,
D/Volley  ( 4463): [593] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4502): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/Process (  907): killProcessQuiet, pid=4019,
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4522 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  907): Killing 4019:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4019,
,W/ActivityThread( 4502): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4502): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c8ca9b6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4502): Installed default security provider GmsCore_OpenSSL
,D/Process (  907): killProcessQuiet, pid=4019,
W/libprocessgroup(  907): failed to open /acct/uid_10079/pid_4019/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Finsky  ( 4463): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4463): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4463): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,W/ResourcesManager( 4522): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4463): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/MultiDex( 4522): VM with version 2.1.0 has multidex support,
I/MultiDex( 4522): install
I/MultiDex( 4522): VM has multidex support, MultiDex support library is disabled.
,D/Process (  907): killProcessQuiet, pid=4044
,I/ActivityManager(  907): Killing 4044:com.htc.showme/u0a85 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,V/JNIHelp ( 4522): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  907): Recipient 4044
,W/ActivityThread( 4522): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4522): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13a68e84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4522): Installed default security provider GmsCore_OpenSSL,
,I/HtcModeClient( 3312): handler message = 4011
E/HtcModeClient( 3312): Check connection and retry 2 times.
,D/Process (  907): killProcessQuiet, pid=4044
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10085/pid_4044/cgroup.procs: No such file or directory
,V/Finsky  ( 4463): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  907): Killing 4066:com.htc.feedback/u0a87 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4066
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 4066,
,I/CalendarProvider2( 4418): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4418): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  907): killProcessQuiet, pid=4066
,W/libprocessgroup(  907): failed to open /acct/uid_10087/pid_4066/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/GLSUser ( 1809): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  907): Killing 4088:com.htc.updater/u0a88 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4088
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 4088
,D/Process (  907): killProcessQuiet, pid=4088
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10088/pid_4088/cgroup.procs: No such file or directory
D/PMS     (  907): acquireWL(34562807): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1809 10025 null
,V/GmsCoreStatsServiceLauncher( 4522): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) },
,I/NotificationStore( 1809): System rebooted after Notification storage file was last written,
I/NotificationStore( 1809): Deleting the file
,D/PMS     (  907): releaseWL(34562807): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null,
,D/PersistentNotificationBroadcastReceiver( 1809): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) },
,E/MP-Decision( 2321): Update arg 2
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  907):  packet count Tx=55 Rx=92
,E/WifiTrafficPoller(  907): notifying of data activity 0
D/WIFI_ICON( 1124): WifiActivity: 0
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  907): handleMessage: E msg.what=131155
,E/WifiStateMachine(  907): processMsg: ConnectedState
,E/WifiStateMachine(  907):  ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-54 f=5220 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:1705] from screen [on:0 period:616240496] gl hn rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  907): processMsg: L2ConnectedState
,E/WifiStateMachine(  907):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-54 f=5220 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:616240498] gl hn rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  907):  get link layer stats 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,D/FileApkUtils( 4522): Spent 14ms computing apk sha1.
,D/FileApkUtils( 4522): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4522): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/InstanceID/Rpc( 4522): Found 10025
,D/DexOptUtils( 4522): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.,
D/FileApkUtils( 4522): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/GmsModuleFndr( 4522): Beginning GMS chimera module scan
,W/asset   ( 4522): Copying FileAsset 0xb92745d0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/GmsModuleFndr( 4522): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 4522): Beginning module configuration check
,D/ChimeraCfgMgr( 4522): Module APKs unchanged, check complete
,D/PMS     (  907): acquireWL(1c8a6c59): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4522 10025 null
,D/PMS     (  907): acquireWL(39c9701e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4522 10025 WorkSource{10025 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1809, uid=10025, userID:0
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.nearby.sharing.NearbySharingBroadcastReceiver
,E/MP-Decision( 2321): Update arg 1,
,D/PMS     (  907): acquireWL(23e91ecc): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4522 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  907): acquireWL(710be1b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4522 10025 null
,D/PMS     (  907): acquireWL(3fef5bb8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4522 10025 WorkSource{10025 com.google.android.gms}
,D/GCM     ( 4522): COMPAT: Multi user not supported
,D/GCM     ( 1809): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/PMS     (  907): acquireWL(2b7320f7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4522 10025 WorkSource{10025 com.google.android.gms},
D/PMS     (  907): releaseWL(39c9701e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(1c8a6c59): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null,
D/PMS     (  907): releaseWL(3fef5bb8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,I/CheckinService( 4522): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 4522): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/SystemUpdateService( 4522): onCreate
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4522, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4522, uid=10025, userID:0
D/PMS     (  907): acquireWL(43ada82): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4522, uid=10025, userID:0,
I/GCoreUlr( 1769): DispatchingService.onCreate()
,W/art     ( 4522): Suspending all threads took: 5.356ms
,I/art     ( 4522): Background sticky concurrent mark sweep GC freed 2372(224KB) AllocSpace objects, 8(128KB) LOS objects, 5% free, 3MB/4MB, paused 7.442ms total 30.044ms
,D/PMS     (  907): acquireWL(4cd22e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4522, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
,D/SystemUpdateService( 4522): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4522, uid=10025, userID:0,
,I/ConfigService( 1809): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4522, uid=10025, userID:0
,I/ConfigFetchService( 4522): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4522, uid=10025, userID:0
,V/AuthZen ( 4522): Handling intent: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4522, uid=10025, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4522, uid=10025, userID:0
,D/AuthZenEventHandler( 4522): Handling event: android.intent.action.BOOT_COMPLETED
,I/CheckinService( 4522): Checking schedule, now: 1448020219440 next: 1448587009483,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4522, uid=10025, userID:0
I/CheckinService( 4522): active receiver: disabled
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER,
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecb4b8a:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4522, uid=10025, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4522, uid=10025, userID:0
,D/PMS     (  907): acquireWL(1d9a9656): PARTIAL_WAKE_LOCK  Icing 0x1 4522 10025 WorkSource{10025 com.google.android.gms},
,I/GCoreUlr( 1769): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
,I/SystemUpdateService( 4522): cancelUpdate (empty URL)
,I/SystemUpdateService( 4522): active receiver: disabled
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4522, uid=10025, userID:0
,I/ConfigFetchService( 4522): service connected
,W/BaseAppContext( 4522): Using Auth Proxy for data requests.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1769, uid=10025, userID:0,
,I/GLSUser ( 4522): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/PMS     (  907): releaseWL(1d9a9656): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(2b7320f7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
,D/ConfigFetchService( 4522): ConfigApi connection successful.
,D/PMS     (  907): releaseWL(23e91ecc): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
,D/SystemUpdateService( 4522): onDestroy,
,I/GLSUser ( 4522): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/PMS     (  907): releaseWL(43ada82): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10025 com.google.android.gms}
,I/AuthZen ( 4522): Fetching signing key...
,I/AuthZen ( 4522): Signing key fetched successfully!,
I/ActivityManager(  907): Resuming delayed broadcast
,W/BaseAppContext( 4522): Using Auth Proxy for data requests.
,I/AuthZen ( 4522): Starting Enrollment...
,D/AuthZen ( 4522): getting auth token. Attempt 0,
,I/GCoreUlr( 1769): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/ChimeraCfgMgr( 4522): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  907): acquireWL(32a7bed5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(32a7bed5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1769): Unbound from all location providers
D/PMS     (  907): releaseWL(4cd22e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1769): DispatchingService.onDestroy(),
,D/PMS     (  907): acquireWL(303f7ddb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(303f7ddb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,D/ChimeraCfgMgr( 4522): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GCoreUlr( 1769): Unbound from all location providers
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0],
D/wpa_supplicant( 1369): Wireless event: cmd=0x8b19 len=8
D/wpa_supplicant( 1369): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1369): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1369): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1369): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1369): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1369): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1369): wlan0: Scan completed in 2.094744 seconds
D/wpa_supplicant( 1369): nl80211: Associated on 5220 MHz
D/wpa_supplicant( 1369): nl80211: Associated with c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1369): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1369): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:4a as associated
I/wpa_supplicant( 1369): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1369): [NULL] c2:ff:d4:d3:aa:48 freq=2462 level=-52
I/wpa_supplicant( 1369): [NULL] c0:ff:d4:d3:aa:48 freq=2462 level=-52
I/wpa_supplicant( 1369): [NULL] 38:f8:89:11:e9:11 freq=2447 level=-82
D/wpa_supplicant( 1369): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 1369): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1369): wlan0: Scan-only results received
D/wpa_supplicant( 1369): wlan0: Radio work 'scan'@0xb8226158 done in 2.095302 seconds
E/WifiStateMachine(  907): fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
E/WifiMonitor(  907): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  907): fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
D/Tethering(  907): interfaceStatusChanged wlan0, true
E/WifiConfigStore(  907): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-53 "NG7005g"WPA_PSK
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  907): calculateWifiScore freq=5220 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.32 txretriesrate=0.00 rxrate=4.52 userTriggerdPenalty0
E/WifiStateMachine(  907):  good link -> stuck count =0
E/WifiStateMachine(  907):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  907):  isHighRSSI       ---> score=61
I/GLSUser ( 1809): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1809): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/GLSActivity( 1809): [ac] getting account id
E/WifiStateMachine(  907): handleMessage: X
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4631 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/WifiStateMachine(  907): handleMessage: E msg.what=147461
I/ActivityManager(  907): Waited long enough for: ServiceRecord{17411efe u0 com.google.android.gms/.gcm.GcmService}
E/WifiStateMachine(  907): processMsg: ConnectedState
D/WIFI_ICON( 1124): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  907):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  907): RSSI current: 3 new: -54, 3
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
E/WifiStateMachine(  907): processMsg: L2ConnectedState
E/WifiStateMachine(  907):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  907): processMsg: ConnectModeState
E/WifiStateMachine(  907):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  907): processMsg: DriverStartedState
E/WifiStateMachine(  907):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  907): processMsg: SupplicantStartedState
E/WifiStateMachine(  907):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1369): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  907): [1,448,020,219,656 ms] noteScanEnd WorkSource{10054}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1369): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WirelessDisplayService(  907): getDiscoveryDongleList
E/WifiStateMachine(  907): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3470ffdd sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  907): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  907): updateSavedNetworkHistory(): try "NG7005g"WPA_PSK SSID="NG7005g" NG7005g [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  907): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  907): linkConfiguration link due to same gw "NG700" and "NG7005g" GW c0:ff:d4:d3:aa:48
E/WifiConfigStore(  907): readNetworkVariablesFromSupplicantFile key=psk
I/GLSUser ( 1809): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiConfigStore(  907): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore(  907): readNetworkVariablesFromSupplicantFile key=psk
I/GLSUser ( 1809): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1809): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1809): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1809): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/WifiConfigStore(  907): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  907): linkConfiguration: will link "NG700"WPA_PSK and "NG7005g"WPA_PSK
E/WifiConfigStore(  907):         got known scan result c0:ff:d4:d3:aa:4a key : "NG7005g"WPA_PSK num: 1 rssi=-54 freq=5220
E/WifiAutoJoinController (  907): 01ABC c2:ff:d4:d3:aa:48 rssi=-52 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  907): NG700 c0:ff:d4:d3:aa:48 rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  907): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  907): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  907): linkConfiguration link due to same gw "NG7005g" and "NG700" GW c0:ff:d4:d3:aa:48
E/WifiConfigStore(  907): readNetworkVariablesFromSupplicantFile key=psk
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiConfigStore(  907): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  907): readNetworkVariablesFromSupplicantFile key=psk
I/GLSUser ( 1809): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1809): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1809): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1809): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/WifiConfigStore(  907): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore(  907): linkConfiguration: will link "NG7005g"WPA_PSK and "NG700"WPA_PSK
E/WifiConfigStore(  907):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-52 freq=2462
E/WifiAutoJoinController (  907): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  907): ageScanResultsOut delay 40000 size 4 now 1448020219691
E/WifiAutoJoinController (  907): newSupplicantResults size=4 known=2 true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1369): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  907): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:4a
E/WifiAutoJoinController (  907): ssid=NG7005g
E/WifiAutoJoinController (  907): id=3
E/WifiAutoJoinController (  907): mode=station
E/WifiAutoJoinController (  907): pairwise_cipher=CCMP
E/WifiAutoJoinController (  907): group_cipher=CCMP
E/WifiAutoJoinController (  907): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  907): wpa_state=COMPLETED
E/WifiAutoJoinController (  907): ip_address=192.168.1.127
E/WifiAutoJoinController (  907): p2p_device_address=02:ee:bd:dd:33:d2
E/WifiAutoJoinController (  907): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  907): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  907): attemptAutoJoin() num recent config 2 current="NG7005g"WPA_PSK ---> suppNetId=3
E/WifiAutoJoinController (  907): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG7005g"WPA_PSK rssi=(-127,-54) num=(0,1)
E/WifiAutoJoinController (  907): attemptAutoJoin skip current candidate  3 key "NG7005g"WPA_PSK
E/WifiAutoJoinController (  907): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-52,-127) num=(1,0)
E/WifiAutoJoinController (  907): attemptAutoJoin trying id=2 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  907): compareNetwork will compare "NG700"WPA_PSK with current "NG7005g"WPA_PSK
E/WifiAutoJoinController (  907):     getConfigNetworkScore for "NG7005g"WPA_PSK -> no available score
E/WifiAutoJoinController (  907):     getConfigNetworkScore for "NG700"WPA_PSK -> no available score
E/WifiAutoJoinController (  907):     compareWifiConfigurationsWithScorer no-scores: "NG7005g"WPA_PSK "NG700"WPA_PSK
E/WifiAutoJoinController (  907):     compareWifiConfigurationsRSSI: "NG7005g"WPA_PSK -127,-54 boost=10 "NG700"WPA_PSK -52,-127 boost=0
E/WifiAutoJoinController (  907):         "NG7005g"WPA_PSK->:    rssi5 -54 boost 50
E/WifiAutoJoinController (  907):     compareWifiConfigurationsRSSI "NG7005g"WPA_PSK rssi=(-127,-54) num=(0,1) scorea=6 > "NG700"WPA_PSK rssi=(-52,-127) num=(1,0) scoreb=-52 -> -50
E/WifiAutoJoinController (  907): compareWifiConfigurations: "NG7005g"WPA_PSK > "NG700"WPA_PSK order -50
E/WifiAutoJoinController (  907): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK with current "NG7005g"WPA_PSK linked=true : delta=-50  -> not switching
E/WifiAutoJoinController (  907): attemptRoam: "NG7005g"WPA_PSK Found c0:ff:d4:d3:aa:4a rssi=-54 freq=5220 Current: c0:ff:d4:d3:aa:4a
D/HtcWifiControlRoamOffload: (  907): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:4a
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  907): Done attemptAutoJoin status=0
E/WifiConfigStore(  907):  writeKnownNetworkHistory() num networks:4 needWrite=false
D/WifiManager( 1769): getScanResults: Base Package Name=com.google.android.gms, uid=10025
D/WirelessDisplayService(  907): getDiscoveryDongleList
E/WifiStateMachine(  907): handleMessage: X
,I/art     (  907): Explicit concurrent mark sweep GC freed 20768(1137KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 16MB/25MB, paused 1.090ms total 77.771ms,
D/PMS     (  907): acquireWL(1416dbbc): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 WorkSource{10054 com.htc.sense.hsp}
D/LocationManagerService(  907): incoming location from: network
,D/PMS     (  907): releaseWL(1416dbbc): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(3153f7a8): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 907 1000 WorkSource{10054 com.htc.sense.hsp}
D/LocationManagerService(  907):  Report location to Reciever:  PackageName= com.htc.sense.hsp Request interval=+1s0ms
D/PMS     (  907): acquireWL(a25d2c1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 null
D/PMS     (  907): releaseWL(3153f7a8): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  907): acquireWL(2c4e654): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 907 1000 WorkSource{1000 android}
,D/PMS     (  907): acquireWL(24fbd9fd): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 907 1000 WorkSource{10054 com.htc.sense.hsp}
,D/AutoSetting( 1547): service - onStartCommand() action: com.htc.app.autosetting.location
,D/PMS     (  907): acquireWL(125516f2): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 907 1000 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): acquireWL(2c64b143): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 907 1000 WorkSource{10025 com.google.android.gms}
,D/AutoSetting( 1547): service - AddressCache: calling geocoder COUNTME
,D/PMS     (  907): releaseWL(a25d2c1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  907): acquireWL(31b413c0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 null
,W/ResourcesManager( 4631): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PMS     (  907): releaseWL(125516f2): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  907): releaseWL(2c64b143): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  907): releaseWL(31b413c0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  907): acquireWL(e3118f9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  907): releaseWL(2c4e654): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{1000 android}
D/PMS     (  907): releaseWL(24fbd9fd): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10054 com.htc.sense.hsp}
,D/WifiService(  907): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@13b8860c}
,D/PMS     (  907): acquireWL(a19b03e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 null
,D/PMS     (  907): releaseWL(2dfd8d3f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  907): releaseWL(e3118f9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  907): releaseWL(a19b03e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/GoogleURLConnFactory( 1769): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1769): Ignoring unsupported parameter: http.conn-manager.max-per-route
,I/art     ( 1809): Explicit concurrent mark sweep GC freed 7792(458KB) AllocSpace objects, 2(32KB) LOS objects, 50% free, 3MB/7MB, paused 690us total 24.748ms,
,E/AuthZen ( 4522): Error getting auth token,
E/AuthZen ( 4522): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4522): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4522): ,	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4522): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4522): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4522): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
,E/AuthZen ( 4522): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4522): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/libc    ( 1769): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1769): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1769): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1769): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1769): [NET] android_getaddrinfo_proxy+
D/libc    ( 1769): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  462): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  462): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActionCombine( 1809): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/a       ( 4522): Opening database auth.proximity.permit_store...
,W/Kids    ( 4522): [AccountUtils] Account not ready
W/Kids    ( 4522): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/Kids    ( 4522): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4522): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4522): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4522): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4522): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4522): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4522): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4522): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4522): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4522): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4522): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AuthZenTransactionCache( 4522): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4522): Clearing transaction cache
W/ResourcesManager( 1203): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1203): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1203): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
W/ResourcesManager( 1203): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1203): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1203): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc    (  462): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  462): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1769): [NET] android_getaddrinfo_proxy-, success
,I/RemoteViews( 1124): apply : com.google.android.gms 0 6 14 40
,D/libc    ( 1769): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1769): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1769): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1769): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  907): acquireWL(5fc924a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): acquireWL(305905bb): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 907 1000 WorkSource{10025}
,D/PMS     (  907): releaseWL(5fc924a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1124): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/PMS     (  907): acquireWL(20188c84): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(20188c84): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1124): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020652 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/AutoSetting( 1547): service - AddressCache: calling geocoder COUNTME
,D/AutoSetting( 1547): service - handleMessage() process successful, send out updated city
,D/AutoSetting( 1547): service - saveAndNotify() save bundle as current, complete info: true
,I/Babel_SMS( 4631): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4631): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3902): query uri: content://htc-mms-customization/mms-ua/ua_string
,E/WifiDataStallTracker(  907): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=52 rxSum=56} preTxRxSum={txSum=43 rxSum=46}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/MmsCustomizationProvider( 3902): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4631): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,I/Babel_SMS( 4631): MmsConfig.loadFromDatabase
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4631, uid=10120, userID:0
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  907):  packet count Tx=65 Rx=103
E/WifiTrafficPoller(  907): notifying of data activity 3
D/WIFI_ICON( 1124): WifiActivity: 3
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/Babel_SMS( 4631): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4631): MmsConfig.loadFromResources
E/Babel_SMS( 4631): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4631): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,D/PMS     (  907): acquireWL(28d3ecf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(305905bb): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10025}
,D/AutoSetting( 1547): service - handleMessage() remove all retry messages
,I/IntentController( 1124): receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
D/PMS     (  907): releaseWL(28d3ecf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Settings( 4631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4631): startup - clean
,I/Babel   ( 4631): deleted: false for 0,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0,
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4631, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4631, uid=10120, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4631, uid=10120, userID:0
,W/VideoCapabilities( 4631): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4631): Unsupported mime video/x-ms-wmv
W/AudioCapabilities( 4631): Unsupported mime audio/qcelp
W/AudioCapabilities( 4631): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4631): Unsupported mime audio/qcelp
W/VideoCapabilities( 4631): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4631): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4631): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4631): onServiceConnected
,W/Babel   ( 4631): Attempted to change video mute state without an active call.
,I/ActivityManager(  907): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4674 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ResourcesManager( 4674): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4674): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4674): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4674): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4674): Installed default security provider GmsCore_OpenSSL
,E/cutils-trace( 4708): Error opening trace file: No such file or directory (2),
I/dex2oat ( 4708): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1988539220.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-1988539220.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/art     ( 4674): Suspending all threads took: 8.060ms,
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  907): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24274778 mBinding = false
W/Settings:Agent(  907): MONITOR_LOG
W/Settings:Agent(  907): name: bluetooth_on
W/Settings:Agent(  907): value: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1343
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  907): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
,I/dex2oat ( 4708): dex2oat took 60.107ms (threads: 4),
,E/YouTube MDX( 4674): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE,
,D/BluetoothManagerService(  907): Sending off request.
D/BluetoothAdapterState( 3103): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/PMS     (  907): acquireWL(1206259e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3103 1002 null
D/BluetoothAdapterProperties( 3103): Setting state to 13
D/WifiService(  907): New client listening to asynchronous messages
I/BluetoothAdapterState( 3103): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3103): onBluetoothDisable()
I/bt-btm  ( 3103): BTM_SetDiscoverability
I/bt-btm  ( 3103): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3103): disc_mode 0000
I/bt-btif ( 3103): disc_mode 0000
I/bt-btm  ( 3103): evt_type=0x0 p-cb->evt_type=0x0 
I/BluetoothAdapterState( 3103): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3103): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 3103): Scan Mode:21
D/BluetoothAdapterState( 3103): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btm  ( 3103): BTM_SetConnectability
I/bt-btm  ( 3103): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/IntentController( 1124): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-btm  ( 3103): disc_mode 0000
I/bt-btm  ( 3103): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
,E/BtOppRfcommListener( 3103): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
I/bt-btif ( 3103): BTA_JvDeleteRecord
I/bt-btif ( 3103): BTA_JvRfcommStopServer
D/bt-btm  ( 3103): BTM_FreeSCN 
E/bt-btif ( 3103): cmd socket is not created
V/BluetoothSapService( 3103): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3103): cmd socket is not created
I/bt-btm  ( 3103): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3103): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3103): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3103): BTM_SEC_CLR[16]: id 58
D/WifiService(  907): setWifiEnabled: false pid=3978, uid=10380
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:10
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/bt-btm  ( 3103): BTM_SEC_CLR[17]: id 59
I/WifiService(  907): isSprintWifiRestricted(): false
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:9
I/WifiService(  907): isMdmWifiRestricted(): false
I/bt-btm  ( 3103): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3103): Write Extended Inquiry Response to controller
I/bt-btm  ( 3103): Write Extended Inquiry Response to controller
I/bt-btm  ( 3103): Write Extended Inquiry Response to controller
I/bt-btm  ( 3103): Write Extended Inquiry Response to controller
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,I/bt-btm  ( 3103): BTM_SetDiscoverability
I/bt-btm  ( 3103): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3103): disc_mode 0000
I/bt-btm  ( 3103): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3103): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3103): BTM_SetConnectability
I/bt-btm  ( 3103): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3103): disc_mode 0000
D/bt-btm  ( 3103): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3103): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3103): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3103): BTM_IsInquiryActive
,I/bt-btm  ( 3103): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3103): btm_ble_clear_white_list
W/bt-btif ( 3103): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
E/WifiTrafficPoller(  907): ADD_CLIENT: 6
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3103): BTM_FreeSCN 
I/bt-btm  ( 3103): BTM_SEC_CLR[3]: id 12
D/bt-btm  ( 3103): BTM_BleGetVendorCapabilities
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3103): BTM_FreeSCN 
D/NGFService( 3761): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/bt-btm  ( 3103): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3103): AVRC_Close handle:0
,D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3103): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0013
,I/bt-att  ( 3103): GATT_Deregister gatt_if=3
I/bt-att  ( 3103): GATT_Listen gatt_if=3
I/bt-btm  ( 3103): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3103): BTM_ReadConnectability
I/bt-btm  ( 3103): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3103): disc_mode 0000
I/bt-att  ( 3103): GATT_Deregister gatt_if=4
I/bt-att  ( 3103): GATT_Listen gatt_if=4
I/bt-btm  ( 3103): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3103): BTM_ReadConnectability
I/bt-btm  ( 3103): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3103): disc_mode 0000
E/bt-btif ( 3103): bta_gattc_deregister Deregister Failedm unknown client cif
D/WifiManager( 3978): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
W/Settings:Agent(  907): MONITOR_LOG
W/Settings:Agent(  907): name: wifi_on
W/Settings:Agent(  907): value: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1901
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  907): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  907): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 0(ms)
V/BluetoothPbapReceiver( 3103): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3103): ***********state = 13
I/BtOppRfcommListener( 3103): stopping Accept Thread
I/BtOppRfcommListener( 3103): BluetoothSocket listen thread finished
V/BluetoothPbapService( 3103): Pbap Service closeService in
V/BluetoothPbapService( 3103): successfully stopped pbap service
V/BluetoothPbapService( 3103): Pbap Service closeService out
D/PMS     (  907): acquireWL(248587f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4401 1000 null
,V/BluetoothPbapService( 3103): Pbap Service onDestroy
V/BluetoothPbapService( 3103): Pbap Service closeService in
V/BluetoothPbapService( 3103): Pbap Service closeService out
,I/bt-btm  ( 3103): btm_ble_clear_white_list_complete
W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  907): releaseWL(248587f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(722c895): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4401 1000 null
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@613fd9b:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
,D/libc    ( 4674): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4674): [NET] android_getaddrinfofornet-, SUCCESS
,I/QuickSettingBluetooth( 1124): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4738 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a
,D/BluetoothAdapter( 4401): 5537767: getState(). Returning 13
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
D/BluetoothInputDevice( 4401): BluetoothInputDevice()
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 10
D/BluetoothPan( 4401): BluetoothPan()
W/ContextImpl( 4674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/WirelessDisplayService(  907): getMirrorDisplayStatus:falsecurState:1
E/WifiStateMachine(  907): handleMessage: E msg.what=131084
E/WifiStateMachine(  907): processMsg: ConnectedState
E/WifiStateMachine(  907):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
E/WifiStateMachine(  907): processMsg: L2ConnectedState
E/WifiStateMachine(  907):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  907): processMsg: ConnectModeState
E/WifiStateMachine(  907):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  907): processMsg: DriverStartedState
E/WifiStateMachine(  907):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  907): processMsg: SupplicantStartedState
E/WifiStateMachine(  907):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
,I/jxcore-log( 3978): ****TEST TOOK:  5158  ms ****
I/jxcore-log( 3978): 
E/WifiStateMachine(  907): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  907): handleMessage: new destination call exit/enter
E/WifiStateMachine(  907): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  907): invokeExitMethods: ConnectedState
E/WifiStateMachine(  907): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  907): release()
E/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  907): setScanAlarm false period 20000 initial delay 0
D/WirelessDisplayService(  907): getMirrorDisplayStatus:falsecurState:1
I/jxcore-log( 3978): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3978): 
E/WifiStateMachine(  907): invokeExitMethods: L2ConnectedState
D/BluetoothManagerService(  907): registerStateChangeCallback+
E/WifiStateMachine(  907): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$12700 - exit - invokeExitMethods
E/WifiStateMachine(  907): handleNetworkDisconnect c0:ff:d4:d3:aa:4a config "NG7005g"WPA_PSK config.bssid any
E/WifiStateMachine(  907): handleNetworkDisconnect "NG7005g" nid=3
E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/WifiHW  (  907): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1369): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1369): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 1369): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1369): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1369): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1369): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1369): Power_Mode_Type mode = 0
I/wpa_supplicant( 1369): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1369): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
D/WifiDataStallTracker(  907): setDhcpActive: false
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 11
D/BluetoothMap( 4401): Create BluetoothMap proxy object
W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1862 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
E/BluetoothMap( 4401): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothSap( 4401): BluetoothSap() call bindService
D/BluetoothPbap( 4401): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 14
D/LocalBluetoothProfileManager( 4401): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4401): finishStartingService: stopping service
D/BluetoothInputDevice( 4401): Proxy object connected
D/HidProfile( 4401): Bluetooth service connected
D/BluetoothAdapter( 4401): 5537767: getState(). Returning 13
D/BluetoothPan( 4401): BluetoothPAN Proxy object connected
D/PanProfile( 4401): Bluetooth service connected
D/libc    (  907): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  907): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1809): Read error: ssl=0xb931a968: I/O error during system call, Connection timed out
E/WifiStateMachine(  907): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  907): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  907): acquireWL(1ccca881): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1809 10025 WorkSource{10025 com.google.android.gms}
E/WifiTrafficPoller(  907): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  907):  packet count Tx=65 Rx=105
D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiTrafficPoller(  907): notifying of data activity 1
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1124): WifiActivity: 1
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  907): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1809): SSL shutdown failed: ssl=0xb931a968: I/O error during system call, Broken pipe
E/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm 
E/WifiTrafficPoller(  907): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  907): ENABLE_DATA_MONITOR_POLL false Token 1
D/SapServerProfile( 4401): Bluetooth service connected
D/PMS     (  907): releaseWL(722c895): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/ConnectivityService(  907): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10025
,D/HtcBtWidget_BTWidgetProvider( 4738): onBTStateChanged() for widget: 
D/PMS     (  907): releaseWL(1ccca881): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
D/HtcBtWidget_BTWidgetProvider( 4738): updateWidget(context) for widget: 
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): ValidatedState{ when=-1ms what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): DefaultState{ when=-1ms what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Forcing reevaluation
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Validated
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  907): autoRoamSetBSSID any key="NG7005g"WPA_PSK
E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/WifiHW  (  907): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1369): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1369): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 1369): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
,D/wpa_supplicant( 1369): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1369): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1369): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1369): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  907): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  907): invokeExitMethods: DriverStartedState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1369): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1369): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  907): noteBatchedScanstop()
E/WifiStateMachine(  907): [1,448,020,221,039 ms] noteScanEnd no scan source
E/WifiStateMachine(  907): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  907): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  907): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  907): handleMessage: X
D/WifiMonitor(  907): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3fd915f6
E/WifiStateMachine(  907): handleMessage: E msg.what=131212
E/WifiStateMachine(  907): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  907):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): processMsg: SupplicantStartedState
E/WifiStateMachine(  907):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): processMsg: DefaultState
E/WifiStateMachine(  907):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  907): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  907): handleMessage: X
D/WifiNetworkAgent(  907): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  907): handleMessage: E msg.what=131212
E/WifiStateMachine(  907): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  907):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): processMsg: SupplicantStartedState
E/WifiStateMachine(  907):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): processMsg: DefaultState
E/WifiStateMachine(  907):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  907): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  907): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): handleMessage: E msg.what=131205
E/WifiStateMachine(  907): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  907):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  907): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  907): handleMessage: new destination call exit/enter
E/WifiStateMachine(  907): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  907): invokeExitMethods: WaitForP2pDisableState
E/WifiState,Machine(  907): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  907): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  907): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState,
,E/WifiStateMachine(  907): invokeEnterMethods: SupplicantStoppingState
I/ActivityManager(  907): Killing 4135:com.htc.android.worldclock/u0a96 (adj 15): empty #17
E/WifiStateMachine(  907): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  907): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$12700 - enter - invokeEnterMethods
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/ActivityManager(  907): Recipient 4135
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1369): Power_Mode_Type mode = 0
I/wpa_supplicant( 1369): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/wpa_supplicant( 1369): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1369): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
D/WifiDataStallTracker(  907): setDhcpActive: false
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4401): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  907): [NET] android_getaddrinfofornet+,hn 24(0x666538303a3a32),sn(),hints(known),family 0,flags 4
D/libc    (  907): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiScanningService(  907): SCAN_AVAILABLE : 1
D/RttService(  907): SCAN_AVAILABLE : 1
D/WifiScanningService(  907): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/Process (  907): killProcessQuiet, pid=4135
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
,D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
D/HtcEffectManager(  907): convertEffect after=902
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
E/WifiTrafficPoller(  907): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/RttService(  907): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1124): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0,
,D/WifiService(  907): New client listening to asynchronous messages
E/WifiTrafficPoller(  907): ADD_CLIENT: 7,
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:1,
,E/WifiStateMachine(  907): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false,
E/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1124): CM callback handler got msg 524292,
D/Nat464Xlat(  907): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
I/SecurityController( 1124): onLost 100
D/ConnectivityService(  907): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  907): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  907):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  907): Removing idletimer
,D/usbnet  (  907): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  907): acquireWL(289a4bbd): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/CSLegacyTypeTracker(  907): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:0,
,W/bt-btif ( 3103): ag scb idx 1 not allocated
,W/bt-btif ( 3103): ag scb idx 2 not allocated
E/bt-btif ( 3103): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3103): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3103): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3103): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3103): pthread_join() FAILED result:3
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL false Token 14 num clients 7,
,D/Process (  907): killProcessQuiet, pid=4135,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10096/pid_4135/cgroup.procs: No such file or directory
,E/WifiStateMachine(  907): stopping supplicant
W/WifiHW  (  907): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1369): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
,D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 1369): wlan0: Removing interface wlan0
E/ConnectivityService(  907): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1369): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:4a pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1369): TDLS: Tear down peers
D/wpa_supplicant( 1369): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiStateMachine(  907): setWifiState: disabling,
,E/ConnectivityService(  907): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::2ee:bdff:fedd:33d2/64,192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): handleMessage: E msg.what=131131
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  907): processMsg: DefaultState
,E/WifiTrafficPoller(  907): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  907):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  907): handleMessage: X
D/WIFI    (  907): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  907):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WIFI    (  907): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  907): enter WifiNetworkFactory startNetwork. mIPTStart:false
V/NetworkPolicy(  907): ensureActiveMobilePolicyLocked()
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  907): acquireWL(1df405b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
I/IntentController( 1124): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/DATA_ICON( 1124): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Connected:false/Type:-1/Status:0
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
V/NetworkPolicy(  907): updateNetworkEnabledLocked()
D/BluetoothFtpService( 3103): ACTION_STATE_CHANGED: state: 13mHasStarted: true
V/NetworkPolicy(  907): updateIfacesLocked()
E/BluetoothFtpService:RfcommSocketAcceptThread( 3103): Shutdown
V/NetworkPolicy(  907): updateNotificationsLocked()
D/WISPrService( 4401): >>>>>WISPrService start isConnected = false<<<<<
D/DATA_ICON( 1124): dataConnected: false/false
D/WISPrService( 4401): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothMasReceiver( 3103): Bluetooth STATE CHANGED to 13
D/WIFI_ICON( 1124): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): releaseWL(1df405b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/wpa_supplicant( 1369): wlan0: Event DEAUTH (12) received
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4779 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
D/wpa_supplicant( 1369): wlan0: Deauthentication notification
V/NetworkPolicy(  907): updateNetworkEnabledLocked()
D/wpa_supplicant( 1369): wlan0:  * reason 3 (locally generated)
V/NetworkPolicy(  907): updateNotificationsLocked(),
D/wpa_supplicant( 1369): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
I/wpa_supplicant( 1369): Clean 'force_connect' when disconnect
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
I/wpa_supplicant( 1369): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
D/PMS     (  907): acquireWL(98cafe): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
E/wpa_supplicant( 1369): enter disconnect check
D/UsbDeviceManager(  907): [USBNET] bCheckSuppFunc: cdc_network
I/wpa_supplicant( 1369): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiStateMachine(  907): handleMessage: E msg.what=131143
V/NetworkPolicy(  907): updateNetworkEnabledLocked()
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
,V/NetworkPolicy(  907): updateNotificationsLocked(),
D/wpa_supplicant( 1369): wlan0: Auto connect disabled: do not try to re-connect
D/PMS     (  907): releaseWL(98cafe): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1369): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1369): TDLS: Remove peers on disassociation
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1369): wlan0: Disconnect event - remove keys
I/ActivityManager(  907): Killing 4198:com.google.android.configupdater/u0a104 (adj 15): empty #17
,D/wpa_supplicant( 1369): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/WifiStateMachine(  907):  SupplicantStoppingState !CMD_START_SCAN 1000 2 ic=1 proc(ms):35 dur:2114 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:1543] from screen [on:0 period:616242443]
E/WifiStateMachine(  907): processMsg: DefaultState
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
E/WifiMonitor(  907): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
E/WifiMonitor(  907): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:4a reason=3
D/wpa_supplicant( 1369): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1369): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8222398 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1369):    addr=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1369): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1369): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1369): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1369): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1369): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1369): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1369): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1369): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1369): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1369): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1369): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1369): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1369): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1369): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1369): EAPOL: External notification - portValid=0
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/ActivityManager(  907): Recipient 4198
,D/WISPrService( 4401): >>>>>WISPrService start isConnected = false<<<<<
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  907):  DefaultState !CMD_START_SCAN 1000 2 ic=1 proc(ms):39 dur:2114 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:616242448]
D/Tethering(  907): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  907): handleMessage: X
,D/PMS     (  907): releaseWL(1206259e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiStateMachine(  907): handleMessage: E msg.what=147460
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:4a nid=1 reason=3 rt=46597
E/WifiStateMachine(  907): processMsg: DefaultState
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  907):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:4a nid=1 reason=3 rt=46597
E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): handleMessage: E msg.what=147462
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=46598  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: DISCONNECTED
,E/WifiStateMachine(  907): processMsg: DefaultState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  907):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=46598  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: DISCONNECTED
E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): handleMessage: E msg.what=196614
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !CMD_ON_QUIT 0 0
D/Tethering(  907): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  907): processMsg: DefaultState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  907):  DefaultState !CMD_ON_QUIT 0 0
D/Tethering(  907): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  907): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  907): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 4401): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapReceiver( 3103): SapReceiver onReceive 
V/BluetoothSapReceiver( 3103): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 3103):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3103): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/Tethering(  907): sendTetherStateChangedBroadcast 0, 0, 0
V/BluetoothSapService( 3103): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3103): state: 13
V/BluetoothSapService( 3103): Stopping SAP server process
D/UsbnetService(  907): BroadcastReceiver::onReceive+
E/WifiStateMachine(  907): handleMessage: E msg.what=131101
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  907): processMsg: DefaultState
,D/UsbnetService(  907): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
E/WifiStateMachine(  907):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  907): handleMessage: X
D/AuthorizationBluetoothService( 1809): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/art     (  474): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 154us total 11.529ms
V/BluetoothSapService( 3103): Sap Service closeSapService in
V/BluetoothSapService( 3103): Close listen Socket : 
,V/BluetoothSapService( 3103): Close rfcomm Socket : 
V/BluetoothSapService( 3103): Close sapd  Socket : 
I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1124): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
V/BluetoothSapService( 3103): successfully stopped Sap service
V/BluetoothSapService( 3103): Sap Service closeSapService out
V/BluetoothSapService( 3103): Sap Service onDestroycom.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@1c5de6b7
V/BluetoothSapService( 3103): Sap Service closeSapService in
V/BluetoothSapService( 3103): Close listen Socket : 
V/BluetoothSapService( 3103): Close rfcomm Socket : 
V/BluetoothSapService( 3103): Close sapd  Socket : 
,D/SapServerProfile( 4401): Bluetooth service disconnected
V/BluetoothSapService( 3103): Sap Service closeSapService out
V/BluetoothSapService( 3103): ***onDestroyed***
D/WISPrService( 4401): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4401): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Process (  907): killProcessQuiet, pid=4198
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 154us total 10.261ms
I/art     (  474): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 147us total 10.150ms
,I/bt-btif ( 3103): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3103): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3103): mProfilesStarted : true supportedProfileServices.length : 6
,E/wpa_supplicant( 1369): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
,D/wpa_supplicant( 1369): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1369): wlan0: Cancelling scan request
D/wpa_supplicant( 1369): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1369): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  907): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=32 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
W/libprocessgroup(  907): failed to open /acct/uid_10104/pid_4198/cgroup.procs: No such file or directory
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
,E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/WifiMonitor(  907): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
,E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=37 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/Process (  907): killProcessQuiet, pid=4198
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/wpa_supplicant( 1369): Remove interface wlan0 from radio phy0
D/HeadsetService( 3103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785
D/BluetoothHeadset( 1124): Proxy object disconnected
I/QuickSettingMiniLite( 1124): btListener.disconnect:HEADSET
D/A2dpService( 3103): Received stop request...Stopping profile...
D/A2dpStateMachine( 3103): Exit Disconnected: -1
D/HeadsetStateMachine( 3103): Exit Disconnected: -1
D/BluetoothHeadset(  907): Proxy object disconnected
D/BluetoothHeadset( 3761): Proxy object disconnected
D/NGFService( 3761): BluetoothHeadset onServiceDisconnected: main
D/BluetoothHeadset(  907): Proxy object disconnected
D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785
D/BluetoothA2dp(  907): Proxy object disconnected
D/HidService( 3103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785
D/BluetoothA2dp( 3761): Proxy object disconnected
D/NGFService( 3761): BluetoothA2dp onServiceDisconnected: main
D/BluetoothInputDevice( 4401): Proxy object disconnected
,D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/HidProfile( 4401): Bluetooth service disconnected,
W/BluetoothHeadsetServiceJni( 3103): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3103): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterState( 3103): Stopping profile services that were post enabled
D/HealthService( 3103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785
W/BluetoothHidServiceJni( 3103): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3103): Cleaning up Bluetooth GID callback object
D/PanService( 3103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785,
,D/BtGatt.DebugUtils( 3103): handleDebugAction() action=null
D/BluetoothPan( 4401): BluetoothPAN Proxy object disconnected
D/PanProfile( 4401): Bluetooth service disconnected
D/BtGatt.GattService( 3103): Received stop request...Stopping profile...
D/BtGatt.GattService( 3103): stop()
,D/BtGatt.AdvertiseManager( 3103): advertise clients cleared
,D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims,
,D/BluetoothAdapterService( 3103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaae785
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
W/BluetoothHealthServiceJni( 3103): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3103): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3103): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3103): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3103): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3103): Setting state to 10
I/BluetoothAdapterState( 3103): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  907): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 3103): Entering OffState
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(false) to 14 receivers.
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
I/BluetoothAdapterState( 3103): notBluetoothOff()
D/BluetoothHeadset( 3761): onBluetoothStateChange: up=false
,D/BluetoothMap( 4401): onBluetoothStateChange: up=false
E/BluetoothMap( 4401): 
E/BluetoothMap( 4401): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@17b9b52c
E/BluetoothMap( 4401): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 4401): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1914)
E/BluetoothMap( 4401): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 4401): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 4401): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4401): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothA2dp(  907): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=false
D/BluetoothPbap( 4401): onBluetoothStateChange: up=false,
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1124): onBluetoothStateChange: up=false
D/BluetoothPan( 4401): onBluetoothStateChange on: false
,D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/BluetoothHeadset(  907): onBluetoothStateChange: up=false
D/BluetoothSap( 4401): onBluetoothStateChange on: false
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=false
E/cutils-trace( 4768): Error opening trace file: No such file or directory (2)
,D/BluetoothInputDevice( 4401): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3761): onBluetoothStateChange: up=false
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/BluetoothHeadset(  907): onBluetoothStateChange: up=false
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/BluetoothManagerService(  907): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothAdapter( 3103): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@3bb77701
D/BluetoothAdapter( 3103): onBluetoothServiceDown: done
D/BluetoothAdapter(  907): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@24274778
D/BluetoothAdapter(  907): onBluetoothServiceDown: done
D/BluetoothAdapter( 3761): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3d9ec77e
D/BluetoothAdapter( 3761): onBluetoothServiceDown: done
D/BluetoothAdapter( 4401): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3b4dbbf5
D/BluetoothAdapter( 4401): onBluetoothServiceDown: done
D/BluetoothAdapter( 1445): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3c04e45c
D/BluetoothAdapter( 1445): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1124): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@12c1b424
D/WifiService(  907): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/BluetoothAdapter( 1124): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1470): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3d9ec77e
D/BluetoothAdapter( 1470): onBluetoothServiceDown: done
D/BluetoothAdapter( 3978): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1e0b85c9
D/BluetoothAdapter( 3978): onBluetoothServiceDown: done
D/wpa_supplicant( 1369): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1369): netlink: Operstate: ifindex=22 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
D/BluetoothAdapter( 4111): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@113ffdc7
D/BluetoothAdapter( 4111): onBluetoothServiceDown: done
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/BluetoothAdapter( 1769): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@30bb6dbf
D/wpa_supplicant( 1369): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 1369): nl80211: Unsubscribe mgmt frames handle 0x30aab8e9 (mode change)
I/wpa_supplicant( 1369): htc_wext_command_deinit +
I/wpa_supplicant( 1369): htc_wext_command_deinit -
I/wpa_supplicant( 1369): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1369): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1369): p2p0: Removing interface p2p0
D/wpa_supplicant( 1369): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1369): TDLS: Tear down peers
D/wpa_supplicant( 1369): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1369): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1369): netlink: Operstate: ifindex=23 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1369): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1369): EAPOL: External notification - portValid=0
D/WifiMonitor(  907): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  907): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  907): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  907): handleMessage: E msg.what=147458
E/WifiStateMachine(  907): processMsg: SupplicantStoppingState
E/WifiStateMachine(  907):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 38 0
D/BluetoothAdapter( 1769): onBluetoothServiceDown: done
D/BluetoothManagerService(  907): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24274778 mBinding = false
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothManagerService(  907): Sending unbind request.
E/WifiStateMachine(  907): Supplicant connection lost
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 13 -> 10
I/IntentController( 1124): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 3761): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NfcHandover( 1470): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 4401): setBluetoothStateOff
,D/NGFService( 3761): Bluetooth Adapter: OFF
W/BluetoothEventManager( 4401): unregister mProfileBroadcastReceiver fail
,D/TetherPref( 4401): persistRestoreBluetoothState false
,I/bt-btif ( 3103): HAL bt_hal_cbacks->thread_evt_cb
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4809 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
D/Process (  907): killProcessQuiet, pid=4180
I/ActivityManager(  907): Killing 4180:com.htc.tiber2/u0a91 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  907): Recipient 4180
,D/CustomizationManager( 4768): ====startRecUseTime====
,D/htc.customization.log.level( 4768):  is 
W/CustomizationLogLevel( 4768): Level value is invalid, use default level 2
,D/BluetoothAdapter( 1124): 527680460: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1124): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,W/BluetoothHeadset( 1124): Proxy not attached to service
,I/QuickSettingMiniLite( 1124): updateLiteState:no connect device!
,I/art     ( 3103): System.exit called, status: 0
,D/Process (  907): killProcessQuiet, pid=4180
W/libprocessgroup(  907): failed to open /acct/uid_10091/pid_4180/cgroup.procs: No such file or directory
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  907): killProcessQuiet, pid=3103,
I/ActivityManager(  907): Recipient 3103
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/Vold    (  365): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,D/CustomizationManager( 4768):  Read ACC file spent 0.048 (s),
,D/CIDMapFileReader( 4768): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4768): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__203
,D/CIDMapFileReader( 4768): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__304
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 4768): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 4768): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4768): Parsing tag category name = system
,I/CustomizationCIDLoader( 4768): Parsing tag category name = application
,I/CustomizationCIDLoader( 4768): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4768): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4768): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4768): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4768): Parsing tag category name = ACC
,D/CustomizationManager( 4768):  Read CID file spent 0.111 (s)
,D/CustomizationManager( 4768):  All configurations done spent 0.111 (s)
,E/ActTriggerJNI( 4768): open library fail.
,I/ActivityManager(  907): Process com.android.bluetooth (pid 3103) has died
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,I/BroadcastQueue(  907): Schedule to resend BroadcastRecord{18e93bd6 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=907 callingUid=1000} for ResolveInfo{90dde57 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth,
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4768, uid=2000 userid=0
,W/InstanceID/Rpc( 4674): Found 10025
,I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0xb93a58a8
,I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0xb93a5990
,I/ActivityManager(  907): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4838 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,E/WifiStateMachine(  907): setWifiState: disabled
I/ActivityManager(  907): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3978
,I/ActivityManager(  907): Killing 3978:com.example.hello/u0a380 (adj 0): stop com.example.hello
,D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,I/ActivityManager(  907): Recipient 3978
I/WindowState(  907): WIN DEATH: Window{ed03bea u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,W/ActivityManager(  907): Force removing ActivityRecord{10a406e7 u0 com.example.hello/.MainActivity t29}: app died, no saved state
E/MP-Decision( 2321): Update arg "0 380 380 380".
E/MP-Decision( 2321): Update arg "0 400 400 400".
,I/ActivityManager(  907): Force stopping com.example.hello appid=10380 user=0: pkg removed
,W/ResourcesManager( 4838): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect,
W/ActivityManager(  907): Spurious death for ProcessRecord{eeff029 3978:com.example.hello/u0a380}, curProc for 3978: null
E/WifiStateMachine(  907): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$11600 - processMessage
,E/WifiStateMachine(  907): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/Settings( 4631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DotMatrix( 1203): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1203): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1203): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/IntentController( 1124): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false),
,D/PMS     (  907): acquireWL(200befae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
W/Settings( 1769): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1124): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/PMS     (  907): releaseWL(200befae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
E/WifiStateMachine(  907): [MLHD] Error! unhandled message 6 { when=-409ms what=147458 arg1=38 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): acquireWL(2f0c10dc): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 WorkSource{10054 com.htc.sense.hsp}
E/WifiStateMachine(  907): transitionTo: destState=InitialState
I/IntentController( 1124): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1124): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  907): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1124): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/AccTypeManager( 1617): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
E/WifiStateMachine(  907): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  907): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  907): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  907): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  907): invokeEnterMethods: InitialState
,D/PMS     (  907): acquireWL(52b58ba): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/MdUtils ( 4809): [bd0.1.] subId list: (0)r0 (s0)-1
,E/Vold    (  365): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  365): Returning OperationFailed - no handler for errno 0
,D/AccTypeManager( 1617): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/FeedHostManager( 1487): [onResume]
I/FeedProviderManager( 1487): onResume
I/SocialFeedProvider( 1487): +onResume
D/PMS     (  907): releaseWL(2f0c10dc): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
I/SocialFeedProvider( 1487): updateAccounts - Accounts is no change
D/PMS     (  907): acquireWL(11ca1c3f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 null
I/SocialFeedProvider( 1487): -onResume
I/ConnectivityHelper( 1487): [getCurrentConnectionType] no network connection
D/AdapterServiceConfig( 4838): Adding HeadsetService
D/AdapterServiceConfig( 4838): Adding A2dpService
D/AdapterServiceConfig( 4838): Adding HidService
D/AdapterServiceConfig( 4838): Adding HealthService
D/AdapterServiceConfig( 4838): Adding PanService
D/AdapterServiceConfig( 4838): Adding GattService
D/WISPrService( 4401): >>>>>WISPrService start isConnected = false<<<<<
V/BluetoothPbapReceiver( 4838): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4838): ***********state = 10
D/WISPrService( 4401): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/BluetoothMasService( 4838): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
I/QuickSettingWifi( 1124): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
,D/MdScPhnSt( 4809): [bd0.1.]  listen tmrbb8
I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
D/PMS     (  907): acquireWL(3cca2010): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4401 1000 null
I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,I/QuickSettingWifi( 1124): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  907): releaseWL(3cca2010): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 4738): onBTStateChanged() for widget: 
D/StatusBarManagerService(  907): setSystemUiVisibility(0x700)
D/HtcBtWidget_BTWidgetProvider( 4738): updateWidget(context) for widget: 
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/StatusBarManagerService(  907): hiding MENU key
D/PMS     (  907): acquireWL(3948932f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4401 1000 null,
,D/DockEventReceiver( 4401): finishStartingService: stopping service,
D/PMS     (  907): releaseWL(3948932f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,E/ExternalAccountType( 1617): Unsupported attribute readOnly,
,W/PackageManager(  907): Unable to load service info ResolveInfo{158fe7d4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823),
D/PMS     (  907): releaseWL(11ca1c3f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothMasService( 4838): Add permission for SmsProvider.
D/PMS     (  907): acquireWL(127c7479): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1769 10025 null
W/System.err(  907): java.lang.Throwable: stack dump
D/PMS     (  907): acquireWL(24af550f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 WorkSource{10025 com.google.android.gms}
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  907): releaseWL(127c7479): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ca1e22:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:454)
V/BluetoothMasService( 4838): Starting MAS instances
D/BluetoothAdapter( 4838): 32967632: getState() :  mService = null. Returning STATE_OFF
I/MailMessageReceiver( 4838): reg:com.android.bluetooth.btservice.AdapterApp@ea997c9 with com.htc.util.mail.MailMessageReceiver@18eb0ece
,D/PMS     (  907): releaseWL(24af550f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/MailManager( 4838): MailManager contruct! com.htc.util.mail.MailMessageReceiver@18eb0ece
V/EmailUtils( 4838): Manager Instance is not NULL
D/PMS     (  907): acquireWL(3fc8e946): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1769 10025 null
,D/PMS     (  907): releaseWL(3fc8e946): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/MdUtils ( 4809): [bd0.2.] subId list: (0)r0 (s0)-1
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3978 uid 10380
,D/StatusBarManagerService(  907): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  907): Enable input method client, pid=1487
,D/MdUtils ( 4809): [bd0.3.] subId list: (0)r0 (s0)-1
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4861 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/StatusBarManagerService(  907): setSystemUiVisibility(0xc0000700),
,D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
,D/JobSchedulerService(  907): Receieved: android.intent.action.PACKAGE_REMOVED
,D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/TaskPersister(  907): removeObsoleteFile: deleting file=29_task.xml
D/WirelessDisplayService(  907): WIFI Trun OFF
D/WirelessDisplayService(  907): getDiscoveryDongleList
E/WifiTrafficPoller(  907): ENABLE_TRAFFIC_STATS_POLL false Token 15
,D/HtcAdjCursorFactory( 4861): Set CursorWindow size to: 4194304 KB, Tid: 4877
,W/ResourcesManager(  907): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/MdUtils ( 4809): [bd0.4.] subId list: (0)r0 (s0)-1,
,D/EmailUtils( 4838): ============NULL aList========
,V/EmailUtils( 4838): <-getEmailAccountIdList
V/BluetoothMasService( 4838): onCreate: mIsEmailEnabled: true
,D/BluetoothMasReceiver( 4838): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 4838): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 4838): SapReceiver onReceive ,
I/ActivityManager(  907): Killing 4234:com.htc.cs.dm/u0a105 (adj 15): empty #17
V/BluetoothSapReceiver( 4838): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 4838):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 4838): startService = false
D/Process (  907): killProcessQuiet, pid=4234
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  907): Recipient 4234,
,E/WifiTrafficPoller(  907): TRAFFIC_STATS_POLL false Token 16 num clients 6
,I/art     (  907): Explicit concurrent mark sweep GC freed 47984(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 17MB/25MB, paused 1.023ms total 265.457ms
,D/AuthorizationBluetoothService( 1809): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Process (  907): killProcessQuiet, pid=4234
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10105/pid_4234/cgroup.procs: No such file or directory
D/MdScDataSum( 4809): [bd0.1.] summary 99:p4 ignore
,D/MdUtils ( 4809): [bd0.1.4.] subId list: (0)r0 (s0)-1
,D/MdUtils ( 4809): [bd0.5.] subId list: (0)r0 (s0)-1
,I/art     (  907): Explicit concurrent mark sweep GC freed 4940(280KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 878us total 80.910ms
,D/Process (  907): killProcessQuiet, pid=4291
I/ActivityManager(  907): Killing 4291:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  907): Recipient 4291
,D/Tethering(  907): interfaceRemoved wlan0
E/Tethering(  907): attempting to remove unknown iface (wlan0), ignoring
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
,D/Process (  907): killProcessQuiet, pid=4291
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4291/cgroup.procs: No such file or directory
,D/Process (  907): killProcessQuiet, pid=4309,
I/ActivityManager(  907): Killing 4309:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,I/ActivityManager(  907): Recipient 4309
,D/Tethering(  907): interfaceRemoved p2p0
E/Tethering(  907): attempting to remove unknown iface (p2p0), ignoring
,D/Process (  907): killProcessQuiet, pid=4309,
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10013/pid_4309/cgroup.procs: No such file or directory
,I/ActivityManager(  907): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4906 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 4379:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  907): killProcessQuiet, pid=4379
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  907): Recipient 4379
,D/Process (  907): killProcessQuiet, pid=4379
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_10013/pid_4379/cgroup.procs: No such file or directory
,W/OpenGLRenderer( 1487): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/LocationManagerService(  907): getProviders()=[passive, network]
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4906, uid=10089, userID:0,
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4906, uid=10089, userID:0
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4936 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4906, uid=10089, userID:0,
,I/ActivityManager(  907): Killing 4362:com.android.settings:remote/1000 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4362
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,D/WifiService(  907): New client listening to asynchronous messages,
E/WifiTrafficPoller(  907): ADD_CLIENT: 7
,I/VelvetNetworkClient( 4906): Network connection not availble
,I/ActivityManager(  907): Recipient 4362
,D/Process (  907): killProcessQuiet, pid=4362
,D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4362/cgroup.procs: No such file or directory
,D/PMS     (  907): releaseWL(52b58ba): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
E/WifiStateMachine(  907): handleMessage: X
E/WifiStateMachine(  907): handleMessage: E msg.what=131155
E/WifiStateMachine(  907): processMsg: InitialState
,E/WifiStateMachine(  907):  InitialState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1522] from screen [on:0 period:616243970] gl hn rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  907): processMsg: DefaultState
,E/WifiStateMachine(  907):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616243971] gl hn rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  907): handleMessage: X
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4966 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.velour.r.aJq(VelourReleaseState.java:213)
,E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.d(SearchUrlHelper.java:1789)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.c(SearchUrlHelper.java:1482)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1671)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1690)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1614)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1402)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.s.as(SearchUrlHelper.java:1123)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:171)
E/SQLiteDatabase( 4906): 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:108)
E/SQLiteDatabase( 4906): 	at com.google.android.c.a.a.a.b.run(RefreshZeroPrefixSuggestionsTask.java:65)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4906): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4906): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/SQLiteOpenHelper( 4906): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
,E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.velour.r.aJq(VelourReleaseState.java:213)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.d(SearchUrlHelper.java:1789)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.c(SearchUrlHelper.java:1482)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1671)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1690)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1614)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1402)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.s.as(SearchUrlHelper.java:1123)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:171)
E/SQLiteOpenHelper( 4906): 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:108)
E/SQLiteOpenHelper( 4906): 	at com.google.android.c.a.a.a.b.run(RefreshZeroPrefixSuggestionsTask.java:65)
E/SQLiteOpenHelper( 4906): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 4906): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4906): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 4906): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4906): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4906): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4906): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/SQLiteOpenHelper( 4906): Opened jar_store.db in read-only mode
,W/LocationOracleImpl( 4906): Best location was null,
,I/WebViewFactory( 4906): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4906): Time to load native libraries: 3 ms (timestamps 8281-8284),
I/LibraryLoader( 4906): Expected native library version number "",actual native library version number ""
,W/art     ( 4906): Attempt to remove local handle scope entry from IRT, ignoring,
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/art     ( 4906): Attempt to remove local handle scope entry from IRT, ignoring,
,E/Search.SharedPreferencesProto( 4906): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak,
,I/Gmail   ( 4966): getAccountsCursor,
,D/Process (  907): killProcessQuiet, pid=4418
I/ActivityManager(  907): Killing 4418:com.htc.bgp/u0a11 (adj 15): empty #17
E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4966): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
,E/SQLiteDatabase( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 4966): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
E/SQLiteDatabase( 4966): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
E/SQLiteDatabase( 4966): 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
E/SQLiteDatabase( 4966): 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
E/SQLiteDatabase( 4966): 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
E/SQLiteDatabase( 4966): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4966): 	,at java.lang.Thread.run(Thread.java:818)
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
E/AndroidRuntime_2_crash( 4966): crash in the same process: AsyncTask #2
E/AndroidRuntime_2_crash( 4966): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 4966): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/AndroidRuntime_2_crash( 4966): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 4966): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 4966): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime_2_crash( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/AndroidRuntime_2_crash( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
E/AndroidRuntime_2_crash( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/AndroidRuntime_2_crash( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/AndroidRuntime_2_crash( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/AndroidRuntime_2_crash( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/AndroidRuntime_2_crash( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/AndroidRuntime_2_crash( 4966): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
E/AndroidRuntime_2_crash( 4966): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
E/AndroidRuntime_2_crash( 4966): 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
E/AndroidRuntime_2_crash( 4966): 	,at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
E/AndroidRuntime_2_crash( 4966): 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
E/AndroidRuntime_2_crash( 4966): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 4966): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 4966): 	... 3 more
E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
,E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.b(SourceFile:6995)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.t.run(SourceFile:6975)
E/SQLiteDatabase( 4966): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 4966): FATAL EXCEPTION: EmailProvider thread
E/AndroidRuntime( 4966): Process: com.google.android.gm, PID: 4966,
E/AndroidRuntime( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/AndroidRuntime( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/AndroidRuntime( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
E/AndroidRuntime( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/AndroidRuntime( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/AndroidRuntime( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/AndroidRuntime( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/AndroidRuntime( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/AndroidRuntime( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/AndroidRuntime( 4966): 	at com.android.email.provider.EmailProvider.b(SourceFile:6995)
E/AndroidRuntime( 4966): 	at com.android.email.provider.t.run(SourceFile:6975)
E/AndroidRuntime( 4966): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4966): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Recipient 4418
,E/ActivityManager(  907): App crashed! Process: com.google.android.gm,
,D/Process (  907): killProcessQuiet, pid=4418
W/libprocessgroup(  907): failed to open /acct/uid_10011/pid_4418/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4966): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
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
D/StatusBarManagerService(  907): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  907): hiding MENU key
,W/ActivityManager(  907): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4966): Error finding the version of the Email provider.....
E/Gmail   ( 4966): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4966): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4966): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4966): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4966): We do not support migrating this version of the Email provider.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4966, uid=10115, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4966, uid=10115, userID:0
I/Gmail   ( 4966): getAccountsCursor
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4966, uid=10115, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4966, uid=10115, userID:0
,I/ActivityManager(  907): Killing 4442:com.android.smith/1000 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4442
D/Process (  907): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Recipient 4442
,D/Process (  907): killProcessQuiet, pid=4442,
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_4442/cgroup.procs: No such file or directory
D/Process (  907): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.bw.<init>(SourceFile:10963)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.cj.run(SourceFile:1053)
E/SQLiteDatabase( 4966): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Gmail   ( 4966): getAccountsCursor
W/GAV2    ( 4966): Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/AndroidRuntime_3_crash( 4966): crash in the same process: MailEngine creation
E/AndroidRuntime_3_crash( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime_3_crash( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 4966): 	at com.google.android.gm.provider.bw.<init>(SourceFile:10963)
E/AndroidRuntime_3_crash( 4966): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/AndroidRuntime_3_crash( 4966): 	at com.google.android.gm.provider.cj.run(SourceFile:1053)
E/AndroidRuntime_3_crash( 4966): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime_3_crash( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime_3_crash( 4966): 	at android.os.Looper.loop(Looper.java:155),
E/AndroidRuntime_3_crash( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1487): loadItems() com.htc.launcher.pageview.WidgetManager@14fbeb22 +
I/Prism.WidgetManager( 1487): onLoadItems() +
,W/ResourcesManager( 1487): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1487): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Prism.WidgetManager( 1487): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1487): onLoadItems() -
I/Prism.ItemManager( 1487): loadItems() com.htc.launcher.pageview.WidgetManager@14fbeb22 -
,E/SQLiteLog( 1487): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=74] disk I/O error
,E/SQLiteDBG( 1487): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb91e2308
,E/AndroidRuntime( 1487): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1487): Process: com.htc.launcher, PID: 1487
E/AndroidRuntime( 1487): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1487): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1487): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1487): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1487): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1487): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.htc.launcher
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  907): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
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
,W/System.err(  907): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
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
,W/System.err(  907): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
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
,W/System.err(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  907): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  907): 	... 14 more
,W/ActivityManager(  907):   Force finishing activity com.htc.launcher/.Launcher
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1448020223550.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/PMS     (  907): acquireWL(19e85d4e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1487): [onPause]
I/FeedProviderManager( 1487): onPause
I/FeedHostManager( 1487): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@8e8a69b
I/SocialFeedProvider( 1487): +onPause
I/SocialFeedProvider( 1487): -onPause
,W/ActivityManager(  907): Can't addPackageDependency on system process
,D/HtcSystemUPManager(  907): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,I/ActivityManager(  907): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,I/OrientationManager( 1487): [release]
,I/Prism.IndicatorPagedVi_( 1487): IndicatorPagedView.nCapability with type count = 1 and capability = 20
,E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@d4c3850 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@d4c3850 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:713)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
,E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@1134aaaa that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@1134aaaa that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:98)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:475)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230),
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@11e338d6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@11e338d6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
E/ActivityThread( 1487): 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:612)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
,E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
E/ActivityThread( 1487): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1487): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ActivityThread( 1487): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@1397aa11 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@1397aa11 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767),
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:694)
E/ActivityThread( 1487): ,	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1487): ,	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/AlarmManager(  907): sending alarm PendingIntent{94f86d6: PendingIntentRecord{1175cd57 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=45674, Int=259200000
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@19d8e129 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@19d8e129 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
E/ActivityThread( 1487): 	at com.htc.feed.local.getstarted.GetStartedFeedProvider.onCreate(GetStartedFeedProvider.java:75)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
E/ActivityThread( 1487): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ActivityThread,( 1487): 	at java.lang.Thread.run(Thread.java:818)
V/AlarmManager(  907): sending alarm PendingIntent{39c1a52d: PendingIntentRecord{5953a62 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448020223637, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{221fe7f3: PendingIntentRecord{1933fcb0 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448017200000, Int=86400000
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@1a211177 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@1a211177 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:709)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): ,	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@2208b8d9 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@2208b8d9 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:152)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:443)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@24949757 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@24949757 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
E/ActivityThread( 1487): 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:669)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
E/ActivityThread( 1487): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ActivityThread( 1487): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@24b45a38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@24b45a38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:689)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostMana,ger(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@278ac776 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@278ac776 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:698)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThre,ad( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@2ae67f2d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@2ae67f2d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:320)
E/ActivityThread( 1487): 	at com.htc.feed.local.calendar.CalendarFeedAdapter.<init>(CalendarFeedAdapter.java:97)
E/ActivityThread( 1487): 	at com.htc.feed.local.calendar.CalendarFeedProvider.onCreate(CalendarFeedProvider.java:19)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
E/ActivityThread( 1487): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ActivityThread( 1487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ActivityThread( 1487): 	at java.lang.Thread.run(Thread.java:818)
I/htcbackup-core( 4257): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
I/htcbackup-core( 4257): SuperSaverModeReceiver: going to send resume event
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@36df029e that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@36df029e that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:153)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:443)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/OrientationManager( 1487): [init] currentOrienation: 1
E/ActivityThread( 1487): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@3fc30995 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@3fc30995 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1487): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1487): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1487): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1487): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1487): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:95)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:475)
E/ActivityThread( 1487): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1487): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1487): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1487): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1487): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/GCM     ( 1809): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/AppWidgetServiceImpl(  907): startListening(),set useForground = true
D/AppWidgetServiceImpl(  907): sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
W/AppWidgetServiceImpl(  907): use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
D/AppWidgetServiceImpl(  907): sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
W/AppWidgetServiceImpl(  907): use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
D/AppWidgetServiceImpl(  907): sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
W/AppWidgetServiceImpl(  907): use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
D/AppWidgetServiceImpl(  907): sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
W/AppWidgetServiceImpl(  907): use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
V/GLSActivity( 1809): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.b.b(SourceFile:83)
E/SQLiteDatabase( 4966): 	at com.android.email.provider.b.a(SourceFile:141)
E/SQLiteDatabase( 4966): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/SQLiteDatabase( 4966): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/SQLiteDatabase( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4522): Failed to open database '/data/data/com.google.android.gms/databases/iu.upload.db'.
E/SQLiteDatabase( 4522): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4522): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4522): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.autobackup.ax.getReadableDatabase(SourceFile:55)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.autobackup.af.g(SourceFile:614)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.autobackup.af.<init>(SourceFile:192)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:49)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/SQLiteDatabase( 4522): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/SQLiteDatabase( 4522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4522): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4522): Couldn't open iu.upload.db for writing (will try read-only):
E/SQLiteOpenHelper( 4522): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4522): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 4522): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.autobackup.ax.getReadableDatabase(SourceFile:55)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.autobackup.af.g(SourceFile:614)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.autobackup.af.<init>(SourceFile:192)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:49)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/SQLiteOpenHelper( 4522): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/SQLiteOpenHelper( 4522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4522): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 4522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4522): Opened iu.upload.db in read-only mode
W/ResourceType( 1487): Invalid package identifier when getting bag for resource number 0x00000014
I/htcbackup-core( 4257): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 4257): BackupRestoreManager: resume
W/GAV2    ( 4966): Thread[IntentService[com.android.email.service.EmailBroadcastProcessorService],5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/AndroidRuntime_4_crash( 4966): crash in the same process: IntentService[com.android.email.service.EmailBroadcastProcessorService]
E/AndroidRuntime_4_crash( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_4_crash( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime_4_crash( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_4_crash( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.EmailProvider.c(SourceFile:579)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.EmailProvider.e(SourceFile:1230)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.EmailProvider.a(SourceFile:424)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.EmailProvider.query(SourceFile:1437)
E/AndroidRuntime_4_crash( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/AndroidRuntime_4_crash( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/AndroidRuntime_4_crash( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/AndroidRuntime_4_crash( 4966): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.b.b(SourceFile:83)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.provider.b.a(SourceFile:141)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/AndroidRuntime_4_crash( 4966): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/AndroidRuntime_4_crash( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_4_crash( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_4_crash( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime_4_crash( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/FeedScrollGridView( 1487): velocity 0.850000
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=5027 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
D/AuthorizationBluetoothService( 1809): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Prism.IndicatorPagedVi_( 1487): IndicatorPagedView.nCapability with type count = 1 and capability = 20
V/GmsCoreStatsServiceLauncher( 4522): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.bw.<init>(SourceFile:10963)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.provider.bw.b(SourceFile:1029)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
E/SQLiteDatabase( 4966): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
E/SQLiteDatabase( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4966): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GmailIS ( 4966): Error handling intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/GmailIS ( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/GmailIS ( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/GmailIS ( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/GmailIS ( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/GmailIS ( 4966): 	at com.google.android.gm.provider.bw.<init>(SourceFile:10963)
E/GmailIS ( 4966): 	,at com.google.android.gm.provider.bw.a(SourceFile:995)
E/GmailIS ( 4966): 	at com.google.android.gm.provider.bw.b(SourceFile:1029)
E/GmailIS ( 4966): 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
E/GmailIS ( 4966): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
E/GmailIS ( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/GmailIS ( 4966): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GmailIS ( 4966): 	at android.os.Looper.loop(Looper.java:155),
E/GmailIS ( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/htcbackup-core( 4257): BackupRestoreManager: Storage is not configured
,D/HtcFooter( 1487): layerDrawableIndex = 0
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5048 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/htcbackup-core( 4257): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,I/FeedActionBar( 1487): updateLastUpdatedTime(in String) LAST UPDATED 1:00
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,I/iu.UploadsManager( 4522): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4522, uid=10025, userID:0
E/AndroidRuntime( 4522): FATAL EXCEPTION: IntentService[MediaMonitorIntentService]
E/AndroidRuntime( 4522): Process: com.google.android.gms, PID: 4522
E/AndroidRuntime( 4522): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 4522): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4522): 	at com.google.android.libraries.social.autobackup.ax.getWritableDatabase(SourceFile:48)
E/AndroidRuntime( 4522): 	at com.google.android.libraries.social.autobackup.af.a(SourceFile:307)
E/AndroidRuntime( 4522): 	at com.google.android.libraries.social.autobackup.q.a(SourceFile:26)
E/AndroidRuntime( 4522): 	at com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService.onHandleIntent(SourceFile:25)
E/AndroidRuntime( 4522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4522): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
W/ResourcesManager(  907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
W/ResourcesManager(  907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,I/Launcher( 1487): Deferring update until onResume,
I/Launcher( 1487): Deferring update until onResume
I/Prism.IndicatorPagedVi_( 1487): IndicatorPagedView.nCapability with type count = 2 and capability = 20
I/Launcher( 1487): Deferring update until onResume
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed,
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,W/ResourcesManager( 5048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
,E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,I/FeedGridScroller( 1487): updateBottomBoundary() - 0 -> 309,
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
,E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,D/PhoneApp( 1445): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1445): -- N1 =0
D/PhoneApp( 1445): -- N2 =0
D/PhoneApp( 1445): -- N3 =0
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{2893e4be u0 com.htc.autobot/.htcmodeclient.HtcModeService},
I/FeedGridScroller( 1487): updateBottomBoundary() - 309 -> 309
,I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
,I/Prism.ProxyView( 1487): onSizeChanged() w: 296, h: 420
E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,D/HtcFooter( 1487): layerDrawableIndex = 0,
W/View    ( 1487): requestLayout() improperly called by android.widget.TextView{2332fdfc V.ED.... ......ID 339,579-741,702} during layout: running second layout pass
W/View    ( 1487): requestLayout() improperly called by android.widget.TextView{33011c85 V.ED.... ......ID 72,52-264,113 #7f0e0193 app:id/load_more_text} during layout: running second layout pass
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,W/View    ( 1487): requestLayout() improperly called by com.htc.launcher.widget.WorkspaceThumbnailLayout{2207dada I.E..... ......ID 0,0-1080,678 #7f0e016a app:id/workspace_page_thubnail_container} during second layout pass: posting in next frame
,W/View    ( 1487): requestLayout() improperly called by android.widget.ImageView{a2cb0b V.ED.... ......ID 1064,0-1070,769 #7f0e0108 app:id/paged_view_indicator} during second layout pass: posting in next frame
W/View    ( 1487): requestLayout() improperly called by android.widget.ImageView{34affde8 V.ED.... ......ID 1064,622-1070,1391 #7f0e0107 app:id/paged_view_indicator_track} during second layout pass: posting in next frame
,I/ActivityManager(  907): Displayed com.htc.launcher/.Launcher: +278ms
,D/PMS     (  907): releaseWL(19e85d4e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
,E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  367): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  367): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  367): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  367): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  367): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  367): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  367): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  367): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  367): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  367): MdpCtrl close error in unset
I/HtcModeClient( 3312): handler message = 4011
E/HtcModeClient( 3312): Check connection and retry 3 times.

```
