#### Test 613623661dfc74c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/EASRequestController( 3439): [ NA ]release
I/EASAppSvc( 3439): [ NA ]< uninitEASService
I/EASAppSvc( 3439): [ NA ]- onCreate()
I/EASAppSvc( 3439): [ NA ]> onUpgrade: version = 63
--------- beginning of /dev/log/system
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3439/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3439/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3439/10064)
I/SocialFeedProvider( 1249): +disConnect socialManager
I/SocialFeedProvider( 1249): disconnect socialManager
I/SocialFeedProvider( 1249): -disConnect socialManager
D/ORMLib  ( 3211): put()
V/AlarmManager(  908): sending alarm PendingIntent{41dd5098: PendingIntentRecord{42623fc0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1456920231884, Int=0
I/EASAppSvc( 3439): [ NA ]- onDestroy()
I/EASAppSvc( 3439): [ NA ]> uninitEASService
I/EASRequestController( 3439): [ NA ]release
I/EASAppSvc( 3439): [ NA ]< uninitEASService
I/SocialManager[SocialBiLogHelper]( 3250): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3250): last commit ulog time 1456906095494
I/SocialManager[SocialBiLogHelper]( 3250): skip commit this time
I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3483 uid=10068 gids={50068, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=3156
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3156:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3156
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3211): put()
W/PackageManager(  908): Unable to load service info ResolveInfo{425e7238 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Process (  908): killProcessQuiet, pid=3170
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3170:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/SoundPicker( 3416): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3416): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3416): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3416): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3416): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3416): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3416): MODE_GSM access default DB
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3416): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3416): MODE_GSM access default DB
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  908): Recipient 3170
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
E/cutils-trace( 3495): Error opening trace file: No such file or directory (2)
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b78e08 +
I/Prism.WidgetManager( 1249): onLoadItems() +
I/Prism.ItemManager( 3250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3250): loadItems() com.htc.launcher.pageview.WidgetManager@41b60558 +
I/Prism.WidgetManager( 3250): onLoadItems() +
D/CustomizationManager( 3495): ====startRecUseTime====
D/htc.customization.log.level( 3495):  is 
W/CustomizationLogLevel( 3495): Level value is invalid, use default level 2
I/MediaStoreImporter( 3375): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/CustomizationManager( 3495):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3495): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3495): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3495): Parsing tag category name = system
I/CustomizationCIDLoader( 3495): Parsing tag category name = application
I/CustomizationCIDLoader( 3495): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3495): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3495): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3495): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3495): Parsing tag category name = Settings
D/CustomizationManager( 3495):  Read CID file spent 0.132 (s)
D/CustomizationManager( 3495):  All configurations done spent 0.132 (s)
W/HtcNativeFlag( 3495): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3495): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3495): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3495): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3495
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  908): acquireWL(4230ce30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4230ce30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4262cce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4262cce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  908): applying state to connected service
D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(42811f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4234ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42811f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4234ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  908): sending alarm PendingIntent{425ee9e0: PendingIntentRecord{4265d678 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1456920232818, Int=0
E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b78e08 -
,I/Prism.WidgetManager( 3250): onLoadItems() -
I/Prism.ItemManager( 3250): loadItems() com.htc.launcher.pageview.WidgetManager@41b60558 -
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3197): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3197): onHandleIntent
I/DFPI.ApkInstallService( 3197): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3197): check CID = HTC__032
I/DFPI.ApkInstallService( 3197): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1218): -- N1 =0
D/PhoneApp( 1218): -- N2 =0
D/PhoneApp( 1218): -- N3 =0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/SoundPicker( 3416): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3416): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3416): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3416): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3416): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3416): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3416): MODE_GSM access default DB
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244,
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,W/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3416): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3416): MODE_GSM access default DB
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3416): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3416): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3416): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3416): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 6 times.
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3375): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(42688c28): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1489 10014 null
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  908): releaseWL(42688c28): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1218): bind: false
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3519 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3532 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3266
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3266:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3266
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(425c1fa8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425c1fa8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3532): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
D/NotificationService(  908): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41c29d70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 4 8 0 10
,V/AlarmManager(  908): sending alarm PendingIntent{424a3058: PendingIntentRecord{42699bc0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456920234586, Int=0
,D/PMS     (  908): acquireWL(4266e990): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41af3410 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 1 7 0 10
,D/PMS     (  908): releaseWL(4266e990): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3563 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  908): killProcessQuiet, pid=3280
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3280:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3280
,D/PMS     (  908): acquireWL(426abea8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/iu.UploadsManager( 1965): End new media; added: 0, uploading: 0, time: 119 ms
,D/PMS     (  908): releaseWL(426abea8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3532): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3532): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3532): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3532): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel   ( 3563): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3563): MmsConfig.loadMmsSettings
,W/dalvikvm( 3563): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3563): VFY: unable to resolve instance field 36
,W/dalvikvm( 3563): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3563): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2466): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2466): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3563): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3563): MmsConfig.loadFromDatabase
E/Babel   ( 3563): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3563): MmsConfig.loadFromResources
E/Babel   ( 3563): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3563): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3563, uid=10111, userID:0
,W/Settings( 3563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3563, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3563, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3563, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3563, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3563, uid=10111, userID:0
,D/PMS     (  908): acquireWL(426a0610): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3563 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3563): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  908): releaseWL(426a0610): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(426546b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3563 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(426546b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3303
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3303:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Recipient 3303
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2583): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  908): acquireWL(42513080): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42513080): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42360c80): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42360c80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41d20d50): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41d20d50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(423fab38): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423fab38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(422e98c0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(422e98c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(420077f8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(420077f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41e83b70): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41e83b70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41b979f0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41b979f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4233f5d0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4233f5d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2583): UpdateCorporaTask done [took 282 ms] updated apps [took 282 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3610 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(425a41a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3610 10160 null
,D/PMS     (  908): releaseWL(425a41a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42647010): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3610 10160 null
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3633 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2744
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2744:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  908): acquireWL(423bdc28): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3610 10160 null
,D/PMS     (  908): releaseWL(42647010): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  908): Recipient 2744
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3610/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3610/10160)
,D/PMS     (  908): releaseWL(423bdc28): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3633, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 3323): id/is att sku: 99/false
,W/SystemReader( 3323): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 3633): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3633/10074)
,W/SystemReader( 3323): Cannot find support_harman, use default value instead
,W/SystemReader( 3323): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3323): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3323): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3323): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3323): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]support         :false
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{426d0278 u0 com.google.android.gms/.gcm.GcmService}
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]support         :false
,W/FingerprintManager( 3323): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcVoWifiWidgetEnabler( 3323): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3323): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3633/10074)
,D/Finsky  ( 3633): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 3633): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3633): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SensorManager(  908): mEventCount = 600
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3633, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3323): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3323): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3323): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3323): [supportHomeButton]support         :false
,W/FingerprintManager( 3323): hasFingerprint() - sSensorCode = 0
,D/Ads     ( 3633): Skipping gmscore version check
D/Finsky  ( 3633): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/Settings:HtcVoWifiWidgetEnabler( 3323): isSupportVoWifi: null
,D/Finsky  ( 3633): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3323): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 3633): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3633): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 3633): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
D/libc    ( 3633): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,D/Process (  908): killProcessQuiet, pid=3340
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3340:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  908): acquireWL(424c8528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  908): releaseWL(424c8528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42475ed8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/PMS     (  908): acquireWL(4260f650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(42475ed8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(4260f650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4269c8d0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.gsf/.settings.GoogleLocationSettings$LocationSettingsChangedListener
,I/ActivityManager(  908): Recipient 3340
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  908): acquireWL(425ec5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(425ec5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,W/dalvikvm( 1965): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1965): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1965): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1965): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1965): cleanUpNonGplusAccounts done.
,I/ActivityManager(  908): Resuming delayed broadcast
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/PMS     (  908): acquireWL(42834ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(42834ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426acc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(426acc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426d6ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(426d6ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426ee990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(426ee990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425f4e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428134b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3211 10071 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  908): acquireWL(427de3e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3211 10071 null
I/ActivityManager(  908): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,E/TodoTaskNotifyService( 3211): java.lang.NullPointerException
,W/System.err( 3211): java.lang.NullPointerException
W/System.err( 3211): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3211): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3211): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3211): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  908): releaseWL(428134b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  908): releaseWL(427de3e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
W/NotifyReceiver( 3211): stopSelfResult true
,D/PMS     (  908): acquireWL(426e3eb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/PMS     (  908): releaseWL(425f4e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426e3eb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  908): acquireWL(426723b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3563 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(426723b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  908): Done.
,I/WSP     ( 1320): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1320): Weather sync is On
,I/WSP     ( 1320): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Mar 02 14:03:56 CET 2016
D/ConnectivityService(  908): Setting timer for 720seconds
,W/WSP     ( 1320): [Receiver] can't get active network info
,V/WSP     ( 1320): [SyncService] no data connection, stop sync service
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3357): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/PMS     (  908): acquireWL(424cc280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(424cc280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=99
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/MediaManager( 3357): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(4269c9d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3563 10111 null
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  908): releaseWL(4269c9d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2583): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/Finsky  ( 3633): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3633): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  908): sending alarm PendingIntent{427ea1f0: PendingIntentRecord{4269b9c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456920236781, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3633): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3633): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/IcingCorporaProvider( 2583): UpdateCorporaTask done [took 203 ms] updated apps [took 203 ms] 
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(42875c70): PARTIAL_WAKE_LOCK  AsyncService 0x1 3610 10160 null
,D/PMS     (  908): releaseWL(42875c70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/TodoTaskshortcut( 3211): update TASK shortcut>
,I/Icing   ( 1965): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Scheduler( 1200): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 1200): Found 10029
,D/Icing   ( 1965): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1965): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,W/MediaManager( 3357): [DualLensScanUtil]	mmpCursor count is 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(425b8810): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3375 10154 null
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  908): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 3375): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3375): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3375): Conditions not met for autocaching.
,I/MusicLeanback( 3375): Stop autocaching.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3375, uid=10154, userID:0
D/PMS     (  908): releaseWL(425b8810): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3736 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3633): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3633/10074)
D/Finsky  ( 3633): [1] DailyHygiene.access$600: Logging device features
,D/SyncApplication( 3736): Loading default preferences
,D/Finsky  ( 3633): [1] DailyHygiene.reschedule: Scheduling new run in 749 minutes (failures=5)
,V/AlarmManager(  908): sending alarm PendingIntent{4266d320: PendingIntentRecord{42528cb8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1456920237338, Int=0
W/Resources( 3736): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 3633): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3633): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3736): Overriding preferences with custom values
,D/SyncApplication( 3736): Updating preferences succeeded
,E/SyncApplication( 3736): Application created.
D/VolumeInfo( 3736): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3736): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 3736): Found 0 mount point(s)
,V/VolumeInfo( 3736): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3736): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3736): getNewCalendarAuthority()...
,D/VolumeInfo( 3736): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3736): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3736): enableAppOperation()+
,D/SyncApplication( 3736): enableAppOperation()-
,D/HTCUtilities( 3736): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3736, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3736, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3736): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3736): isNeorSinged() return false
,D/CDMountReceiver( 3736): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3736): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3736): enable CD Auto-mount: true
,D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3736): enable auto-mount
,D/HTCUtilities( 3736): enable auto-mount
,I/ActivityManager(  908): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/RemoteViews( 1110): com.nero.android.htc.sync (false,0)
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  908): Resuming delayed broadcast
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41c388f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1110): com.nero.android.htc.sync 1 9 2 11
I/RemoteViews( 1110): com.nero.android.htc.sync (false,0)
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41ecb428 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1110): com.nero.android.htc.sync 1 7 2 16
,W/MediaManager( 3357): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3182
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3182:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3182
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42651750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(42651750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426851a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(426851a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4263f268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(4263f268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4263eb10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  908): acquireWL(428721d8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3633 10074 null
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258,
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/Finsky  ( 3633): [387] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/PMS     (  908): releaseWL(4263eb10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
D/libc    ( 3633): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(428721d8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(4261e198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,I/Icing   ( 1965): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1965): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(4269c8d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 7 times.
,I/GAV2    ( 3532): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3563): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(4262cea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=65871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1110): now=1456920240039 next=59961
,D/PMS     (  908): releaseWL(4262cea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/CheckinService( 1965): Done disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/CalendarProvider2( 1489): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1489): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3769 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3769): onCreate
D/ProviderChangeReceiver( 3769): ---------------------------------------------------
,D/ProviderChangeReceiver( 3769): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3769): start to updateAlertNotification!
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3783 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=3439
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3439:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3439
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/AlertService( 3769): No fired or scheduled alerts
,D/HtcAlertUtils( 3769): -- cancelReminderNotification --
,D/HtcAlertUtils( 3769): broadcastExistReminder!
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3783): [3783/3783] onCreate()
W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  908): killProcessQuiet, pid=3250
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3250:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/SensorManager(  908): mEventCount = 750
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{426e4228 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  908): Recipient 3250
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 8 times.
,D/PMS     (  908): acquireWL(4262aa80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4262aa80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=99
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 9 times.
,I/SensorManager(  908): mEventCount = 900
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3483
,I/ActivityManager(  908): Killing 3483:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 3483
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 10 times.
,I/SensorManager(  908): mEventCount = 1050
,D/PMS     (  908): acquireWL(425e26b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
V/AlarmManager(  908): sending alarm PendingIntent{4237a9f0: PendingIntentRecord{423c2ca8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=82689, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{427def18: PendingIntentRecord{42636410 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456920251970, Int=0
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(425e26b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 3633): [377] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3633): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(425bfb88): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/HtcModeClient( 1489): handler message = 4011
E/HtcModeClient( 1489): Check connection and retry 12 times.
,D/PMS     (  908): releaseWL(425bfb88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): mEventCount = 1200
,I/HtcModeClient( 1489): handler message = 4011
,E/HtcModeClient( 1489): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1489): Don't start project servcice
,D/HtcModeClient( 1489): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1489): connectState: CONNECTION_READY = false
D/SilentMusic( 1489): call stop
,D/HtcModeClient( 1489): close connection
,W/HtcModeClient( 1489): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1489): read the terminate packet, so break
,D/Process (  908): killProcessQuiet, pid=3197
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3197:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3197
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3799 uid=10078 gids={50078}
D/PMS     (  908): acquireWL(426ff460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10078}
,V/AlarmManager(  908): sending alarm PendingIntent{42570fe8: PendingIntentRecord{42612610 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456920269960, Int=60000
,D/PMS     (  908): releaseWL(426ff460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3799): SMSBackupAgentService started
,D/SMSBackup( 3799): Checking restore status
,D/SMSBackup( 3799): Restore complete
,D/SMSBackup( 3799): cancelCheckAlarm
,D/SMSBackup( 3799): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  908): killProcessQuiet, pid=3416,
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,I/ActivityManager(  908): Killing 3416:com.htc.sdm/u0a81 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3416
,V/LightsService(  908): setLight #0: color=#24
,V/LightsService(  908): setLight #0: color=#21
,V/LightsService(  908): setLight #0: color=#1a
,V/LightsService(  908): setLight #0: color=#14
,I/SensorManager(  908): mEventCount = 1350
,D/PMS     (  908): acquireWL(426244c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426244c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=99
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f7998
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/PMS     (  908): mWirelessDisplayManager is null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f7998, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b6ab68
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42599cd0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 324ms
,W/PnPMgr  (  353): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@422c47e8)
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1232): applyRouting -2
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  908): Disable input method client, pid=1249
D/PMN     (  908): wakingUp
D/PMS     (  908): acquireWL(422fea78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  908): releaseWL(422fea78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
,W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  908): acquireWL(42709608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  908): releaseWL(42709608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/MtpService( 2141): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NfcService( 1232): applyRouting - 0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/MtpService( 2141): [MTP][onReceive]-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=99
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/NfcService( 1232): applyRouting -2
D/PMS     (  908): acquireWL(425bec20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  908): releaseWL(425bec20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,V/NotificationService(  908): batLight: plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c80000
D/qdlights(  908): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiNative-wlan0(  908):    returned false
I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3820 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  908): batLight: plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c80000
D/qdlights(  908): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,I/ClockThread( 1110): stop update clock
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  908): updateScreenOn: false
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(4267cfe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 3820): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(425bf368): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3820 1000 null
D/PMS     (  908): releaseWL(4267cfe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(425862f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425862f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b6ab68
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b6ab68, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42599cd0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(426e8908): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
D/PMS     (  908): releaseWL(425bf368): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1249): [onPause]
,I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d24790
,I/SocialFeedProvider( 1249): +onPause
,I/SocialFeedProvider( 1249): -onPause
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20838 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  908):    returned false
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
I/AlarmManager(  908): [AlarmQueuing] wifi connection: false
D/PMS     (  908): acquireWL(42825698): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  908): releaseWL(42825698): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  908): releaseWL(426e8908): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3820): getMobilePolicyEnabled, result = true
D/AutoSetting( 1320): service - onCreate()
D/TetherSettings( 3323): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3323): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3323): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3323): Cust_ConnectToPC   : spcsc>false
D/        ( 3323): Cust_ConnectToPC   : IPT>true
D/        ( 3323): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3323): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3323): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3323): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3323): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3323): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3323): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3323): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3323):  defaultType:0
,D/LocationManagerService(  908): request 42493ab0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
,D/NetworkPolicy(  908): updateScreenOn: false
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3820): isEpsOn(), nState = 0
D/SmartSyncUtils( 3820): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3820): getMobilePolicyEnabled, result = true
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42599cd0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  908): New client listening to asynchronous messages
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42599cd0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42599cd0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42599cd0
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1528): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4259a0f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4259a0f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  908): acquireWL(42812ad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42812ad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42591610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42591610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=3397
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3397:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3397
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{425d6738 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(426d82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426d82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42851f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/HtcPowerSaver(  908): updateBatteryInfo
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): runPSCheck
D/PMS     (  908): releaseWL(42851f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=99
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - onDestroy() END
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=3519
,I/ActivityManager(  908): Killing 3519:com.htc.updater/u0a85 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  908): acquireWL(425da860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  908): sending alarm PendingIntent{42614290: PendingIntentRecord{426d5b88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122078, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{424d1e98: PendingIntentRecord{427024e0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136894, Int=0
I/ActivityManager(  908): Recipient 3519
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42850d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  908): releaseWL(42850d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425da860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42630330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42309e80: PendingIntentRecord{42309e00 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142698, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{4237a9f0: PendingIntentRecord{423c2ca8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=142700, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/PMS     (  908): acquireWL(426e3c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
,D/PMS     (  908): releaseWL(426e3c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/libc    (  908): [NET] getaddrinfo-,err=8
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-,
D/PMS     (  908): releaseWL(42630330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(427e82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427e82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=99
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,I/ClearcutLoggerApiImpl( 1356): disconnect managed GoogleApiClient
,D/PMS     (  908): acquireWL(4285df98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4285df98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4286e468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4286e468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42826518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{423aa650: PendingIntentRecord{426d5b88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181800, Int=0
D/PMS     (  908): acquireWL(423e10b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
V/AlarmManager(  908): sending alarm PendingIntent{4237a9f0: PendingIntentRecord{423c2ca8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202774, Int=0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  908): releaseWL(42826518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42624968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423e10b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42624968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427ac178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(427ac178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426a6aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): acquireWL(427a8378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1456920377241 tag=VacuumService
,D/PMS     (  908): releaseWL(426a6aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427a8378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427b04a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(427b04a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42802cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(42802cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426c4990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(426c4990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderNotification, total:0
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/TetherSettings( 3323): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3323): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3323): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3323): Cust_ConnectToPC   : spcsc>false
D/        ( 3323): Cust_ConnectToPC   : IPT>true
D/        ( 3323): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3323): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3323): Index of the first 1 = -1
W/Settings( 3323): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3323): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3323): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3323): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3323): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(426ec488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426ec488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426bf128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426bf128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(426c0680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(426c0680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(423ca7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=305871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423ca7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(423cca10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(423cca10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/Process (  908): killProcessQuiet, pid=2466
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2466:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2466
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(428168b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428168b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(427a0998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427a0998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(427a2a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427a2a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(427ed220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=425871, Int=0
,D/PMS     (  908): releaseWL(427ed220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(427ef4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427ef4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(427f0dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=485871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427f0dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42845480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42845480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42846d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=545871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42846d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42849000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42849000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4284a900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=605871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4284a900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4284cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4284cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1218): sku_id=99
D/ContactMessageStore( 1218): start background delete task...
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete,
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(426df560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=665871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426df560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426e1800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426e1800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426f36b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=725871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426f36b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426f5f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426f5f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426f7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426f7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(427962c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=785871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427962c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42798548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42798548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42799e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=845872, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42799e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4279c670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4279c670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(428539a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=905871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428539a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42855c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42855c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
,D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(428072a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428072a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42809528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42809528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4280b8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  908): sending alarm PendingIntent{41d52dc0: PendingIntentRecord{4247fd98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782321, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3872 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{4246be88: PendingIntentRecord{426320e8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1456920385771, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{422a0798: PendingIntentRecord{426cdb10 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1456920958649, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{420a4ea8: PendingIntentRecord{42688208 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456921106129, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{4240af30: PendingIntentRecord{428703a8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456921180967, Int=0
,D/PMS     (  908): acquireWL(42867bc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428698d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42867bc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3820): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3820): MY_DEBUG = false
,D/SmartSyncUtils( 3820): isEpsOn(), nState = 0
,D/PMS     (  908): releaseWL(4280b8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (3872/10049)
,I/EventLogService( 1965): Aggregate from 1456919158605 (log), 1456919158605 (data)
D/PMS     (  908): acquireWL(427d2798): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3820 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3820): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3820): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3820): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3820): SettingOnTime = 1456984800000, randomSettingOnTime = 1456982778000
,D/SmartSyncScreenOnOffTimeReceiver( 3820): SettingOffTime = 1456970400000, randomSettingOffTime = 1456976093000
,W/BatSI   (  908): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 3820): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3820): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 3820): bNightModeTurnOffOnce = false
,D/PMS     (  908): releaseWL(427d2798): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025029
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025262
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025266
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025269
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026599
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026613
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029132
,D/PMS     (  908): releaseWL(428698d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms},
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=3563
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 3563:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3563
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42564300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1025871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42564300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426298b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426298b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42826678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1085871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42826678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4283d608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4283d608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4283b790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1145871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4283b790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42845460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42845460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425e6ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1205871, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425e6ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428108b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428108b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3633): [NET] getaddrinfo-,err=8
D/libc    ( 3633): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3633): [NET] getaddrinfo-, 1
D/libc    ( 3633): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3633): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(427f13b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41b08440: PendingIntentRecord{4235f1b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1265872, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427f13b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3891): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3891): ====startRecUseTime====
D/htc.customization.log.level( 3891):  is 
W/CustomizationLogLevel( 3891): Level value is invalid, use default level 2
D/CustomizationManager( 3891):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3891): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3891): Parsing tag category name = system
I/CustomizationCIDLoader( 3891): Parsing tag category name = application
I/CustomizationCIDLoader( 3891): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3891): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3891): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3891): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3891): Parsing tag category name = Settings
D/CustomizationManager( 3891):  Read CID file spent 0.107 (s)
D/CustomizationManager( 3891):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 3891): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3891): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3891): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3891): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=3891, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  908): Skipping PackageSetting{4218d0c0 com.example.hello/10397} due to missing metadata
W/PackageSettings(  908): Skipping PackageSetting{42197798 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  908): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  908): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(428734a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(428734a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1301): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1301): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1301): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Scheme: "smsto"
I/IcingCorporaProvider( 2583): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3905 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/IcingCorporaProvider( 2583): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
E/ExternalAccountType( 1301): Unsupported attribute readOnly
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  908): Unable to load service info ResolveInfo{4244bc88 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 3905): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3905): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3905): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3905): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3905): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3905): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3905): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3905): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3905): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3905): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3905): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3905): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3905): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3905): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3905): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3905): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3905): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3905): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3905): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3905): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3905): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3905): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3905): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3905): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3905): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3905): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3905): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3905): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3905): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3905): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3905): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3905): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3905): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3905): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3905): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3905): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3905): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3905): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3905): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3905): threadid=11: thread exiting with uncaught exception (group=0x416b6e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 3905): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3905): Process: com.google.android.apps.docs, PID: 3905
E/AndroidRuntime( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3905): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3905): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3905): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3905): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3905): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteDatabase( 3905): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3905): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3905): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3905): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3905): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3905): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3905): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3905): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3905): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3905): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3905): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3905): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3905): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3905): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3905): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3905): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3905): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3905): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3905): Opened ClientFlag.db in read-only mode
D/Process ( 3905): killProcess, pid=3905
D/Process ( 3905): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3923 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Recipient 3905
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 3905) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 3923): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 3923): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3923): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 3923): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 3923): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3923): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3923): threadid=10: thread exiting with uncaught exception (group=0x416b6e30)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3937 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 3923): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3923): Process: com.android.keychain, PID: 3923
E/AndroidRuntime( 3923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3923): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 3923): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 3923): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3923): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 3923): killProcess, pid=3923
D/Process ( 3923): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1456921445689.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 3923
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 3923) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10799ms
D/AppTag  ( 3937): getInstance(Context context)
D/AppTag  ( 3937): getInstance(Context context)
D/AppTag  ( 3937): onCreate()
D/PMS     (  908): acquireWL(42563d08): PARTIAL_WAKE_LOCK  AsyncService 0x1 3610 10160 null
D/PMS     (  908): releaseWL(42563d08): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  908): killProcessQuiet, pid=3211
I/ActivityManager(  908): Killing 3211:com.htc.task/u0a71 (adj 15): empty #17
W/dalvikvm( 3633): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1965): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1965): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 1965): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 1965): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 1965): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1965): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1965): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1965): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1965): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1965): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1965): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1965): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1965): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1965): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1965): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 1965): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1965): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1965): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 1965): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3211
I/GMPM-SVC( 1965): App measurement is starting up, version: 8489
I/GMPM-SVC( 1965): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1965): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1965): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1965): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6d51c860
W/dalvikvm( 1965): threadid=37: thread exiting with uncaught exception (group=0x416b6e30)
I/Icing   ( 1965): doRemovePackageData com.test.thalitest
D/PMS     (  908): acquireWL(42894de0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteDatabase( 1965): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1965): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1965): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1965): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1965): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 1965): Opening the database failed, dropping and recreating it
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1965): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1965): Process: com.google.android.gms, PID: 1965
E/AndroidRuntime( 1965): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1965): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 1965): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1965): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1965): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1965): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1965): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1965): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 1965): killProcess, pid=1965
D/Process ( 1965): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Recipient 1965
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms (pid 1965) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10302ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10301ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20301ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20300ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20299ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30299ms
D/PMS     (  908): handleWLDeath(42894de0): PARTIAL_WAKE_LOCK  Icing 0x1
D/PMS     (  908): acquireWL(4289b610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4289b610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true

```
