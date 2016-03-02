#### Test 613623666a5dbc7_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Resuming delayed broadcast
--------- beginning of /dev/log/main
D/DFPI.PIReciver( 3296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3296): onHandleIntent
I/DFPI.ApkInstallService( 3296): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3296): check CID = HTC__032
I/DFPI.ApkInstallService( 3296): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/cutils-trace( 3541): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3541): ====startRecUseTime====
D/htc.customization.log.level( 3541):  is 
W/CustomizationLogLevel( 3541): Level value is invalid, use default level 2
D/CustomizationManager( 3541):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3541): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3541): Parsing tag category name = system
I/CustomizationCIDLoader( 3541): Parsing tag category name = application
I/CustomizationCIDLoader( 3541): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3541): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3541): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3541): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3541): Parsing tag category name = Settings
D/CustomizationManager( 3541):  Read CID file spent 0.107 (s)
D/CustomizationManager( 3541):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 3541): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3541): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3541): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3541): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3541
,I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=3337
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3337:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/SoundPicker( 3520): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3520): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3520): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3520): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3520): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3520): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/ActivityManager(  905): Recipient 3337
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1976, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1976, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1976, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1976, uid=10029, userID:0
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1224): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/dalvikvm-heap( 1247): Grow heap (frag case) to 13.164MB for 53840-byte allocation
I/Prism.ItemManager( 3349): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3349): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,I/ActivityManager(  905): Resuming delayed broadcast
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3557 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3296): onHandleIntent
I/DFPI.ApkInstallService( 3296): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3296): check CID = HTC__032
,I/DFPI.ApkInstallService( 3296): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3557): [ NA ]- onCreate()
,I/EASAppSvc( 3557): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3310): put()
,D/AutoSetting( 1295): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1295): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1295): service - requestNLP() NetworkLocationProvider not enabled
,I/EASAppSvc( 3557): [ NA ]- onDestroy()
,I/EASAppSvc( 3557): [ NA ]> uninitEASService
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.android.mail (3557/10064)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.htc.android.mail (3557/10064)
D/ConnectivityService(  905): getNetworkInfo networkType=55 called by com.htc.android.mail (3557/10064)
,I/EASRequestController( 3557): [ NA ]release
,I/EASAppSvc( 3557): [ NA ]< uninitEASService
,I/EASAppSvc( 3557): [ NA ]- onCreate()
,I/EASAppSvc( 3557): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  905): getNetworkInfo networkType=55 called by com.htc.android.mail (3557/10064)
,D/ORMLib  ( 3310): put()
,I/EASAppSvc( 3557): [ NA ]- onDestroy()
,I/EASAppSvc( 3557): [ NA ]> uninitEASService
,I/EASRequestController( 3557): [ NA ]release
I/ActivityManager(  905): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3589 uid=10068 gids={50068, 3003, 5012}
,I/EASAppSvc( 3557): [ NA ]< uninitEASService
,I/SocialFeedProvider( 1247): +disConnect socialManager
,I/SocialFeedProvider( 1247): disconnect socialManager
,I/SocialFeedProvider( 1247): -disConnect socialManager
,D/Process (  905): killProcessQuiet, pid=3237
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3237:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,W/PackageManager(  905): Unable to load service info ResolveInfo{4282a3d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  905): Recipient 3237
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3310): put()
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41b31cd0 +
I/Prism.WidgetManager( 1247): onLoadItems() +
I/Prism.ItemManager( 3349): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3349): loadItems() com.htc.launcher.pageview.WidgetManager@41b11c08 +
,I/Prism.WidgetManager( 3349): onLoadItems() +
I/ActivityManager(  905): Resuming delayed broadcast
,I/SoundPicker( 3520): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3520): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3520): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3520): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3520): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3520): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3478): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41b31cd0 -
,I/Prism.WidgetManager( 3349): onLoadItems() -
,I/Prism.ItemManager( 3349): loadItems() com.htc.launcher.pageview.WidgetManager@41b11c08 -
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1196): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/AlarmManager(  905): sending alarm PendingIntent{4265cc30: PendingIntentRecord{4264ec20 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1456906093795, Int=0
,D/PMS     (  905): acquireWL(42696b08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42696b08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4265df28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4265df28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(42667bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42667bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425f82d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425f82d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1213): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1213): -- N1 =0
,D/PhoneApp( 1213): -- N2 =0
,D/PhoneApp( 1213): -- N3 =0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 3254:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3254
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PMS     (  905): acquireWL(427b9d90): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1457 10014 null
I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3254
,D/PMS     (  905): releaseWL(427b9d90): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/DFPI.PIReciver( 3296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  905): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3296): onHandleIntent
,I/DFPI.ApkInstallService( 3296): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3296): check CID = HTC__032
,I/DFPI.ApkInstallService( 3296): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 6 times.
,V/AlarmManager(  905): sending alarm PendingIntent{4235b348: PendingIntentRecord{424e4e48 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1456906094968, Int=0
,I/SocialManager[SocialBiLogHelper]( 3349): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3349): last commit ulog time 1456811704648
,I/SocialManager[SocialBiLogHelper]( 3349): do commit ulog
,I/ActivityManager(  905): Delaying start of: ServiceRecord{4264e278 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,I/ActivityManager(  905): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=3621 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ImageRamCache( 3621): create image Cache, size: 31457280.
,I/ImageRamCache( 3621): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3621): create image Cache, size: 12582912.
,I/FeedSettings( 3621): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3621): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3621): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3621): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3621): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3621): loadGridSize() with Alternative
,V/SocialManagerService( 1295): getDataSources
,I/SocialManagerService( 1295): plugin added: com.facebook.auth.login
I/SocialManagerService( 1295): plugin added: com.twitter.android.auth.login
,I/SocialManagerService( 1295): plugin added: com.htc.linkedin
I/SocialManagerService( 1295): plugin added: com.htc.venuesrecommend
,I/SocialManagerService( 1295): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1295): plugin added: com.htc.drive.activator
,I/SocialManagerService( 1295): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1295): plugin added: com.htc.opensense.htcnews
,I/SocialManagerService( 1295): plugin added: com.google
,I/SocialManagerService( 1295): device total memory: 1873M
,I/SocialManagerService( 1295): groupAccounts
,I/ActivityManager(  905): Resuming delayed broadcast
,I/SoundPicker( 3520): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3520): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3520): SoundPickerReceiver [onReceive] startService
E/SocialManagerService( 1295): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1295): error when get process name! process name is null!
E/SocialManagerService( 1295): skip binding the plugin without process namecom.htc.drive.activator
I/SoundPicker( 3520): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3520): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3520): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3520): MODE_GSM access default DB
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SocialManagerService( 1295): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1295): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1295): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1295): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1295): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1295): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1295): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1295): add com.google to pending queue!
I/SocialManagerService( 1295): consume pending plugin session
I/SocialManagerService( 1295): add com.facebook.auth.login to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.facebook.auth.login
I/SocialManagerService( 1295): com.facebook.auth.login connecting, adding msg, h,as message?true
I/SocialManagerService( 1295): add com.htc.linkedin to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.htc.linkedin
I/SocialManagerService( 1295): com.htc.linkedin connecting, adding msg, has message?true
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  905): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=3638 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
I/SocialManagerService( 1295): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.twitter.android.auth.login
I/SocialManagerService( 1295): com.twitter.android.auth.login connecting, adding msg, has message?true
I/SocialManagerService( 1295): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1295): com.htc.venuesrecommend connecting, adding msg, has message?true
I/SocialManagerService( 1295): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1295): add com.htc.socialnetwork.rss.octopus to process map!
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
V/SocialManagerService( 1295): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1295): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
D/LocationSocialPlugin( 3349): onBind
I/SocialManagerService( 1295): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1295): com.htc.opensense.htcnews connecting, adding msg, has message?true
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SocialManagerService( 1295): skip to add com.google, plugin per process full!
I/SocialManagerService( 1295): com.htc.venuesrecommend connected, removed msg, has message?false
I/SocialManagerService( 1295): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
D/StreamPluginService( 3349): getDataSources start
D/SocialManagerService( 1295): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
D/LocationIdentityProvider( 3349): is_approved false
D/LocationSocialPlugin( 3349): account null
I/SocialManagerService( 1295): remove account type: com.htc.socialnetwork.rss.octopus from process map!
D/LocationSocialPlugin( 3349): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
V/SocialManagerService( 1295): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1295): consume pending plugin session
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SocialManagerService( 1295): skip to add com.google, plugin per process full!
I/SocialManagerService( 1295): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1295): handling plugin: com.htc.venuesrecommend set result in bg
I/SocialManagerService( 1295): remove account type: com.htc.venuesrecommend from process map!
V/SocialManagerService( 1295): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1295): consume pending plugin session
I/SocialManagerService( 1295): skip to add com.google, plugin per process full!
I/SocialManagerService( 1295): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path =, /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SocialManagerService( 1295): com.htc.opensense.htcnews connected, removed msg, has message?false
D/SocialManagerService( 1295): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1295): remove account type: com.htc.opensense.htcnews from process map!
I/SocialManagerService( 1295): remove process: com.htc.sense.news from process map!
V/SocialManagerService( 1295): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1295): consume pending plugin session
I/SocialManagerService( 1295): skip to add com.google, plugin per process full!
I/SocialManagerService( 1295): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3520): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3520): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3520): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3520): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
D/LinkedIn( 3638): contentprovider oncreate getReadableDatabase
I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/SocialManagerService( 1295): com.facebook.auth.login connected, removed msg, has message?false
D/LinkedIn( 3638): service onBind
I/SocialManagerService( 1295): com.htc.linkedin connected, removed msg, has message?false
D/g       ( 3638): get htcisdemo: false
,D/FacebookSocialPluginService( 3638): get htcisdemo: false
D/Facebook_Session( 3638): MSG_QUERY_ACCOUNT
D/Facebook_Session( 3638): queryAccount
D/Facebook_Session( 3638): queryAccount enter lock
I/SocialManagerService( 1295): com.twitter.android.auth.login connected, removed msg, has message?false
D/Facebook_Session( 3638): Facebook Session created
D/Facebook_Session( 3638): queryAccount
D/SocialManagerService( 1295): handling plugin: com.htc.linkedin set result in bg
I/SocialManagerService( 1295): remove account type: com.htc.linkedin from process map!
V/SocialManagerService( 1295): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1295): consume pending plugin session
I/SocialManagerService( 1295): add com.google to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.google
I/SocialManagerService( 1295): com.google connecting, adding msg, has message?true
I/SocialManagerService( 1295): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/Facebook_Session( 3638): Query Facebook account complete
D/Facebook_Session( 3638): queryAccount enter lock
D/Facebook_Session( 3638): Query Facebook account complete
D/GooglePlusSocialPluginService( 3638): Bind
D/SocialManagerService( 1295): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1295): remove account type: com.twitter.android.auth.login from process map!
I/SocialManagerService( 1295): com.google connected, removed msg, has message?false
V/SocialManagerService( 1295): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1295): consume pending plugin session
I/SocialManagerService( 1295): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1295): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1295): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
I/GooglePlusSocialPluginService( 3638): getDataSources start
D/SocialManagerService( 1295): handling plugin: com.facebook.auth.login set result in bg
I/SocialManagerService( 1295): remove account type: com.facebook.auth.login from process map!
V/SocialManagerService( 1295): on plugin completed! plugin session type com.facebook.auth.login
I/SocialManagerService( 1295): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
D/SocialManagerService( 1295): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
I/GooglePlusSocialPluginService( 3638): getDataSources end
,I/MediaStoreImporter( 3478): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SocialManagerService( 1295): remove account type: com.htc.sense.socialnetwork.instagram from process map!
,D/TelephonyReceiver( 1213): bind: false
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
V/SocialManagerService( 1295): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
,D/SocialManagerService( 1295): handling plugin: com.google set result in bg
I/SocialManagerService( 1295): remove account type: com.google from process map!
,I/SocialManagerService( 1295): remove process: com.htc.sense.socialplugins from process map!
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3665 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/GooglePlusSocialPluginService( 3638): Unbind
V/SocialManagerService( 1295): on plugin completed! plugin session type com.google
I/SocialManagerService( 1295): onSessionCompleted
,D/Process (  905): killProcessQuiet, pid=3365
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3365:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SocialManager[SocialBiLogHelper]( 3349): social manager disconnect
,I/ActivityManager(  905): Recipient 3365
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3380
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3380:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3380
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1196): callingUid 10029, callindPid: 1196
,E/MDM     ( 1196): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1976): Restart initialization of location
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Delaying start of: ServiceRecord{42767ab0 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,W/GCoreFlp( 1196): No location to return for getLastLocation()
,W/FusedLocationProvider( 1196): location=null
D/PMS     (  905): acquireWL(426ada38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(426ada38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,I/ActivityManager(  905): Delaying start of: ServiceRecord{428159e8 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,V/AlarmManager(  905): sending alarm PendingIntent{42527460: PendingIntentRecord{426b7d78 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456906095569, Int=0
,D/DotMatrix( 1517): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  905): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1106): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41d521b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.htc.updater 1 8 0 10
,I/RemoteViews( 1106): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41e55e20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
I/RemoteViews.Performance( 1106): com.htc.updater 2 6 1 10
,I/iu.UploadsManager( 1976): End new media; added: 0, uploading: 0, time: 72 ms
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3405
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3405:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/AuthorizationBluetoothService( 2355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2355): Proximity feature is not enabled.
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Recipient 3405
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1295): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1295): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/IcingCorporaProvider( 2664): UpdateCorporaTask done [took 37 ms] updated apps [took 36 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3692 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42552460): PARTIAL_WAKE_LOCK  AsyncService 0x1 3692 10160 null
,D/PMS     (  905): releaseWL(42552460): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4254fae8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3692 10160 null
,I/ActivityManager(  905): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  905): acquireWL(4254d218): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3692 10160 null
,D/PMS     (  905): releaseWL(4254fae8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3692/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3692/10160)
,D/PMS     (  905): releaseWL(4254d218): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2751
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3719 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 2751:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2751
,D/Settings:HtcWirelessFeatureFlags( 3425): id/is att sku: 99/false
,W/SystemReader( 3425): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3425): Cannot find support_harman, use default value instead
,W/SystemReader( 3425): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3425): no such activity!
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3425): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3425): updateDevelopment, bPrefShow = true
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3719, uid=10074, userID:0
,E/Settings:HtcUmcWidgetEnabler( 3425): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]support         :false
,D/Finsky  ( 3719): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/FingerprintManager( 3425): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3719/10074)
,E/Settings:HtcVoWifiWidgetEnabler( 3425): isSupportVoWifi: null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3425): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3719/10074)
,D/Finsky  ( 3719): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,W/Settings( 3719): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3719): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3425): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3425): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3425): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3425): [supportHomeButton]support         :false
,W/FingerprintManager( 3425): hasFingerprint() - sSensorCode = 0
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,E/Settings:HtcVoWifiWidgetEnabler( 3425): isSupportVoWifi: null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3425): Failed to find provider info for com.htc.vowifi
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3719, uid=10074, userID:0
,D/Ads     ( 3719): Skipping gmscore version check
,D/Finsky  ( 3719): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3719): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3719): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 3719): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  905): killProcessQuiet, pid=3442
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 3442:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3442
,D/PackageBroadcastService( 1976): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3757 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(42607948): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42607948): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425c1ac0): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4264e518 u0 com.google.android.gms/.gcm.GcmService}
,W/GAV2    ( 3757): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 1976): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1976): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1976): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1976): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1976): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1976): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1976): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1976, uid=10029, userID:0
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3780 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  905): killProcessQuiet, pid=3281
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/PeopleDatabaseHelper( 1976): cleanUpNonGplusAccounts done.
I/ActivityManager(  905): Killing 3281:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3281
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 3757): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3757): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Babel   ( 3780): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3780): MmsConfig.loadMmsSettings
,I/SensorManager(  905): mEventCount = 450
,W/dalvikvm( 3780): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3780): VFY: unable to resolve instance field 36
,W/dalvikvm( 3780): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/Gmail   ( 3757): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3757): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  905): acquireWL(42551470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42551470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/JNIHelp ( 3780): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2546): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
D/MmsCustomizationProvider( 2546): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3780): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3780): MmsConfig.loadFromDatabase
,E/Babel   ( 3780): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3780): MmsConfig.loadFromResources
,E/Babel   ( 3780): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3780): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3780, uid=10111, userID:0
,W/Settings( 3780): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3780, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3780, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3780, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3780, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3780, uid=10111, userID:0
,D/PMS     (  905): acquireWL(425f0060): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3780 10111 null
I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425b3838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,D/PMS     (  905): releaseWL(425b3838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42511a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(42511a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 3780): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1976/10029)
W/GCoreFlp( 1196): No location to return for getLastLocation()
,W/FusedLocationProvider( 1196): location=null
D/PMS     (  905): acquireWL(425e2c80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425e2c80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/GCM     ( 2355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,D/PMS     (  905): acquireWL(42819ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(42819ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425f0060): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  905): acquireWL(42642e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,D/Process (  905): killProcessQuiet, pid=3310
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3310:com.htc.task/u0a71 (adj 15): empty #17
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(42642e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425f4418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(425f4418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425de300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(425de300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425dc2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(425dc2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
D/PMS     (  905): acquireWL(425d58c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
W/BroadcastQueue(  905): Exception when sending broadcast to ComponentInfo{com.htc.task/com.htc.task.notification.NotifyReceiver}
W/BroadcastQueue(  905): android.os.TransactionTooLargeException
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  905): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  905): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  905): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  905): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3830 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(425d58c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4254cd60): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3830 10071 null
,D/PMS     (  905): acquireWL(4254c0e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3830 10071 null
,D/Process (  905): killProcessQuiet, pid=3557
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3557:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/PMS     (  905): releaseWL(4254cd60): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): acquireWL(424d7de8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,E/TodoTaskNotifyService( 3830): java.lang.NullPointerException
W/System.err( 3830): java.lang.NullPointerException
W/System.err( 3830): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3830): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3830): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3830): stopSelfResult true
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3557
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): releaseWL(4254c0e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/PMS     (  905): releaseWL(424d7de8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  905): acquireWL(423c2148): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3780 10111 null
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,I/WSP     ( 1295): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1295): Weather sync is On
D/PMS     (  905): releaseWL(423c2148): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/WSP     ( 1295): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Mar 02 10:08:17 CET 2016
,W/WSP     ( 1295): [Receiver] can't get active network info
D/ConnectivityService(  905): Done.
D/ConnectivityService(  905): Setting timer for 720seconds
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1295/10055)
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/WSP     ( 1295): [SyncService] no data connection, stop sync service
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1295/10055)
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(424e1900): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3780 10111 null
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  905): releaseWL(424e1900): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Finsky  ( 3719): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3719): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  905): sending alarm PendingIntent{42551ad0: PendingIntentRecord{42565490 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456906097249, Int=0
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1295): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1295): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3719): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/MediaManager( 3461): [DualLensScanUtil]	mmpCursor count is 0
,D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3719): [NET] getaddrinfo_proxy-
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3719): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
,I/Icing   ( 1976): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1976): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/IcingCorporaProvider( 2664): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
D/PMS     (  905): releaseWL(425c1ac0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(425f06a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3692 10160 null
D/PMS     (  905): releaseWL(425f06a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/PackageBroadcastService( 1976): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1976): Null package name or gms related package.  Ignoreing.
,W/MediaManager( 3461): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
D/PMS     (  905): acquireWL(4263db20): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 1976): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/TodoTaskshortcut( 3830): update TASK shortcut>
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
,W/MediaManager( 3461): [DualLensScanUtil]	mmpCursor count is 0
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42642e78): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3478 10154 null
,I/ActivityManager(  905): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3478): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3719): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ContextImpl( 3478): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/MusicLeanback( 3478): Conditions not met for autocaching.
,I/MusicLeanback( 3478): Stop autocaching.
,D/Finsky  ( 3719): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (3719/10074)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3478, uid=10154, userID:0
D/PMS     (  905): releaseWL(42642e78): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/Finsky  ( 3719): [1] DailyHygiene.reschedule: Scheduling new run in 267 minutes (failures=4)
V/AlarmManager(  905): sending alarm PendingIntent{425cf3b8: PendingIntentRecord{424e8670 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1456906097790, Int=0
,D/DeviceConnectionService( 1196): client connected with version: 8296000
,D/Finsky  ( 3719): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3719): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3877 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3877): Loading default preferences
,W/Resources( 3877): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 3877): Overriding preferences with custom values
,D/SyncApplication( 3877): Updating preferences succeeded
,E/SyncApplication( 3877): Application created.
D/VolumeInfo( 3877): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3877): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3877): Found 0 mount point(s)
,V/VolumeInfo( 3877): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3877): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3877): getNewCalendarAuthority()...
,D/VolumeInfo( 3877): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3877): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3877): enableAppOperation()+
,D/SyncApplication( 3877): enableAppOperation()-
,D/HTCUtilities( 3877): isNeorSinged() + 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3877, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3877, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3877): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3877): isNeorSinged() return false
,D/CDMountReceiver( 3877): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3877): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3877): enable CD Auto-mount: true
,D/DotMatrix( 1517): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3877): enable auto-mount
,D/HTCUtilities( 3877): enable auto-mount
,I/ActivityManager(  905): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1106): com.nero.android.htc.sync (false,0)
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  905): Resuming delayed broadcast
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41be67f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1106): com.nero.android.htc.sync 1 14 4 11
,I/RemoteViews( 1106): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41bebd20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.nero.android.htc.sync 0 9 3 16
,W/MediaManager( 3461): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3589
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3589:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3589
,D/PMS     (  905): acquireWL(4235bbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(4235bbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42581128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(42581128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41c28388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,D/PMS     (  905): acquireWL(423ac4c8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3719 10074 null
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,D/Finsky  ( 3719): [395] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(41c28388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
D/PMS     (  905): releaseWL(423ac4c8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(42497000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,I/Icing   ( 1976): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1976): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1976): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(4263db20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 7 times.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1976, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1976, uid=10029, userID:0
,I/CheckinService( 1976): Done disabling old GoogleServicesFramework version
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1976, uid=10029, userID:0
,I/GAV2    ( 3757): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3780): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1457): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1457): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3908 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3908): onCreate
D/ProviderChangeReceiver( 3908): ---------------------------------------------------
,D/ProviderChangeReceiver( 3908): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3908): start to updateAlertNotification!
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3922 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3296
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3296:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AlertService( 3908): No fired or scheduled alerts
,D/HtcAlertUtils( 3908): -- cancelReminderNotification --
,D/HtcAlertUtils( 3908): broadcastExistReminder!
I/ActivityManager(  905): Recipient 3296
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3922): [3922/3922] onCreate()
W/ContextImpl( 3922): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=3520
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3520:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3520
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42635c30 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 8 times.
,I/SensorManager(  905): mEventCount = 600
,D/PMS     (  905): acquireWL(425d9ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425d9ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 9 times.
,D/AutoSetting( 1295): service - handleMessage() stop self
,D/AutoSetting( 1295): service - handleMessage() quit looper
,D/AutoSetting( 1295): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3349
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3349:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3349
,I/SensorManager(  905): mEventCount = 750
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 10 times.
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
,D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  905): [NET] getaddrinfo_proxy-
D/PMS     (  905): acquireWL(4281bd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{423950d8: PendingIntentRecord{4234c4d0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81959, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{427f6730: PendingIntentRecord{42692fd0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456906112454, Int=0
,D/PMS     (  905): releaseWL(4281bd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3719): [386] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3719): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/SensorManager(  905): mEventCount = 900
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 12 times.
,D/PMS     (  905): acquireWL(428194e0): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428194e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426b9c38): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426b9c38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4268f320): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4268f320): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42685960): PARTIAL_WAKE_LOCK  Icing 0x1 1976 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42685960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1457): handler message = 4011
,E/HtcModeClient( 1457): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1457): Don't start project servcice
,D/HtcModeClient( 1457): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1457): connectState: CONNECTION_READY = false
,D/SilentMusic( 1457): call stop
,D/HtcModeClient( 1457): close connection
,W/HtcModeClient( 1457): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1457): read the terminate packet, so break
,D/Process (  905): killProcessQuiet, pid=3638
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3638:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3638
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3939 uid=10078 gids={50078}
,D/PMS     (  905): acquireWL(42630750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10078}
,V/AlarmManager(  905): sending alarm PendingIntent{424477f0: PendingIntentRecord{424e93a8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456906131182, Int=60000
,D/PMS     (  905): releaseWL(42630750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3939): SMSBackupAgentService started
,D/SMSBackup( 3939): Checking restore status
,D/SMSBackup( 3939): Restore complete
,D/SMSBackup( 3939): cancelCheckAlarm
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/SMSBackup( 3939): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3665
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3665:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3665
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  905): mEventCount = 1050
,V/LightsService(  905): setLight #0: color=#23
,V/LightsService(  905): setLight #0: color=#20
,V/LightsService(  905): setLight #0: color=#16
,V/LightsService(  905): setLight #0: color=#14
,I/SensorManager(  905): mEventCount = 1200
,D/PMS     (  905): acquireWL(42569c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105625, Int=0
,D/PMS     (  905): releaseWL(42569c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1106): now=1456906140055 next=59945
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420c08e8
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420c08e8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e61f0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4243b8a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  905): mWirelessDisplayManager is null
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 336ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=1247
D/NfcService( 1224): ScreenObserver: OFF
D/NfcService( 1224): applyRouting - 0
,D/NfcService( 1224): applyRouting -2
D/PMS     (  905): acquireWL(42488cb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1224 1027 null
D/PMS     (  905): releaseWL(42488cb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4236db10)
,I/IntentController( 1106): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  905): wakingUp
,D/PMS     (  905): acquireWL(425b4a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  905): No lock screen! windowToken=null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(425b4a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMN     (  905): onScreenOn
D/MtpService( 2048): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2048): [MTP][onReceive]-
,D/NfcService( 1224): applyRouting - 0
,D/NfcService( 1224): applyRouting -2
,D/AutoSetting( 1295): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  905): acquireWL(42818e70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1224 1027 null
D/PMS     (  905): releaseWL(42818e70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/AutoSetting( 1295): service - onCreate()
D/TetherSettings( 3425): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3425): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3425): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3425): Cust_ConnectToPC   : spcsc>false
D/        ( 3425): Cust_ConnectToPC   : IPT>true
D/        ( 3425): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3425): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3425): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3425): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3425): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1295): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3425): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3425): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/ClockThread( 1106): stop update clock
D/AutoSetting( 1295): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 3425): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3425): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3425):  defaultType:0
,D/LocationManagerService(  905): request 4236eae8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  905):    returned false
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  905): updateScreenOn: false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3962 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(425b6498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425b6498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(425bf5c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425bf5c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e61f0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e61f0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4243b8a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(427b6c68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/FeedHostManager( 1247): [onPause]
,I/FeedProviderManager( 1247): onPause
,I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b083c8
I/SocialFeedProvider( 1247): +onPause
,I/SocialFeedProvider( 1247): -onPause
W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20522 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  905):    returned false
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: false
D/PMS     (  905): acquireWL(42806cf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(42806cf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  905): releaseWL(427b6c68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/PMS     (  905): acquireWL(42676f18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3962 1000 null
,D/SmartSyncUtils( 3962): isEpsOn(), nState = 0
,D/PMS     (  905): releaseWL(42676f18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/PhoneStatusBar( 1106): removeHeadsNotification.gc: 54
,D/SmartSyncUtils( 3962): getMobilePolicyEnabled, result = true
,W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3962): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3962): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3962): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4243b8a0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4243b8a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4243b8a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4243b8a0
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422d2a58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422d2a58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  905): acquireWL(425d87a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425d87a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42699008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42699008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1295): service - mHandler: cancel location update
,D/AutoSetting( 1295): service -           changes count: 0
,D/Process (  905): killProcessQuiet, pid=3501
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3501:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3501
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42652f10 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(4268a0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4268a0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(426631e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42557798: PendingIntentRecord{426bbde0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122566, Int=0
,D/PMS     (  905): acquireWL(42664940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{423ce4d0: PendingIntentRecord{4265c698 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137676, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,D/PMS     (  905): releaseWL(42664940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426631e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1295): service - handleMessage() stop self
,D/AutoSetting( 1295): service - handleMessage() quit looper
,D/AutoSetting( 1295): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3621
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3621:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3621
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4269a480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423950d8: PendingIntentRecord{4234c4d0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141978, Int=0
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  905): [NET] getaddrinfo_proxy-,
V/AlarmManager(  905): sending alarm PendingIntent{42168ed8: PendingIntentRecord{42387b58 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141985, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(426f24a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(4269a480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  905): releaseWL(426f24a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(42765910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42765910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427673b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(427673b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 2355): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(426f5a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(426f5a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42771b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{423c8b30: PendingIntentRecord{426bbde0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182331, Int=0
,D/PMS     (  905): acquireWL(4276abb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: ,
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  905): [NET] getaddrinfo_proxy-
V/AlarmManager(  905): sending alarm PendingIntent{423950d8: PendingIntentRecord{4234c4d0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201998, Int=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
D/PMS     (  905): releaseWL(42771b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4276ee30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4276abb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4276ee30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4268de08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(4268de08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428291e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): acquireWL(427691a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1196): Vacuum at: now=1456906236701 tag=VacuumService
,D/PMS     (  905): releaseWL(428291e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(427691a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426a8798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(426a8798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426ac0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024473
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024602
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024688
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024691
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024697
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026043
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026054
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028955
,D/PMS     (  905): releaseWL(426ac0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4279ac68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225625, Int=0
,D/PMS     (  905): releaseWL(4279ac68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42756008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42756008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4282af40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4282af40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42646630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=285625, Int=0
,D/PMS     (  905): releaseWL(42646630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426480c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(426480c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427fbfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427fbfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  905): killProcessQuiet, pid=2546
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2546:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2546
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42800438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=345625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42800438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42776c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(42776c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(4280af50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4280af50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42810ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=405625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42810ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(428129b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(428129b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427de4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427de4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427dfdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=465625, Int=0
,D/PMS     (  905): releaseWL(427dfdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427e1870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(427e1870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(427e6e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427e6e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(427e86f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=525625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427e86f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427eb978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427eb978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427f0f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427f0f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4279c290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=585625, Int=0
,D/PMS     (  905): releaseWL(4279c290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4279dd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4279dd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427a3308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427a3308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1213): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1213): sku_id=99
D/ContactMessageStore( 1213): start background delete task...
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/PMS     (  905): acquireWL(427a8de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=645625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427a8de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427aa860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427aa860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(427bdca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427bdca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1106): closing low battery warning: level=100
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427c3678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=705625, Int=0
,D/PMS     (  905): releaseWL(427c3678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427c5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427c5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427ca6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427ca6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427cc560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=765625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427cc560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427cdfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427cdfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427d35b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(427d35b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427d8fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=825625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427d8fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427daa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427daa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427dbf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427dbf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42609450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=885625, Int=0
,D/PMS     (  905): releaseWL(42609450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4260b6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(4260b6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42611698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=945625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42611698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426132c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426132c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(4261ad48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(4261ad48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42620720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1005625, Int=0
,D/PMS     (  905): releaseWL(42620720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42623070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d897e0: PendingIntentRecord{42435aa0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782831, Int=0
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4020 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  905): sending alarm PendingIntent{4240d448: PendingIntentRecord{42532100 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4031 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42476d40: PendingIntentRecord{4240dd48 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1456906246918, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42365ab8: PendingIntentRecord{42295690 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456906967337, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{42320660: PendingIntentRecord{42673f38 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456907042014, Int=0
,W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3962): call getInstance()
,D/SmartSyncUtils( 3962): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3962): MY_DEBUG = false
D/PMS     (  905): releaseWL(42623070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  905): acquireWL(42701840): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3962 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3962): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3962): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3962): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3962): SettingOnTime = 1456984800000, randomSettingOnTime = 1456984661000
,D/SmartSyncScreenOnOffTimeReceiver( 3962): SettingOffTime = 1456970400000, randomSettingOffTime = 1456976462000
,D/SmartSyncScreenOnOffTimeReceiver( 3962): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 3962): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3962): bNightModeTurnOffOnce = false
D/PMS     (  905): releaseWL(42701840): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4031/10049)
I/ImageRamCache( 4020): create image Cache, size: 31457280.
I/ImageRamCache( 4020): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4020): create image Cache, size: 12582912.
I/FeedSettings( 4020): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4020): GroupBudget 0.500000 0.380000
I/FeedSettings( 4020): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4020): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4020): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4020): loadGridSize() with Alternative
,D/libc    ( 4020): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4020): [NET] getaddrinfo-,err=8
D/libc    ( 4020): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4020): [NET] getaddrinfo-, 1
,D/libc    ( 4020): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 4020): [NET] getaddrinfo_proxy-,
,E/[CSBICLIENT][v9][BiLogUploadService]( 4020): Exception on getConfig()
,D/Process (  905): killProcessQuiet, pid=3780
W/BatSI   (  905): Couldn't get kernel wake lock stats
,I/ActivityManager(  905): Killing 3780:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3780
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=3692
,I/ActivityManager(  905): Killing 3692:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3692
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(427c5d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(427c5d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42660b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42660b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4276ffb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1065625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4276ffb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425a70f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425a70f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1106): closing low battery warning: level=98
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1517): [EventService] reorderNotification, total:1
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/TetherSettings( 3425): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3425): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3425): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3425): Cust_ConnectToPC   : spcsc>false
D/        ( 3425): Cust_ConnectToPC   : IPT>true
,D/        ( 3425): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3425): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3425): Index of the first 1 = -1
W/ContextImpl( 3425): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3425): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3425): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3425): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3425): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3425): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3425): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1106): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4280cee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(4280cee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=98
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42619298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42619298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427b4598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1125625, Int=0
,D/PMS     (  905): releaseWL(427b4598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427add48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427add48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425eb188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1185625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425eb188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425bb6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(425bb6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=98
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425b8588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425b8588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  905): acquireWL(425d7b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4204e898: PendingIntentRecord{42015fe8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1245625, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425d7b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3719): [NET] getaddrinfo-,err=8
D/libc    ( 3719): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3719): [NET] getaddrinfo-, 1
,D/libc    ( 3719): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3719): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(42698b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1517): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1517): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(42698b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=99
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:2 level:99 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4063): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4063): ====startRecUseTime====
D/htc.customization.log.level( 4063):  is 
W/CustomizationLogLevel( 4063): Level value is invalid, use default level 2
D/CustomizationManager( 4063):  Read ACC file spent 0.111 (s)
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4063): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4063): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4063): Parsing tag category name = system
I/CustomizationCIDLoader( 4063): Parsing tag category name = application
I/CustomizationCIDLoader( 4063): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4063): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4063): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4063): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4063): Parsing tag category name = Settings
D/CustomizationManager( 4063):  Read CID file spent 0.173 (s)
D/CustomizationManager( 4063):  All configurations done spent 0.174 (s)
W/HtcNativeFlag( 4063): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4063): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4063): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4063): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4063, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  905): Skipping PackageSetting{41fb0028 com.example.hello/10397} due to missing metadata
W/PackageSettings(  905): Skipping PackageSetting{41faf2f0 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  905): Package source /data/app/com.test.thalitest-2.apk does not exist.
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/PackageManager(  905): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1517): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1517): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1517): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(4282de18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 4020): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4020): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  905): releaseWL(4282de18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1259): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1295): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/[PluginManager]RegisterService( 1295): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
W/SystemReader( 1224): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4080 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
E/ExternalAccountType( 1316): Unsupported attribute readOnly
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
F/PackageManager(  905): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  905): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  905): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  905): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  905): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  905): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  905): 	... 9 more
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1456907303349.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/ErrorReport(  905): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  905): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  905): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  905): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  905): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  905): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 18 more
E/SQLiteLog( 2664): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2664): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6435c5e8
W/dalvikvm( 2664): threadid=14: thread exiting with uncaught exception (group=0x4166de30)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2664): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2664): Process: com.google.android.googlequicksearchbox:search, PID: 2664
E/AndroidRuntime( 2664): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2664): 	at cid.d(PG:186)
E/AndroidRuntime( 2664): 	at clo.g(PG:594)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2664): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2664): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2664): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2664): 	at clr.tL(PG:827)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2664): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2664): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2664): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2664): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2664): killProcess, pid=2664
D/Process ( 2664): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 2664
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2664) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2664): Died!
D/WifiService(  905): Client connection lost with reason: 4
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4080): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4080): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4080): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4080): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4080): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4080): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4080): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4080): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4080): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4080): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4080): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4080): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4080): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4080): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4080): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4080): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4080): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4080): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4080): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4080): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4080): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4080): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4080): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4080): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4080): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4080): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4080): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4080): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4080): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4080): threadid=11: thread exiting with uncaught exception (group=0x4166de30)
E/AndroidRuntime( 4080): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4080): Process: com.google.android.apps.docs, PID: 4080
E/AndroidRuntime( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4080): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4080): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4080): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4080): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4080): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4080): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4080): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4080): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4080): killProcess, pid=4080
D/Process ( 4080): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4097 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4080
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4080) has died.
W/ContextImpl( 4097): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4110 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4097): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4097): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4097): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4097): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4097): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4097): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4097): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4097): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4097): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4097): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4097): threadid=10: thread exiting with uncaught exception (group=0x4166de30)
E/AndroidRuntime( 4097): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4097): Process: com.android.keychain, PID: 4097
E/AndroidRuntime( 4097): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4097): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4097): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4097): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4097): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4097): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4097): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4097): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4097): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4097): killProcess, pid=4097
D/Process ( 4097): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1456907304308.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4110): getInstance(Context context)
D/AppTag  ( 4110): getInstance(Context context)
D/AppTag  ( 4110): onCreate()

```
