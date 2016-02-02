#### Test 5797209499148df_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Process (  916): killProcessQuiet, pid=3668
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  916): Recipient 3682
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 3668
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  916): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  916): start
I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  916): applying state to connected service
D/PMS     (  916): acquireWL(430242d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(430242d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Resuming delayed broadcast
D/LocationProviderProxy(  916): applying state to connected service
D/Process (  916): killProcessQuiet, pid=3569
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3569:com.htc.task/u0a71 (adj 15): empty #17
D/PMS     (  916): acquireWL(42e50190): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42e50190): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 3855): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3855): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3855): SoundPickerReceiver [onReceive] startService
D/PMS     (  916): acquireWL(42e2dc70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3855): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3855): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3855): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3855): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 3569
D/PMS     (  916): releaseWL(42e2dc70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42e2c5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/PMS     (  916): releaseWL(42e2c5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
E/cutils-trace( 3878): Error opening trace file: No such file or directory (2)
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@422e5b98 -
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/Prism.WidgetManager( 3706): onLoadItems() -
I/Prism.ItemManager( 3706): loadItems() com.htc.launcher.pageview.WidgetManager@422c8810 -
D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1248): -- N1 =0
D/PhoneApp( 1248): -- N2 =0
D/PhoneApp( 1248): -- N3 =0
D/CustomizationManager( 3878): ====startRecUseTime====
D/htc.customization.log.level( 3878):  is 
W/CustomizationLogLevel( 3878): Level value is invalid, use default level 2
D/CustomizationManager( 3878):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3878): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3878): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3878): Parsing tag category name = system
I/CustomizationCIDLoader( 3878): Parsing tag category name = application
I/CustomizationCIDLoader( 3878): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3878): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3878): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3878): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3878): Parsing tag category name = Settings
D/CustomizationManager( 3878):  Read CID file spent 0.102 (s)
D/CustomizationManager( 3878):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 3878): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3878): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3878): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3878): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  916): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3878
,I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3893 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  916): Delay finish: com.htc.task/.TodoTaskReceiver
I/ActivityManager(  916): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3906 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
D/DFPI.PIReciver( 3625): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3625): onHandleIntent
I/DFPI.ApkInstallService( 3625): Media Scan Finished Case 
I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3625): check CID = HTC__032
I/DFPI.ApkInstallService( 3625): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/EASAppSvc( 3906): [ NA ]- onCreate()
I/EASAppSvc( 3906): [ NA ]> onUpgrade: version = 63
D/ORMLib  ( 3893): put()
I/EASAppSvc( 3906): [ NA ]- onDestroy()
I/EASAppSvc( 3906): [ NA ]> uninitEASService
D/WifiService(  916): New client listening to asynchronous messages
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.android.mail (3906/10064)
D/ConnectivityService(  916): getNetworkInfo networkType=0 called by com.htc.android.mail (3906/10064)
D/ConnectivityService(  916): getNetworkInfo networkType=55 called by com.htc.android.mail (3906/10064)
I/EASRequestController( 3906): [ NA ]release
I/EASAppSvc( 3906): [ NA ]< uninitEASService
I/EASAppSvc( 3906): [ NA ]- onCreate()
I/EASAppSvc( 3906): [ NA ]> onUpgrade: version = 63
D/Process (  916): killProcessQuiet, pid=3656
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.android.mail (3906/10064)
I/ActivityManager(  916): Killing 3656:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/ConnectivityService(  916): getNetworkInfo networkType=0 called by com.htc.android.mail (3906/10064)
D/ConnectivityService(  916): getNetworkInfo networkType=55 called by com.htc.android.mail (3906/10064)
I/ActivityManager(  916): Recipient 3656
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3893): put()
I/EASAppSvc( 3906): [ NA ]- onDestroy()
I/EASAppSvc( 3906): [ NA ]> uninitEASService
I/EASRequestController( 3906): [ NA ]release
I/ActivityManager(  916): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3938 uid=10068 gids={50068, 3003, 5012}
I/EASAppSvc( 3906): [ NA ]< uninitEASService
,D/Process (  916): killProcessQuiet, pid=3334
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3334:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 3334
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 3893): put()
,I/ActivityManager(  916): Resuming delayed broadcast,
,I/ActivityManager(  916): Killing 3694:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  916): killProcessQuiet, pid=3694
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3855): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3855): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3855): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3855): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3855): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3855): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3855): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  916): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
D/PMS     (  916): acquireWL(42b0b1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42b0b1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/ActivityManager(  916): Recipient 3694
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): [ScoreAP] + current TXpacket:52, mTXpacketCount:24, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  916): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/MediaStoreImporter( 3812): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  916): mEventCount = 450
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  916): Resuming delayed broadcast
,D/DFPI.PIReciver( 3625): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  916): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3625): onHandleIntent
I/DFPI.ApkInstallService( 3625): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3625): check CID = HTC__032
,I/DFPI.ApkInstallService( 3625): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{42dcf508 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/SoundPicker( 3855): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3855): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3855): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3855): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3855): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3855): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3855): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3855): MODE_GSM access default DB
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/ActivityManager(  916): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
V/AlarmManager(  916): sending alarm PendingIntent{42e073b0: PendingIntentRecord{42e07f50 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454416522084, Int=0
D/WIFI_ICON( 1120): WifiActivity: 0
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3855): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3855): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3855): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3855): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3812): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  916): Resuming delayed broadcast
D/PMS     (  916): acquireWL(42ee5878): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1524 10014 null,
I/ActivityManager(  916): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  916): releaseWL(42ee5878): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  916): Resuming delayed broadcast
D/TelephonyReceiver( 1248): bind: false
D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,I/ActivityManager(  916): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3970 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  916): acquireWL(42fdf470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
,D/WifiDataStallTracker(  916): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  916): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/PMS     (  916): releaseWL(42fdf470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  916): updateDataStallInfo: mDataStallTxRxSum={txSum=30 rxSum=28} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  916): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  916): onDataStallAlarm: tag=20764 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  916): startDataStallAlarm: tag=20765 delay=15s
,I/ActivityManager(  916): Delay finish: com.android.providers.contacts/.PackageIntentReceiver
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
I/ActivityManager(  916): Resuming delayed broadcast
,I/IcingCorporaProvider( 2786): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  916): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  916): acquireWL(42e2c6d0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e2c6d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e2c630): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e2c630): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e189f8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e189f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42df2ea0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 7 times.
,D/PMS     (  916): releaseWL(42df2ea0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42de00d8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42de00d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42dd71d0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42dd71d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42dcb7e0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42dcb7e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1623): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  916): notification sound not played, stream=5 volume=0 always=false
,D/PMS     (  916): acquireWL(42b435b0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/RemoteViews( 1120): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42557e60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.updater 2 10 1 10
D/PMS     (  916): releaseWL(42b435b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Resuming delayed broadcast
,I/RemoteViews( 1120): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4256cf20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.updater 2 9 0 10
D/PMS     (  916): acquireWL(4228ee48): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  916): releaseWL(4228ee48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(426e33d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3479 10160 null
,D/PMS     (  916): releaseWL(426e33d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  916): acquireWL(422ea278): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(422ea278): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{42cbfe58: PendingIntentRecord{42d569a0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454416523862, Int=0
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(42705d98): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  916): releaseWL(42705d98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4003 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,V/AlarmManager(  916): sending alarm PendingIntent{42e116e0: PendingIntentRecord{426ebd10 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454416523926, Int=0
,I/IcingCorporaProvider( 2786): UpdateCorporaTask done [took 954 ms] updated apps [took 954 ms] 
,I/iu.UploadsManager( 2179): End new media; added: 0, uploading: 0, time: 142 ms
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4003, uid=10074, userID:0
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Finsky  ( 4003): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  916): getAllNetworkInfo called by com.android.vending (4003/10074)
,D/Settings:HtcWirelessFeatureFlags( 3758): id/is att sku: 99/false
,W/SystemReader( 3758): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3758): Cannot find support_harman, use default value instead
,W/SystemReader( 3758): Cannot find effect_manager_id, use default value instead
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcWrapHeaderInfo( 3758): no such activity!
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  916): getAllNetworkInfo called by com.android.vending (4003/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3758): The wrap header doesn't exist in header list.
,D/Finsky  ( 4003): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,E/Settings:HtcWrapHeaderInfo( 3758): updateDevelopment, bPrefShow = true
,W/Settings( 4003): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4003): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Settings:HtcUmcWidgetEnabler( 3758): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]support         :false
,W/FingerprintManager( 3758): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4003): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4003): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,E/Settings:HtcVoWifiWidgetEnabler( 3758): isSupportVoWifi: null
I/ActivityManager(  916): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3758): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4003): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4003, uid=10074, userID:0
,D/Ads     ( 4003): Skipping gmscore version check
,D/Finsky  ( 4003): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4003): [1] Libraries$2.run: Finished loading 1 libraries.
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/Finsky  ( 4003): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3758): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3758): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3758): isSupportMusicChannel(): false
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportRecentAppsButton]support         :false
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  916):    returned true
W/dalvikvm( 4003): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3758): [supportHomeButton]support         :false
,W/FingerprintManager( 3758): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 3758): isSupportVoWifi: null
,D/Finsky  ( 4003): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  916): killProcessQuiet, pid=3491
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3758): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  916): Killing 3491:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  916): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4043 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/PMS     (  916): acquireWL(42cd6598): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Recipient 3491
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 4043): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/dalvikvm( 2179): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2179): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2179): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2179): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 2179): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2179): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2179): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2179, uid=10029, userID:0
,I/ActivityManager(  916): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/PeopleDatabaseHelper( 2179): cleanUpNonGplusAccounts done.
,I/ActivityManager(  916): Resuming delayed broadcast
,D/Process (  916): killProcessQuiet, pid=3729
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4070 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  916): Killing 3729:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 3729
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  916): Client connection lost with reason: 4
,I/Gmail   ( 4043): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4043): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4043): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4043): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel   ( 4070): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4070): MmsConfig.loadMmsSettings
,W/dalvikvm( 4070): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4070): VFY: unable to resolve instance field 36
,W/dalvikvm( 4070): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4070): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2131): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2131): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4070): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4070): MmsConfig.loadFromDatabase
E/Babel   ( 4070): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4070): MmsConfig.loadFromResources
,E/Babel   ( 4070): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4070): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml,
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4070, uid=10111, userID:0
,W/Settings( 4070): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4070, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4070, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4070, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4070, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4070, uid=10111, userID:0
D/PMS     (  916): acquireWL(4302a168): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4070 10111 null
I/ActivityManager(  916): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4070): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  916): releaseWL(4302a168): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(42e387c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4070 10111 null
,I/ActivityManager(  916): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  916): releaseWL(42e387c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(4235fe98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  916): killProcessQuiet, pid=3775
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  916): Killing 3775:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,I/ActivityManager(  916): Recipient 3775
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(4235fe98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42fc56b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(42fc56b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  916): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/PMS     (  916): acquireWL(42ddb8e0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  916): acquireWL(42df20d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42df20d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42ddb8e0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(42e94fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(42e94fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42e72688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(42e72688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42d31de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
,D/PMS     (  916): releaseWL(42d31de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(4282eaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
D/PMS     (  916): releaseWL(4282eaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(42bb8260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4117 uid=10041 gids={50041}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(42bb8260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42abf120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4070 10111 null,
,I/ActivityManager(  916): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  916): releaseWL(42abf120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  916): Resuming delayed broadcast
,D/ConnectivityService(  916): Sampling interval elapsed, updating statistics ..
,D/Process (  916): killProcessQuiet, pid=3555
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3555:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/ConnectivityService(  916): Done.
,D/ConnectivityService(  916): Setting timer for 720seconds
I/ActivityManager(  916): Recipient 3555
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/LocationInitializer( 2179): Restart initialization of location
D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
,E/MDM     ( 1227): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  916): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  916): acquireWL(42dd2db0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42dd2db0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Resuming delayed broadcast
D/PMS     (  916): releaseWL(42cd6598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): acquireWL(42d23090): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3893 10071 null
,D/PMS     (  916): acquireWL(42daf7c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3893 10071 null
,D/PMS     (  916): acquireWL(42b22300): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3893 10071 null
,E/TodoTaskNotifyService( 3893): java.lang.NullPointerException
,W/System.err( 3893): java.lang.NullPointerException
W/System.err( 3893): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3893): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3893): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  916): releaseWL(42d23090): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  916): acquireWL(42daf7c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3893 10071 null
D/PMS     (  916): acquireWL(42e78708): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3893 10071 null
D/PMS     (  916): releaseWL(42b22300): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/NotifyReceiver( 3893): stopSelfResult false
,E/TodoTaskNotifyService( 3893): java.lang.NullPointerException
D/PMS     (  916): releaseWL(42daf7c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 3893): java.lang.NullPointerException
W/System.err( 3893): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3893): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3893): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3893): stopSelfResult false
E/TodoTaskNotifyService( 3893): java.lang.NullPointerException
W/System.err( 3893): java.lang.NullPointerException
,W/System.err( 3893): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3893): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3893): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 3893): mStartingService is null
,W/NotifyReceiver( 3893): stopSelfResult true
D/PMS     (  916): acquireWL(42bb56d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3893 10071 null
D/PMS     (  916): releaseWL(42e78708): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  916): releaseWL(42bb56d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/WSP     ( 1347): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1347): Weather sync is On
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  916): acquireWL(42ce9020): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4070 10111 null
,I/WSP     ( 1347): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 14:35:25 CET 2016
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,D/PMS     (  916): releaseWL(42ce9020): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  916): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
D/PMS     (  916): acquireWL(430271a8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1347 10055 null
,I/IcingCorporaProvider( 2786): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  916): Resuming delayed broadcast
I/ActivityManager(  916): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  916): acquireWL(42c3a5b0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42c3a5b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42d33208): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42d33208): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42ddf020): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42ddf020): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42ce33f8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42ce33f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(430066c8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(430066c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e0a370): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e0a370): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42ba67d8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42ba67d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42aef390): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42aef390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e1dad8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e1dad8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e990b8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e990b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2786): UpdateCorporaTask done [took 250 ms] updated apps [took 250 ms] 
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  916): acquireWL(42fac7c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3479 10160 null
,D/PMS     (  916): releaseWL(42fac7c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  916): acquireWL(42fff170): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3794): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  916): Resuming delayed broadcast
D/PMS     (  916): acquireWL(42f9f730): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(42fec320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  916): releaseWL(42f9f730): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  916): releaseWL(42fec320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/MediaManager( 3794): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3893): update TASK shortcut>
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2179): Loaded CLD2 Version V2.0 - 20141016
,W/SQLiteConnectionPool( 2179): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2179, uid=10029, userID:0
I/CheckinService( 2179): Done disabling old GoogleServicesFramework version
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2179, uid=10029, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2179, uid=10029, userID:0
D/PMS     (  916): releaseWL(42fff170): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1120): WifiActivity: 1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 8 times.
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/GAV2    ( 4043): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4070): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/PMS     (  916): acquireWL(42e66b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(42e66b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/Process (  916): killProcessQuiet, pid=3706
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3706:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 3706
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 1524): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1524): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(42de00d8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3812 10154 null
,I/ActivityManager(  916): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3812): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3812, uid=10154, userID:0
,I/MusicLeanback( 3812): Conditions not met for autocaching.
,I/MusicLeanback( 3812): Stop autocaching.
,W/ContextImpl( 3812): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  916): releaseWL(42de00d8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{42e7ca38 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4172 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4172): Loading default preferences
,W/Resources( 4172): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  916): New client listening to asynchronous messages
,D/SyncApplication( 4172): Overriding preferences with custom values
,D/SyncApplication( 4172): Updating preferences succeeded
,E/SyncApplication( 4172): Application created.
D/VolumeInfo( 4172): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4172): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4172): Found 0 mount point(s)
,V/VolumeInfo( 4172): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4172): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4172): getNewCalendarAuthority()...
D/VolumeInfo( 4172): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,D/SyncApplication( 4172): enableAppOperation()+
,W/VolumeInfo( 4172): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4172): enableAppOperation()-
,D/HTCUtilities( 4172): isNeorSinged() + 
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4172, uid=10008, userID:0
W/PackageManager(  916): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4172, uid=10008, userID:0
W/PackageManager(  916): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,W/MediaManager( 3794): [DualLensScanUtil]	mmpCursor count is 0
,D/HTCUtilities( 4172): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4172): isNeorSinged() return false
,D/CDMountReceiver( 4172): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4172): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4172): enable CD Auto-mount: true
,D/DotMatrix( 1623): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4172): enable auto-mount
,D/PMS     (  916): releaseWL(42dd8c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/HTCUtilities( 4172): enable auto-mount
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
I/ActivityManager(  916): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/MountService(  916): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  916): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  916): Resuming delayed broadcast
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{4258df50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 3 12 4 11
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
I/ActivityManager(  916): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{423f96a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  916): Resuming delayed broadcast
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 0 10 3 16
,D/PMS     (  916): acquireWL(42d14a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): releaseWL(42d14a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e0ec80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(42e0ec80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,W/MediaManager( 3794): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  916): killProcessQuiet, pid=3906
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3906:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/PMS     (  916): acquireWL(42d7ca38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  916): Recipient 3906
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  916): Client connection lost with reason: 4
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  916): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4195 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(42d7ca38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarApplication( 4195): onCreate
D/ProviderChangeReceiver( 4195): ---------------------------------------------------
,D/ProviderChangeReceiver( 4195): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4195): start to updateAlertNotification!
,I/ActivityManager(  916): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4209 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  916): killProcessQuiet, pid=3938
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  916): Killing 3938:com.htc.task.gtask/u0a68 (adj 15): empty #17
,D/AlertService( 4195): No fired or scheduled alerts
,D/HtcAlertUtils( 4195): -- cancelReminderNotification --
,D/HtcAlertUtils( 4195): broadcastExistReminder!
I/ActivityManager(  916): Recipient 3938
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4209): [4209/4209] onCreate()
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  916): killProcessQuiet, pid=3625
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3625:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 3625
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 9 times.
,D/PMS     (  916): releaseWL(430271a8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72,
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): [ScoreAP] + current TXpacket:52, mTXpacketCount:52, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  916): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/Finsky  ( 4003): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4003): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  916): acquireWL(42fa8780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10074}
,I/SensorManager(  916): mEventCount = 600
V/AlarmManager(  916): sending alarm PendingIntent{42d36850: PendingIntentRecord{42cd6a20 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454416536513, Int=0
D/PMS     (  916): releaseWL(42fa8780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.android.vending (4003/10074)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4003): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4003): [NET] getaddrinfo-,err=8
D/libc    ( 4003): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4003): [NET] getaddrinfo-, 1
,D/libc    ( 4003): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =193a +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4003): [NET] getaddrinfo_proxy-, success
,I/global  ( 4003): call createSocket() return a new socket.
D/libc    ( 4003): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4003): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4003): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4003): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4003): untagSocket(69) failed with errno -22
,D/Finsky  ( 4003): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4003): untagSocket(69) failed with errno -22
,D/PMS     (  916): acquireWL(42e72688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,D/WifiDataStallTracker(  916): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  916): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  916): updateDataStallInfo: mDataStallTxRxSum={txSum=48 rxSum=44} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  916): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  916): onDataStallAlarm: tag=20765 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  916): startDataStallAlarm: tag=20766 delay=15s
V/AlarmManager(  916): sending alarm PendingIntent{42c01080: PendingIntentRecord{42b168d0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=78435, Int=0
D/PMS     (  916): releaseWL(42e72688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4003): untagSocket(69) failed with errno -22
,D/ConnectivityService(  916): getNetworkInfo networkType=0 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4003/10074)
,D/Finsky  ( 4003): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  916): acquireWL(42cb1ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10074}
,V/AlarmManager(  916): sending alarm PendingIntent{42badde0: PendingIntentRecord{42c0f030 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454416538631, Int=0
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/PMS     (  916): acquireWL(42c5e138): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4003 10074 null
,D/PMS     (  916): releaseWL(42cb1ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4003): [428] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1227): client connected with version: 8296000
,D/Finsky  ( 4003): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4003): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 10 times.
,D/libc    ( 4003): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4003): [NET] getaddrinfo-,err=8
D/libc    ( 4003): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4003): [NET] getaddrinfo-, 1
D/libc    ( 4003): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =d092 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  362): [NET]res_nsend:resplen=87
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4003): [NET] getaddrinfo_proxy-, success
,D/PMS     (  916): releaseWL(42c5e138): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [53][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1347): service - mHandler: update timezone
,D/AutoSetting( 1347): service - handleMessage() stop self
,D/AutoSetting( 1347): service - onDestroy() END
,D/Process (  916): killProcessQuiet, pid=3855
,D/AutoSetting( 1347): service - handleMessage() quit looper
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3855:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 3855
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1524): service - onCreate()
W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1524): service - mHandler: update timezone
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1524): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1524): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1623): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1623): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42671cc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 1 7 3 11
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 11 times.
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  916):    returned true,
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 12 times.
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): [ScoreAP] + current TXpacket:106, mTXpacketCount:52, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  916): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  916): acquireWL(42e596c0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e596c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e793a8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  916): onReceive: action=com.android.internal.wifi.data-stall
,D/PMS     (  916): acquireWL(42dc78f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000},
,D/WifiDataStallTracker(  916): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  916): updateDataStallInfo: mDataStallTxRxSum={txSum=82 rxSum=93} preTxRxSum={txSum=48 rxSum=44}
D/WifiDataStallTracker(  916): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  916): onDataStallAlarm: tag=20766 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  916): startDataStallAlarm: tag=20767 delay=15s
V/AlarmManager(  916): sending alarm PendingIntent{42e2ee90: PendingIntentRecord{42b168d0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=93439, Int=0
D/PMS     (  916): releaseWL(42dc78f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): releaseWL(42e793a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42d80e38): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42d80e38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fd3ae8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42fd3ae8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  916): mEventCount = 750
,I/HtcModeClient( 1524): handler message = 4011
,E/HtcModeClient( 1524): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1524): Don't start project servcice
,D/HtcModeClient( 1524): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1524): connectState: CONNECTION_READY = false
,D/SilentMusic( 1524): call stop
D/HtcModeClient( 1524): close connection
,W/HtcModeClient( 1524): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1524): read the terminate packet, so break
,D/PMS     (  916): acquireWL(42d4e6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10074}
,V/AlarmManager(  916): sending alarm PendingIntent{42e1b990: PendingIntentRecord{42decec0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454416552961, Int=0
,I/ActivityManager(  916): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4239 uid=10078 gids={50078}
,V/AlarmManager(  916): sending alarm PendingIntent{42ce9cf0: PendingIntentRecord{42e33a30 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454416554090, Int=60000
,D/PMS     (  916): releaseWL(42d4e6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SMSBackup( 4239): SMSBackupAgentService started
,D/SMSBackup( 4239): Checking restore status,
,D/SMSBackup( 4239): Restore complete
,D/SMSBackup( 4239): cancelCheckAlarm
,D/SMSBackup( 4239): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/Finsky  ( 4003): [419] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4003): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  916): killProcessQuiet, pid=3970
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3970:com.htc.updater/u0a85 (adj 15): empty #17
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  916): Recipient 3970
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{42ae4260 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  916): setLight #0: color=#3e
,V/LightsService(  916): setLight #0: color=#38
,V/LightsService(  916): setLight #0: color=#31
,V/LightsService(  916): setLight #0: color=#2a
,V/LightsService(  916): setLight #0: color=#24
,V/LightsService(  916): setLight #0: color=#1d
,V/LightsService(  916): setLight #0: color=#16
,V/LightsService(  916): setLight #0: color=#14
,D/PMS     (  916): acquireWL(42dea6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=101028, Int=0
,D/PMS     (  916): releaseWL(42dea6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1120): now=1454416560060 next=59940
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  916): mEventCount = 900
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  916): Going to sleep due to screen timeout...
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4292d0e0
,W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  916): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  916): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  916): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4292d0e0, eanble = 0, strlen(mName) = 59
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  916): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427b0c58
W/SensorService(  916): Listener[1] = com.htc.smartdim.sensor_eye@42a89bc0
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  916): mWirelessDisplayManager is null
V/LightsService(  916): setLight #2: color=#0
D/qdlights(  916): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  916): Couldn't get kernel wake lock stats
V/LightsService(  916): setLight #0: color=#0
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): [ScoreAP] + current TXpacket:106, mTXpacketCount:106, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  916): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/SurfaceControl(  916): Excessive delay in blankDisplay() while turning screen off: 337ms
,W/PnPMgr  (  355): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  916): nativeSetInteractive:false
D/PMS     (  916): nativeSetInteractive:false done
D/PMS     (  916): nativeSetAutoSuspend:true
D/PMS     (  916): nativeSetAutoSuspend:true done
D/HABCtrl (  916): TPE algorithm. remove timeout.
D/PMS     (  916): OOBE c monitor 11
I/InputManager(  916): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1260): ScreenObserver: OFF
,D/NfcService( 1260): applyRouting - 0
I/InputMethodManagerService(  916): screenObserver, isScreenOn=false
I/InputMethodManagerService(  916): Disable input method client, pid=1277
,V/KeyguardServiceDelegate(  916): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42d8b5d8)
,D/NfcService( 1260): applyRouting -2
,V/KeyguardServiceDelegate(  916): **** SHOWN CALLED ****
D/PMN     (  916): wakingUp
D/PMS     (  916): acquireWL(42d8be58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  916): releaseWL(42d8be58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  916): No lock screen! windowToken=null
,D/PMS     (  916): acquireWL(4301ef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMN     (  916): onScreenOn
D/AlarmManager(  916): ACTION_SCREEN_ON
I/AlarmManager(  916): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  916): [AlarmQueuing] done recovering
I/AlarmManager(  916): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WirelessDisplayService(  916): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/AlarmManager(  916): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  916): releaseWL(4301ef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_ON
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  916): updateBatteryInfo
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiDataStallTracker(  916): startDataStallAlarm: tag=20768 delay=15s
D/MtpService( 2691): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2691): [MTP][onReceive]-
,D/NfcService( 1260): applyRouting - 0
,D/NfcService( 1260): applyRouting -2
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
D/PMS     (  916): acquireWL(42e45268): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
D/PMS     (  916): releaseWL(42e45268): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/ClockThread( 1120): stop update clock
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1140): SET_SCREEN_ON:On
I/wpa_supplicant( 1140): htc_wext_set_keepalive +
I/wpa_supplicant( 1140): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1140): getPrivFuncNum +	
I/wpa_supplicant( 1140): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1140): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1140): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1140): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1140): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  916):    returned true
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ActivityManager(  916): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4258 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1140): WiFioffload: SignalStrength: =97
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiNative-wlan0(  916):    returned true
,D/NetworkPolicy(  916): updateScreenOn: false
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  916): acquireWL(42dc83a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42dc83a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42dc9890): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42dc9890): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4258): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1796): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): onScreenOn: 1454416567408
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1796): onScreenOn: 1454416567408
D/PMS     (  916): acquireWL(42d6fcd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4258 1000 null
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427b0c58
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427b0c58, eanble = 0, strlen(mName) = 91
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  916): Listener[0] = com.htc.smartdim.sensor_eye@42a89bc0
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  916): goingToSleep
D/PMS     (  916): releaseWL(42d6fcd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  916): acquireWL(42fab150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 916 1000 null
,I/FeedHostManager( 1277): [onPause]
,I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424106b8
I/SocialFeedProvider( 1277): +onPause
,I/SocialFeedProvider( 1277): -onPause
D/AlarmManager(  916): ACTION_SCREEN_OFF
D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=20768 mDataStallAlarmIntent=PendingIntent{42b0b1f0: PendingIntentRecord{42b168d0 android broadcastIntent}}
,D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1140): SET_SCREEN_ON:Off
I/wpa_supplicant( 1140): htc_wext_set_keepalive +
I/wpa_supplicant( 1140): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1140): getPrivFuncNum +	
I/wpa_supplicant( 1140): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1140): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1140): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1140): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1140): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  916):    returned true
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  916): [AlarmQueuing] screen off now: 
I/AlarmManager(  916): [AlarmQueuing] data connection: true
I/AlarmManager(  916): [AlarmQueuing] wifi connection: true
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
D/PMS     (  916): acquireWL(42f0b168): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 916 1000 null
,V/SRS_Proc(  369): ParamSet string: screen_state=off
D/PMS     (  916): releaseWL(42fab150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4258): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1347): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  916): updateScreenOn: false
D/AutoSetting( 1347): service - onCreate()
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/AutoSetting( 1347): service - AddressCache: using context: com.htc.Weather
D/wpa_supplicant( 1140): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  916):    returned true
D/TetherSettings( 3758): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3758): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3758): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3758): Cust_ConnectToPC   : spcsc>false
D/        ( 3758): Cust_ConnectToPC   : IPT>true
D/        ( 3758): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3758): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3758): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3758): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3758): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1347): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  916): releaseWL(42f0b168): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/LocationManagerService(  916): request 42ca71d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  916): provider request: passive ProviderRequest[ON interval=0]
,I/PSReceiver( 3758): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3758): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3758): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3758):  defaultType:0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  916): acquireWL(42cf4528): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42cf4528): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4258): isEpsOn(), nState = 0
,D/PMS     (  916): acquireWL(42cf5a40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 4258): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4258): isEpsOn(), nState = 0
D/WifiService(  916): New client listening to asynchronous messages
D/PMS     (  916): releaseWL(42cf5a40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a89bc0
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 1
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a89bc0, eanble = 0, strlen(mName) = 36
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  916): disable: get sensor name = CM36282 Proximity sensor
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1796): onScreenOff.
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): onScreenOff
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a89bc0, eanble = 0, strlen(mName) = 36
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): disableBatteryAlarm
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1796): onScreenOff
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a89bc0
E/ActivityThread(  916): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4236e2f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4236e2f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  916): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  916): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  916): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  916): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  916): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  916): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  916): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1524): service - handleMessage() stop self
,D/AutoSetting( 1524): service - onDestroy() END
,D/AutoSetting( 1524): service - handleMessage() quit looper
,D/Process (  916): killProcessQuiet, pid=2131
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 2131:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  916): Recipient 2131
,D/Process (  916): killProcessQuiet, pid=3835
,I/ActivityManager(  916): Killing 3835:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 3835
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1347): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1347): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1347): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{42de4960 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  916): acquireWL(42f73b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42f73b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1347): service - handleMessage() stop self
,D/AutoSetting( 1347): service - handleMessage() quit looper
D/PMS     (  916): acquireWL(42fb5e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  916): sending alarm PendingIntent{42e76950: PendingIntentRecord{42d8a010 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126343, Int=0
V/AlarmManager(  916): sending alarm PendingIntent{42d8ad30: PendingIntentRecord{42e096f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138617, Int=0
D/PMS     (  916): acquireWL(42fb7628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/AutoSetting( 1347): service - onDestroy() END
,D/Process (  916): killProcessQuiet, pid=4117
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  916): Killing 4117:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4117
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(42ff9458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42ff9458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42fb7628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fcc5d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,D/PMS     (  916): releaseWL(42fb5e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42fcc5d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fe55e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): acquireWL(42e89a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fbfe80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1227): Vacuum at: now=1454416597878 tag=VacuumService
,D/PMS     (  916): releaseWL(42fe55e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fc5048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42fc5048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42fbfe80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42fa4450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42e89a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836,
,D/PMS     (  916): releaseWL(42fa4450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f8a3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42f8a3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f69748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42f69748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f70808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{426f31a8: PendingIntentRecord{42b927d0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142308, Int=0
,D/GpsLocationProvider(  916): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  916): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  916): acquireWL(42edb8b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/PMS     (  916): releaseWL(42f70808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
,D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =abd5 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=243
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo_proxy-, success
I/global  (  916): call createSocket() return a new socket.
D/libc    (  916): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  916): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  916): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  916): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  916):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  916): releaseWL(42edb8b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  916): acquireWL(42f67058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=161028, Int=0
,D/PMS     (  916): releaseWL(42f67058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(42f476d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/PMS     (  916): releaseWL(42f476d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f4cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10027}
,V/AlarmManager(  916): sending alarm PendingIntent{42bb0580: PendingIntentRecord{42eb23b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173098, Int=0
,D/PMS     (  916): releaseWL(42f4cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  916): acquireWL(42f4f390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{42af0e78: PendingIntentRecord{42d8a010 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186357, Int=0
,D/PMS     (  916): releaseWL(42f4f390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f50e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=1 [51][1][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(42f1f450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42f50e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42f1f450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f24d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42f24d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f28ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(4300c1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42f28ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1227): Scheduling Phenotype for one-off execution 13190 seconds from now (1454416645976)
,D/GetConfigurationSnapshotOperation( 1227): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1227): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1227): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1227): [NET] getaddrinfo-, 1
,D/libc    ( 1227): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =130e +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1227): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): releaseWL(4300c1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f02f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42f02f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42f095a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1140): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1140): nl80211: survey data missing!
E/wpa_supplicant( 1140): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1140): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(42f095a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43034c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): releaseWL(43034c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(4303a938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=221027, Int=0
,D/PMS     (  916): releaseWL(4303a938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(4303cbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
,D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(4303cbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(43042360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): releaseWL(43042360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(43047f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=281028, Int=0
,D/PMS     (  916): releaseWL(43047f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(4304a1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4304a1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  916): updateBatteryInfo
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(4302cfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(4302cfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42ff1138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424b10f0: PendingIntentRecord{42c4ff28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=317029, Int=0
,D/PMS     (  916): acquireWL(42fe4630): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 916 1000 null
,I/ActivityManager(  916): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4310 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  916): sending alarm PendingIntent{42b71278: PendingIntentRecord{42d8ec28 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454416670078, Int=10800000
,D/PMS     (  916): releaseWL(42ff1138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(42fd9ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/PMS     (  916): releaseWL(42fe4630): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  916): releaseWL(42fd9ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.aurora (4310/10049)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,I/ActivityManager(  916): Killing 4070:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  916): killProcessQuiet, pid=4070
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 4070
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(42e31158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=341027, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42e31158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(42e2dc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42e2dc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=100
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
,D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  916): updateBatteryInfo
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(42e1a010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(42e1a010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(42e17b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=401027, Int=0
,D/PMS     (  916): releaseWL(42e17b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42e11560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42e11560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(42e0c6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/BatteryService(  916): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PMS     (  916): releaseWL(42e0c6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42caf4a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=461028, Int=0
,D/PMS     (  916): releaseWL(42caf4a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(42b30e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42b30e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(424e40f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(424e40f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(42db76c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=521028, Int=0
,D/PMS     (  916): releaseWL(42db76c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42bce5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(42bce5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
,I/HtcPowerSaver(  916): >> updateStatus
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(42b8b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42b8b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42e52918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=581027, Int=0
,D/PMS     (  916): releaseWL(42e52918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42cb9540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  916): releaseWL(42cb9540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=100
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42e21310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42e21310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1248): sku_id=99
D/ContactMessageStore( 1248): start background delete task...
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  916): acquireWL(42c69450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=641028, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42c69450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42d0e400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42d0e400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42d976c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42d976c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42e76080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=701027, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42e76080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42fdc958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42fdc958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
,D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42add160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42add160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42d3a038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=761027, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42d3a038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42d140e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/PMS     (  916): releaseWL(42d140e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42df5858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42df5858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42dc7688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=821028, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42dc7688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f81ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42f81ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(4302e928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(4302e928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42e43568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=881028, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42e43568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43002a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): releaseWL(43002a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42fac398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42fac398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42dc2568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=941027, Int=0
,D/PMS     (  916): releaseWL(42dc2568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42d54028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{424ddf08: PendingIntentRecord{42be9300 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786482, Int=0
,D/ConnectivityService(  916): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  916): sending alarm PendingIntent{42d0d7c8: PendingIntentRecord{42dc0330 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=948623, Int=0
,V/AlarmManager(  916): sending alarm PendingIntent{42ac99f0: PendingIntentRecord{42b301b8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454417390437, Int=900000
,D/PMS     (  916): acquireWL(42e7f5b8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): Done.
,D/ConnectivityService(  916): Setting timer for 720seconds
,D/PMS     (  916): releaseWL(42e7f5b8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  916): releaseWL(42d54028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4258): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4258): MY_DEBUG = false
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,D/PMS     (  916): acquireWL(430fced8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): releaseWL(430fced8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(43102828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024725
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024787
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024791
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024799
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360024802
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026221
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026234
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360028836
,D/PMS     (  916): releaseWL(43102828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  916): acquireWL(4308d8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(4308d8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(4300ee48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1001028, Int=0
,D/PMS     (  916): releaseWL(4300ee48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43006618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42da3dc8: PendingIntentRecord{42fa94a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454417467565, Int=0
,D/SmartSyncUtils( 4258): isEpsOn(), nState = 0
,D/PMS     (  916): releaseWL(43006618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42fd2ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4258 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4258): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4258): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4258): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4258): SettingOnTime = 1454479200000, randomSettingOnTime = 1454479085000
,D/SmartSyncScreenOnOffTimeReceiver( 4258): SettingOffTime = 1454464800000, randomSettingOffTime = 1454471244000
,D/SmartSyncScreenOnOffTimeReceiver( 4258): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4258): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4258): bNightModeTurnOffOnce = false
,D/PMS     (  916): releaseWL(42fd2ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  916): acquireWL(42fc5ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42fc5ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
,I/HtcPowerSaver(  916): >> updateStatus
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f6b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42f6b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f6a2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1061027, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42f6a2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f69dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(42f69dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f60000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/PMS     (  916): releaseWL(42f60000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f2cba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1121028, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42f2cba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f2c5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42f2c5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  916): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f2b058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/PMS     (  916): releaseWL(42f2b058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42f12b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1181027, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42f12b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f10408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/PMS     (  916): releaseWL(42f10408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42e2c590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/PMS     (  916): releaseWL(42e2c590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1623): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1623): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  916): acquireWL(42ae9d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42a26040: PendingIntentRecord{42a07d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1241028, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42ae9d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),D/PMS     (  916): acquireWL(42385620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
D/PMS     (  916): releaseWL(42385620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/cutils-trace( 4359): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4359): ====startRecUseTime====
D/htc.customization.log.level( 4359):  is 
W/CustomizationLogLevel( 4359): Level value is invalid, use default level 2
D/CustomizationManager( 4359):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4359): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4359): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4359): Parsing tag category name = system
I/CustomizationCIDLoader( 4359): Parsing tag category name = application
I/CustomizationCIDLoader( 4359): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4359): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4359): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4359): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4359): Parsing tag category name = Settings
D/CustomizationManager( 4359):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4359):  All configurations done spent 0.152 (s)
W/HtcNativeFlag( 4359): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4359): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4359): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4359): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  916): deletePackageAsUser: pkg=com.test.thalitest, pid=4359, uid=2000 user=0
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  916): Skipping PackageSetting{428b9078 com.example.hello/10397} due to missing metadata
W/PackageSettings(  916): Skipping PackageSetting{428bcce8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1623): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1623): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1623): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
D/PMS     (  916): acquireWL(42bb4640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  916): releaseWL(42bb4640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  916): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  916): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/VoicemailCleanupService( 1303): Cleaning up data for package: com.test.thalitest
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/IcingCorporaProvider( 2786): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  916): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4375 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mmsto"
F/PackageManager(  916): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/ErrorReport(  916): HtcErrorReportManager Begin---add error logs to dropbox
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  916): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  916): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1454417732222.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  916): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  916): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  916): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  916): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  916): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  916): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  916): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  916): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  916): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  916): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  916): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  916): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  916): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  916): 	... 18 more
E/SQLiteLog( 2786): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2786): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63cf8f78
W/dalvikvm( 2786): threadid=15: thread exiting with uncaught exception (group=0x41e22e30)
E/AndroidRuntime( 2786): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2786): Process: com.google.android.googlequicksearchbox:search, PID: 2786
E/AndroidRuntime( 2786): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2786): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2786): 	at cid.d(PG:186)
E/AndroidRuntime( 2786): 	at clo.g(PG:594)
E/AndroidRuntime( 2786): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2786): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2786): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2786): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2786): 	at clr.tL(PG:827)
E/AndroidRuntime( 2786): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2786): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2786): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2786): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2786): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  916): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2786): killProcess, pid=2786
D/Process ( 2786): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
I/InputMethodManagerService(  916): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/MediaRouterService(  916): Client com.google.android.googlequicksearchbox (pid 2786): Died!
D/WifiService(  916): Client connection lost with reason: 4
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 2786
I/ActivityManager(  916): Process com.google.android.googlequicksearchbox:search (pid 2786) has died.
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/SQLiteDatabase( 4375): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4375): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4375): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4375): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4375): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4375): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4375): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4375): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4375): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4375): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4375): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4375): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4375): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4375): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4375): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4375): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4375): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4375): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4375): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4375): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4375): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4375): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4375): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4375): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4375): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4375): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4375): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4375): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4375): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4375): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4375): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4375): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4375): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4375): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4375): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4375): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4375): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4375): threadid=11: thread exiting with uncaught exception (group=0x41e22e30)
E/ActivityManager(  916): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4375): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4375): Process: com.google.android.apps.docs, PID: 4375
E/AndroidRuntime( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4375): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4375): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4375): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4375): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4375): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
E/SQLiteDatabase( 4375): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4375): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4375): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4375): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4375): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4375): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4375): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4375): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4375): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4375): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4375): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4375): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4375): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4375): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4375): Opened ClientFlag.db in read-only mode
D/Process ( 4375): killProcess, pid=4375
I/ActivityManager(  916): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4392 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4375): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/JavaBinder(  916): !!! FAILED BINDER TRANSACTION !!!
D/Process (  916): killProcessQuiet, pid=3479
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  916): Killing 3479:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  916): Recipient 3479
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4375
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@422e5b98 +
I/Prism.WidgetManager( 1277): onLoadItems() +
I/ActivityManager(  916): Process com.google.android.apps.docs (pid 4375) has died.
W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4392): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4392): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4392): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4392): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4392): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4392): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4392): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4392): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4392): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4392): threadid=10: thread exiting with uncaught exception (group=0x41e22e30)
E/AndroidRuntime( 4392): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4392): Process: com.android.keychain, PID: 4392
E/AndroidRuntime( 4392): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4392): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4392): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4392): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4392): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4392): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4392): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4392): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  916): App crashed! Process: com.android.keychain
I/ActivityManager(  916): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4406 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  916): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4406): getInstance(Context context)
D/Process ( 4392): killProcess, pid=4392
D/Process ( 4392): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  916): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  916): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454417733199.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  916): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  916): 	... 4 more
I/ActivityManager(  916): Recipient 4392
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Process com.android.keychain (pid 4392) has died.
W/ActivityManager(  916): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10112ms
D/AppTag  ( 4406): getInstance(Context context)
D/AppTag  ( 4406): onCreate()
I/ActivityManager(  916): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4421 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}

```
