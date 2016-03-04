#### Test 614329799926788_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
--------- beginning of /dev/log/main
I/EASAppSvc( 3420): [ NA ]- onCreate()
,I/EASAppSvc( 3420): [ NA ]> onUpgrade: version = 63
D/ORMLib  ( 3230): put()
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3420/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3420/10064)
I/EASAppSvc( 3420): [ NA ]- onDestroy()
I/EASAppSvc( 3420): [ NA ]> uninitEASService
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3420/10064)
D/WifiService(  908): New client listening to asynchronous messages
I/EASRequestController( 3420): [ NA ]release
I/EASAppSvc( 3420): [ NA ]< uninitEASService
I/EASAppSvc( 3420): [ NA ]- onCreate()
I/EASAppSvc( 3420): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3420/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3420/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3420/10064)
D/ORMLib  ( 3230): put()
E/cutils-trace( 3444): Error opening trace file: No such file or directory (2)
I/EASAppSvc( 3420): [ NA ]- onDestroy()
I/EASAppSvc( 3420): [ NA ]> uninitEASService
I/EASRequestController( 3420): [ NA ]release
I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3465 uid=10068 gids={50068, 3003, 5012}
I/EASAppSvc( 3420): [ NA ]< uninitEASService
I/SensorManager(  908): mEventCount = 600
D/Process (  908): killProcessQuiet, pid=3245
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3245:com.htc.stock/u0a82 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3245
D/ORMLib  ( 3230): put()
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3444): ====startRecUseTime====
D/htc.customization.log.level( 3444):  is 
W/CustomizationLogLevel( 3444): Level value is invalid, use default level 2
D/CustomizationManager( 3444):  Read ACC file spent 0.074 (s)
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3444): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3444): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3444): Parsing tag category name = system
I/CustomizationCIDLoader( 3444): Parsing tag category name = application
I/CustomizationCIDLoader( 3444): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3444): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3444): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3444): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3444): Parsing tag category name = Settings
D/CustomizationManager( 3444):  Read CID file spent 0.125 (s)
D/CustomizationManager( 3444):  All configurations done spent 0.125 (s)
W/HtcNativeFlag( 3444): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3444): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3444): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3444): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3444
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3257
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3257:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/SoundPicker( 3398): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3398): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3398): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  908): Recipient 3257
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3398): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3398): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3398): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3398): MODE_GSM access default DB
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3398): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3398): MODE_GSM access default DB
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262,
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3356): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1965, uid=10029, userID:0,
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  908): Resuming delayed broadcast
D/DFPI.PIReciver( 3216): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3216): onHandleIntent
I/DFPI.ApkInstallService( 3216): Media Scan Finished Case 
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3216): check CID = HTC__032
I/DFPI.ApkInstallService( 3216): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead,
,I/dalvikvm-heap( 1248): Grow heap (frag case) to 13.271MB for 53840-byte allocation
I/Prism.ItemManager( 3269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1248): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Scheme: "mmsto"
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1317): Unsupported attribute readOnly
,V/AlarmManager(  908): sending alarm PendingIntent{42610b20: PendingIntentRecord{42633198 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457077292178, Int=0
,D/AutoSetting( 1292): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1292): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1292): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcModeClient( 1485): handler message = 4011
E/HtcModeClient( 1485): Check connection and retry 7 times.
I/ActivityManager(  908): Resuming delayed broadcast
I/SoundPicker( 3398): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3398): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3398): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3398): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3398): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3398): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3398): MODE_GSM access default DB
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 4)
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3398): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3398): MODE_GSM access default DB
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3398): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3398): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3398): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3398): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/MediaStoreImporter( 3356): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(425b08b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1485 10014 null
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  908): releaseWL(425b08b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1216): bind: false
D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3497 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/Process (  908): killProcessQuiet, pid=3176
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3176:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3176
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1292): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1292): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2572): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  908): Delaying start of: ServiceRecord{41ec4200 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,I/IcingCorporaProvider( 2572): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/Prism.ItemManager( 3269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3269): loadItems() com.htc.launcher.pageview.WidgetManager@41b34e00 +
,I/Prism.WidgetManager( 3269): onLoadItems() +
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b56cd0 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
,W/PackageManager(  908): Unable to load service info ResolveInfo{425d12a8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1248): onLoadItems() -
,I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b56cd0 -
,I/Prism.WidgetManager( 3269): onLoadItems() -
,I/Prism.ItemManager( 3269): loadItems() com.htc.launcher.pageview.WidgetManager@41b34e00 -
,D/PhoneApp( 1216): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1216): -- N1 =0
,D/PhoneApp( 1216): -- N2 =0
,D/PhoneApp( 1216): -- N3 =0
,V/AlarmManager(  908): sending alarm PendingIntent{42662900: PendingIntentRecord{425e7870 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457077293951, Int=0
,I/iu.UploadsManager( 1965): End new media; added: 0, uploading: 0, time: 114 ms
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,D/NotificationService(  908): notification sound not played, stream=5 volume=0 always=false
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41b161d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 2 9 1 10,
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41afdd78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 1 8 1 10
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3520 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(42339a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42339a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(426cfd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426d0948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426cfd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426d0948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4271ec60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4271ec60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(4276ecb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3520 10160 null
,D/PMS     (  908): acquireWL(4277e9c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3520 10160 null
,D/PMS     (  908): releaseWL(4276ecb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  908): acquireWL(427796a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3520 10160 null
,D/PMS     (  908): releaseWL(4277e9c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3520/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3520/10160)
,D/PMS     (  908): releaseWL(427796a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3547 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 3189:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3189
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  908): Recipient 3189
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3547, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 2879): id/is att sku: 99/false
,D/Finsky  ( 3547): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/SystemReader( 2879): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3547/10074)
,W/SystemReader( 2879): Cannot find support_harman, use default value instead
,W/SystemReader( 2879): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 2879): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 2879): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 2879): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 2879): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]support         :false
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/FingerprintManager( 2879): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 2879): isSupportVoWifi: null
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 2879): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3547/10074)
,D/Finsky  ( 3547): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,W/Settings( 3547): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3547): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3547, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 2879): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 2879): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 2879): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 2879): [supportHomeButton]support         :false
W/FingerprintManager( 2879): hasFingerprint() - sSensorCode = 0
D/Ads     ( 3547): Skipping gmscore version check
D/Finsky  ( 3547): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3547): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3547): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Settings:HtcVoWifiWidgetEnabler( 2879): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 2879): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3547): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 3547): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  908): killProcessQuiet, pid=3029
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3029:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
I/ActivityManager(  908): Recipient 3029
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  908): acquireWL(425df858): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425df858): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425b0738): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,W/IcingInternalCorpora( 1965): getNumBytesRead when not calculated.
,W/dalvikvm( 1965): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1965): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1965): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1965): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1965): cleanUpNonGplusAccounts done.
,D/Finsky  ( 3547): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3547): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  908): sending alarm PendingIntent{42588f98: PendingIntentRecord{426677f0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457077296335, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 3547): [NET] getaddrinfo-, 1
,D/libc    ( 3547): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3547): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Waited long enough for: ServiceRecord{425a3c50 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3594 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
,D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
,D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3547): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,W/GAV2    ( 3594): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 1965): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1965): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  908): releaseWL(425b0738): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3615 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  908): acquireWL(42767610): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42767610): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425aa618): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425aa618): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 3615): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3615): VFY: unable to resolve instance field 36
,W/dalvikvm( 3615): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3615): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 3615): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3615): MmsConfig.loadMmsSettings
,I/Gmail   ( 3594): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/MmsCustomizationProvider( 2456): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/Gmail   ( 3594): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/MmsCustomizationProvider( 2456): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3615): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3615): MmsConfig.loadFromDatabase
,I/Gmail   ( 3594): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3594): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/Babel   ( 3615): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3615): MmsConfig.loadFromResources
,E/Babel   ( 3615): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3615): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3615, uid=10111, userID:0
,W/Settings( 3615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3615, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3615, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3615, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3615, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3615, uid=10111, userID:0
D/PMS     (  908): acquireWL(4261f8b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3615 10111 null
,D/PMS     (  908): acquireWL(426041b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/PMS     (  908): releaseWL(426041b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,D/PMS     (  908): acquireWL(4233b210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  908): Done.
,I/ProviderInstaller( 3615): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): releaseWL(4233b210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425e4448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/PMS     (  908): releaseWL(425e4448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
I/ActivityManager(  908): Resuming delayed broadcast
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  908): acquireWL(42656bf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
D/PMS     (  908): releaseWL(42656bf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
,D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3547): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
D/PMS     (  908): releaseWL(4261f8b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Finsky  ( 3547): [1] DailyHygiene.access$600: Logging device features
,D/Process (  908): killProcessQuiet, pid=3297
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  908): Killing 3297:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,D/Finsky  ( 3547): [1] DailyHygiene.reschedule: Giving up. (failures=6)
V/AlarmManager(  908): sending alarm PendingIntent{425f2210: PendingIntentRecord{425c3da0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1457077297093, Int=0
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 3547): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3547): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/Process (  908): killProcessQuiet, pid=3319
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3319:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  908): acquireWL(41f09250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
I/ActivityManager(  908): Recipient 3319
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
D/PMS     (  908): releaseWL(41f09250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(424e3b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
D/PMS     (  908): releaseWL(424e3b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(41f2dae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
D/PMS     (  908): releaseWL(41f2dae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Recipient 3297
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
D/PMS     (  908): acquireWL(41cff8b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
D/PMS     (  908): releaseWL(41cff8b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4254f2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  908): acquireWL(41eb4350): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3230 10071 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): acquireWL(42438080): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3230 10071 null
,D/PMS     (  908): releaseWL(41eb4350): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  908): releaseWL(4254f2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/TodoTaskNotifyService( 3230): java.lang.NullPointerException
W/System.err( 3230): java.lang.NullPointerException
W/System.err( 3230): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3230): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3230): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3230): stopSelfResult true
,I/WSP     ( 1292): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1292): Weather sync is On
D/PMS     (  908): releaseWL(42438080): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WSP     ( 1292): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 09:41:37 CET 2016
,W/WSP     ( 1292): [Receiver] can't get active network info
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1292/10055)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1292/10055)
,V/WSP     ( 1292): [SyncService] no data connection, stop sync service
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3230): update TASK shortcut>
,W/MediaManager( 3336): [DualLensScanUtil]	mmpCursor count is 0
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 8 times.
,W/MediaManager( 3336): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3336): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(4277acb8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3356 10154 null
,I/ActivityManager(  908): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3356): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3356): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3356): Conditions not met for autocaching.
,I/MusicLeanback( 3356): Stop autocaching.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3356, uid=10154, userID:0
D/PMS     (  908): releaseWL(4277acb8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(4270b780): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3615 10111 null
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  908): releaseWL(4270b780): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1292): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1292): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2572): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  908): acquireWL(4270b5a0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4270b5a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42681918): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4267e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  908): n_update end
D/HtcPowerSaver(  908): updateBatteryInfo
,D/PMS     (  908): releaseWL(4267e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(42681918): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PMS     (  908): acquireWL(426133c8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426133c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426115a0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426115a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4260f450): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): releaseWL(4260f450): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426099f8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426099f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425fc5b8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425fc5b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425d7028): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425d7028): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425922c0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425922c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42554248): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42554248): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2572): UpdateCorporaTask done [took 237 ms] updated apps [took 237 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(4250d220): PARTIAL_WAKE_LOCK  AsyncService 0x1 3520 10160 null
,D/PMS     (  908): releaseWL(4250d220): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3695 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  908): acquireWL(42366040): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
,D/SyncApplication( 3695): Loading default preferences
,W/Resources( 3695): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3695): Overriding preferences with custom values
,D/SyncApplication( 3695): Updating preferences succeeded
,E/SyncApplication( 3695): Application created.
D/VolumeInfo( 3695): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3695): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3695): Found 0 mount point(s)
,V/VolumeInfo( 3695): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3695): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3695): getNewCalendarAuthority()...
,D/VolumeInfo( 3695): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3695): Can not create volume ID for unmounted volume null
D/SyncApplication( 3695): enableAppOperation()+
,D/SyncApplication( 3695): enableAppOperation()-
,D/HTCUtilities( 3695): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3695, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3695, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3695): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3695): isNeorSinged() return false
,D/CDMountReceiver( 3695): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3695): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
D/CDMountReceiver( 3695): enable CD Auto-mount: true
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
I/SensorManager(  908): mEventCount = 750
I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
D/HTCUtilities( 3695): enable auto-mount
D/HTCUtilities( 3695): enable auto-mount
I/ActivityManager(  908): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  908): Resuming delayed broadcast
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41ea8c08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 2 10 3 11
I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41eb0438 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 1 7 3 16
,W/MediaManager( 3336): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3201
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3201:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3201
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42545910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): releaseWL(42545910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(424bf438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  908): acquireWL(42557800): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3547 10074 null
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/Finsky  ( 3547): [376] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  908): releaseWL(424bf438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
,D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(42557800): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(4234e0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3547): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3547/10074)
,D/PMS     (  908): acquireWL(42693f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): releaseWL(42693f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1965): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1965): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1965): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(42366040): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4263cdb0 u0 com.htc.musicenhancer/.EnhancerService}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/CheckinService( 1965): Done disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/GAV2    ( 3594): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3615): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1485): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1485): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3727 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3727): onCreate
D/ProviderChangeReceiver( 3727): ---------------------------------------------------
,D/ProviderChangeReceiver( 3727): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3727): start to updateAlertNotification!
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3741 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=3269
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3269:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/AlertService( 3727): No fired or scheduled alerts
,D/HtcAlertUtils( 3727): -- cancelReminderNotification --
,D/HtcAlertUtils( 3727): broadcastExistReminder!
,I/ActivityManager(  908): Recipient 3269
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 3741): [3741/3741] onCreate()
W/ContextImpl( 3741): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 9 times.
,D/Process (  908): killProcessQuiet, pid=3420
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3420:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3420
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,I/SensorManager(  908): mEventCount = 900
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 10 times.
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): acquireWL(42303548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{421d14e0: PendingIntentRecord{4234ea00 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=83498, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{42301ee0: PendingIntentRecord{42525f00 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457077311538, Int=0
D/PMS     (  908): releaseWL(42303548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3547): [365] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3547): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SensorManager(  908): mEventCount = 1050
,D/AutoSetting( 1292): service - handleMessage() stop self
,D/AutoSetting( 1292): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3465
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 3465:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/AutoSetting( 1292): service - handleMessage() quit looper
,I/ActivityManager(  908): Recipient 3465
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times.
,D/PMS     (  908): acquireWL(4263e198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=94329, Int=0
,D/PMS     (  908): releaseWL(4263e198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1107): now=1457077320060 next=59940
,I/SensorManager(  908): mEventCount = 1200
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1485): Don't start project servcice
,D/HtcModeClient( 1485): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1485): connectState: CONNECTION_READY = false
D/SilentMusic( 1485): call stop
,D/HtcModeClient( 1485): close connection
,W/HtcModeClient( 1485): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1485): read the terminate packet, so break
,D/Process (  908): killProcessQuiet, pid=3216
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3216:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3216
,D/PMS     (  908): acquireWL(426004c0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426004c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425d3fc8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425d3fc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42776bd0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42776bd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42642720): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42642720): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42599610): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42599610): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3756 uid=10078 gids={50078}
,D/PMS     (  908): acquireWL(42676e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10078}
,V/AlarmManager(  908): sending alarm PendingIntent{423fa568: PendingIntentRecord{4237f610 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457077323526, Int=60000
,D/PMS     (  908): releaseWL(42676e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3756): SMSBackupAgentService started
,D/SMSBackup( 3756): Checking restore status
,D/SMSBackup( 3756): Restore complete
,D/SMSBackup( 3756): cancelCheckAlarm
,D/SMSBackup( 3756): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/Process (  908): killProcessQuiet, pid=3398
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3398:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3398
,I/SensorManager(  908): mEventCount = 1350
,V/LightsService(  908): setLight #0: color=#3d
,V/LightsService(  908): setLight #0: color=#37
,V/LightsService(  908): setLight #0: color=#30
,V/LightsService(  908): setLight #0: color=#29
,V/LightsService(  908): setLight #0: color=#23
,V/LightsService(  908): setLight #0: color=#1c
,V/LightsService(  908): setLight #0: color=#15
,V/LightsService(  908): setLight #0: color=#14
,I/SensorManager(  908): mEventCount = 1500
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4215f030
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4215f030, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dbf388
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42557838
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  908): mWirelessDisplayManager is null
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 344ms
,W/PnPMgr  (  355): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4271efa0)
D/NfcService( 1228): ScreenObserver: OFF
,D/NfcService( 1228): applyRouting - 0
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=1248
D/PMN     (  908): wakingUp
,D/NfcService( 1228): applyRouting -2
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/PMS     (  908): acquireWL(426f8fe8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  908): acquireWL(426f9968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(426f9968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  908): No lock screen! windowToken=null
D/PMS     (  908): releaseWL(426f8fe8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  908): onScreenOn
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/MtpService( 2142): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2142): [MTP][onReceive]-
,D/NfcService( 1228): applyRouting - 0
I/ClockThread( 1107): stop update clock
,D/AutoSetting( 1292): receiver - intent: android.intent.action.USER_PRESENT
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/NfcService( 1228): applyRouting -2
D/TetherSettings( 2879): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2879): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2879): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2879): Cust_ConnectToPC   : spcsc>false
D/        ( 2879): Cust_ConnectToPC   : IPT>true
D/        ( 2879): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2879): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  908): acquireWL(427865d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
,D/PMS     (  908): releaseWL(427865d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
E/SmartNS_Utility( 2879): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2879): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2879): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1292): service - onCreate()
,I/PSReceiver( 2879): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1292): service - AddressCache: using context: com.htc.Weather
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
,D/AutoSetting( 1292): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/SmartNS_PSService( 2879): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  908):    returned false
W/Settings( 2879): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2879):  defaultType:0
D/LocationManagerService(  908): request 4230bf20 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
,V/SRS_Proc(  369): ParamSet string: screen_state=on
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  908): updateScreenOn: false
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3783 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(4270b730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4270b730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4270b690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4270b690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dbf388
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dbf388, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42557838
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(426f8fe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3783 1000 null
D/PMS     (  908): acquireWL(426f18f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,D/PMS     (  908): releaseWL(426f8fe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1248): [onPause]
,I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c08e40
I/SocialFeedProvider( 1248): +onPause
,I/SocialFeedProvider( 1248): -onPause
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=22063 mDataStallAlarmIntent=null
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
I/AlarmManager(  908): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  908):    returned false
,V/SRS_Proc(  369): ParamSet string: screen_state=off
D/PMS     (  908): acquireWL(42682df0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/PMS     (  908): releaseWL(42682df0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  908): releaseWL(426f18f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  908): updateScreenOn: false
,D/SmartSyncUtils( 3783): getMobilePolicyEnabled, result = true
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3783): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1216): start background delete task...
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  908): New client listening to asynchronous messages
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42557838
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42557838, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42557838, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42557838
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cea6a8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cea6a8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] getTotalRam: 1873 Mb
D/PMS     (  908): acquireWL(41fa0e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(41fa0e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(41f50610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41f50610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1292): service - mHandler: cancel location update
,D/AutoSetting( 1292): service -           changes count: 0
,D/Process (  908): killProcessQuiet, pid=3379
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3379:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3379
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4266d7f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  908): acquireWL(41e33510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(41e33510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4275e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4236d4e0: PendingIntentRecord{41abb938 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=131494, Int=0
,D/PMS     (  908): acquireWL(4275f4f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,V/AlarmManager(  908): sending alarm PendingIntent{41f4ad98: PendingIntentRecord{423388c8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143529, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{421d14e0: PendingIntentRecord{4234ea00 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145883, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{41abbde8: PendingIntentRecord{4260b008 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=145905, Int=0
,D/PMS     (  908): releaseWL(4275f4f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1292): service - handleMessage() stop self
,D/AutoSetting( 1292): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3497
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 3497:com.htc.updater/u0a85 (adj 15): empty #17
D/AutoSetting( 1292): service - handleMessage() quit looper
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(42763760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42763760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(4275e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3497
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(425bb968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425bb968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(423f8b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  908): releaseWL(423f8b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(4246dcf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4246dcf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4255ae00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4240e718: PendingIntentRecord{41abb938 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191207, Int=0
,D/PMS     (  908): acquireWL(4257e480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,V/AlarmManager(  908): sending alarm PendingIntent{421d14e0: PendingIntentRecord{4234ea00 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206145, Int=0
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  908): releaseWL(4255ae00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(424642e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4257e480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(424642e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425752f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): releaseWL(425752f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4236a330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): acquireWL(425e6688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1457077432149 tag=VacuumService
D/PMS     (  908): releaseWL(4236a330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425e6688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42752ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): releaseWL(42752ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42769270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025942
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026013
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026017
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026019
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026024
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028174
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028185
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030769
,D/PMS     (  908): releaseWL(42769270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425ec6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425ec6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(425907d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425907d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4258c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4258c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(4265fa98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4265fa98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(42524a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42524a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4277adf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4277adf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4265cca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=334329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4265cca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(42621098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42621098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(426c7ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426c7ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(42777ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394329, Int=0
,D/PMS     (  908): releaseWL(42777ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42771fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42771fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4268daa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4268daa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4256b710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=454330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4256b710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(425e8940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(425e8940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  908): batLight: plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c80000
D/DotMatrix( 1529): [EventService] reorderNotification, total:1
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/qdlights(  908): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,D/TetherSettings( 2879): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2879): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2879): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2879): Cust_ConnectToPC   : spcsc>false
D/        ( 2879): Cust_ConnectToPC   : IPT>true
D/        ( 2879): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 2879): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 2879): Index of the first 1 = -1
I/HtcPowerSaver(  908): << updateStatus
W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 2879): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2879): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2879): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2879): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 2879): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42550d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42550d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(42605b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=514329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42605b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4264f038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4264f038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1107): closing low battery warning: level=98
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42711f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42711f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426c9068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=574329, Int=0
,D/PMS     (  908): releaseWL(426c9068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426f7180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426f7180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1216): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1216): sku_id=99
,D/ContactMessageStore( 1216): start background delete task...
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,D/PMS     (  908): acquireWL(426f8a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=634329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426f8a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  908): killProcessQuiet, pid=2456
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  908): Killing 2456:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2456
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
D/libc    ( 3547): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-,
,D/PMS     (  908): acquireWL(426e4b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(426e4b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(426ea918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=694330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426ea918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426ecb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(426ecb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42695d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42695d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42697618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=754329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42697618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42699898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42699898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4269ee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4269ee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426a0730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=814329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426a0730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426a2f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(426a2f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(426a8540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426a8540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426a9e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=874330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426a9e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426ac0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426ac0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderNotification, total:0
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 2879): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2879): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2879): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2879): Cust_ConnectToPC   : spcsc>false
D/        ( 2879): Cust_ConnectToPC   : IPT>true
,D/        ( 2879): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 2879): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 2879): Index of the first 1 = -1
W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 2879): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2879): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2879): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2879): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(426b4ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426b4ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426b63c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=934330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426b63c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3547): [NET] getaddrinfo-,err=8
D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
D/libc    ( 3547): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-,
,D/PMS     (  908): acquireWL(426bed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426bed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426c0648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994330, Int=0
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426c0648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(426c3680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d3a4a8: PendingIntentRecord{42423d28 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=791212, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3845 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{425efe48: PendingIntentRecord{42464020 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457077438828, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{42437c68: PendingIntentRecord{4246cf58 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457078159167, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{41e2c700: PendingIntentRecord{41f2f200 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457078241523, Int=0
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3783): call getInstance()
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3783): MY_DEBUG = false
D/PMS     (  908): acquireWL(427334d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3783 1000 null
D/PMS     (  908): releaseWL(426c3680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3783): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3783): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3783): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 3783): SettingOnTime = 1457157600000, randomSettingOnTime = 1457157445000
,D/SmartSyncScreenOnOffTimeReceiver( 3783): SettingOffTime = 1457143200000, randomSettingOffTime = 1457146084000
D/SmartSyncScreenOnOffTimeReceiver( 3783): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3783): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3783): bNightModeTurnOffOnce = false
W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(427334d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (3845/10049)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=3230
,I/ActivityManager(  908): Killing 3230:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3230
,D/PMS     (  908): acquireWL(428cd9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428cd9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(428cf2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054329, Int=0
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428cf2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428d1568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428d1568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(428d2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1114329, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428d2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428d50c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428d50c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(428d69c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1174330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428d69c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428d8c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428d8c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  908): acquireWL(428da548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42011570: PendingIntentRecord{420005e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1234330, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428da548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3547): [NET] getaddrinfo-,err=8
,D/libc    ( 3547): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3547): [NET] getaddrinfo-, 1
D/libc    ( 3547): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET] get_iface_protocol fail: 
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  362): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 3547): [NET] getaddrinfo_proxy-,
,D/PMS     (  908): acquireWL(42854aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42854aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3863): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3863): ====startRecUseTime====
D/htc.customization.log.level( 3863):  is 
W/CustomizationLogLevel( 3863): Level value is invalid, use default level 2
D/CustomizationManager( 3863):  Read ACC file spent 0.122 (s)
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3863): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3863): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3863): Parsing tag category name = system
I/CustomizationCIDLoader( 3863): Parsing tag category name = application
I/CustomizationCIDLoader( 3863): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3863): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3863): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3863): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3863): Parsing tag category name = Settings
D/CustomizationManager( 3863):  Read CID file spent 0.179 (s)
D/CustomizationManager( 3863):  All configurations done spent 0.180 (s)
W/HtcNativeFlag( 3863): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3863): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3863): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3863): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=3863, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  908): Skipping PackageSetting{4211cfd8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  908): Skipping PackageSetting{42125118 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  908): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  908): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(42876630): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42876630): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  908):   Scheme: "mms"
D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1275): Cleaning up data for package: com.test.thalitest
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/[PluginManager]RegisterService( 1292): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1292): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/IcingCorporaProvider( 2572): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3880 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2572): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2572): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x649c3b58
W/dalvikvm( 2572): threadid=14: thread exiting with uncaught exception (group=0x41694e30)
E/AndroidRuntime( 2572): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2572): Process: com.google.android.googlequicksearchbox:search, PID: 2572
E/AndroidRuntime( 2572): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2572): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2572): 	at cid.d(PG:186)
E/AndroidRuntime( 2572): 	at clo.g(PG:594)
E/AndroidRuntime( 2572): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2572): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2572): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2572): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2572): 	at clr.tL(PG:827)
E/AndroidRuntime( 2572): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2572): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2572): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2572): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2572): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2572): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2572): killProcess, pid=2572
D/Process ( 2572): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Recipient 2572
I/ActivityManager(  908): Process com.google.android.googlequicksearchbox:search (pid 2572) has died.
D/MediaRouterService(  908): Client com.google.android.googlequicksearchbox (pid 2572): Died!
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 3880): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3880): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3880): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3880): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3880): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3880): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3880): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3880): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3880): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3880): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3880): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3880): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3880): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3880): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3880): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3880): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3880): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3880): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3880): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3880): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3880): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3880): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3880): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3880): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3880): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3880): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3880): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3880): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3880): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3880): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3880): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3880): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3880): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3880): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3880): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3880): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3880): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3880): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3880): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3880): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3880): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3880): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3880): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3880): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3880): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3880): threadid=11: thread exiting with uncaught exception (group=0x41694e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 3880): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3880): Process: com.google.android.apps.docs, PID: 3880
E/AndroidRuntime( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3880): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3880): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3880): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3880): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3880): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 3880): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3880): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3880): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3880): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3880): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3880): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3880): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3880): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3880): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3880): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3880): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3880): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3880): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3880): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3880): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3880): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3880): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3880): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3880): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3880): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3880): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3880): Opened ClientFlag.db in read-only mode
D/Process ( 3880): killProcess, pid=3880
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3897 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 3880): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Recipient 3880
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  908): killProcessQuiet, pid=3356
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3356:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 3880) has died.
W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3910 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3356
D/MediaRouterService(  908): Client com.google.android.music (pid 3356): Died!
E/SQLiteDatabase( 3897): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3897): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3897): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 3897): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 3897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3897): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3897): threadid=10: thread exiting with uncaught exception (group=0x41694e30)
E/AndroidRuntime( 3897): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3897): Process: com.android.keychain, PID: 3897
E/AndroidRuntime( 3897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3897): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3897): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 3897): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 3897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3897): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 3910): getInstance(Context context)
D/AppTag  ( 3910): getInstance(Context context)
D/Process ( 3897): killProcess, pid=3897
D/Process ( 3897): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 3910): onCreate()

```
