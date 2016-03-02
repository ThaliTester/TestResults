#### Test 61432979123161a_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
--------- beginning of /dev/log/main
D/Process (  906): killProcessQuiet, pid=3251
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/SoundPicker( 3432): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3432): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/ActivityManager(  906): Killing 3251:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/SoundPicker( 3432): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  906): Recipient 3251
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3432): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3432): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3432): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1985, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1985, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1985, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1985, uid=10029, userID:0
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1320): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1320): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1320): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 3263): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3263): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  906): Resuming delayed broadcast
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  906): Resuming delayed broadcast
E/ExternalAccountType( 1320): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3460 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
D/DFPI.PIReciver( 3210): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3210): onHandleIntent
I/DFPI.ApkInstallService( 3210): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3210): check CID = HTC__032
I/DFPI.ApkInstallService( 3210): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
E/cutils-trace( 3455): Error opening trace file: No such file or directory (2)
I/EASAppSvc( 3460): [ NA ]- onCreate()
I/EASAppSvc( 3460): [ NA ]> onUpgrade: version = 63
D/ORMLib  ( 3224): put()
I/EASAppSvc( 3460): [ NA ]- onDestroy()
I/EASAppSvc( 3460): [ NA ]> uninitEASService
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3460/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3460/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3460/10064)
D/CustomizationManager( 3455): ====startRecUseTime====
D/htc.customization.log.level( 3455):  is 
W/CustomizationLogLevel( 3455): Level value is invalid, use default level 2
D/AutoSetting( 1298): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1298): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1298): service - requestNLP() NetworkLocationProvider not enabled
D/CustomizationManager( 3455):  Read ACC file spent 0.084 (s)
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3455): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3455): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3455): Parsing tag category name = system
I/CustomizationCIDLoader( 3455): Parsing tag category name = application
I/CustomizationCIDLoader( 3455): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3455): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3455): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3455): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3455): Parsing tag category name = Settings
D/CustomizationManager( 3455):  Read CID file spent 0.143 (s)
D/CustomizationManager( 3455):  All configurations done spent 0.144 (s)
W/HtcNativeFlag( 3455): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3455): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3455): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3455): Fail to get flag for type 'language', use default value: -1
I/EASRequestController( 3460): [ NA ]release
I/EASAppSvc( 3460): [ NA ]< uninitEASService
I/EASAppSvc( 3460): [ NA ]- onCreate()
I/EASAppSvc( 3460): [ NA ]> onUpgrade: version = 63
W/PackageManager(  906): Unable to load service info ResolveInfo{42712f88 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3460/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3460/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3460/10064)
D/ORMLib  ( 3224): put()
I/EASAppSvc( 3460): [ NA ]- onDestroy()
I/EASAppSvc( 3460): [ NA ]> uninitEASService
I/EASRequestController( 3460): [ NA ]release
I/EASAppSvc( 3460): [ NA ]< uninitEASService
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3508 uid=10068 gids={50068, 3003, 5012}
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3455
D/Process (  906): killProcessQuiet, pid=3263
I/ActivityManager(  906): Killing 3263:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ORMLib  ( 3224): put()
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3263
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(426d81c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426d81c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426d9818): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426d9818): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426db4c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426db4c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3151
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3432): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  906): Killing 3151:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,W/ContextImpl( 3432): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3432): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3432): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3432): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3432): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Recipient 3151
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SocialFeedProvider( 1249): +disConnect socialManager
I/SocialFeedProvider( 1249): disconnect socialManager
I/SocialFeedProvider( 1249): -disConnect socialManager
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): SoundPicker,Util [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3524 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
V/AlarmManager(  906): sending alarm PendingIntent{42394610: PendingIntentRecord{424455d0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1456940308122, Int=0
,I/ImageRamCache( 3524): create image Cache, size: 31457280.
I/ImageRamCache( 3524): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3524): create image Cache, size: 12582912.
,I/FeedSettings( 3524): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3524): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3524): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3524): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3524): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3524): loadGridSize() with Alternative
,I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SocialManager[SocialBiLogHelper]( 3524): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3524): last commit ulog time 1456906095494
I/SocialManager[SocialBiLogHelper]( 3524): skip commit this time
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b32d38 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,I/MediaStoreImporter( 3390): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  906): sending alarm PendingIntent{425d3f38: PendingIntentRecord{426890d0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1456940308468, Int=0
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b32d38 -
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3210): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3210): onHandleIntent
,I/DFPI.ApkInstallService( 3210): Media Scan Finished Case 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3210): check CID = HTC__032
,I/DFPI.ApkInstallService( 3210): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PhoneApp( 1222): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1222): -- N1 =0
,D/PhoneApp( 1222): -- N2 =0
,D/PhoneApp( 1222): -- N3 =0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3166
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3166:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/SoundPicker( 3432): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3432): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3432): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3432): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3432): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3432): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3432): MODE_GSM access default DB
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  906): Recipient 3166
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3432): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExi,sted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3432): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3432): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3432): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3390): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42662360): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1486 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  906): releaseWL(42662360): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1222): bind: false
,D/TelephonyReceiver( 1222): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3549 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3562 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3279
,I/ActivityManager(  906): Killing 3279:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Recipient 3279
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425a2b00): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425a2b00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{41ef7db8: PendingIntentRecord{4250d850 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456940310225, Int=0
,W/GAV2    ( 3562): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  906): acquireWL(41ab84e0): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41ab84e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41b92480): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1108): com.htc.updater (true,33751552)
,I/iu.UploadsManager( 1985): End new media; added: 0, uploading: 0, time: 110 ms
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41da4368 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  906): killProcessQuiet, pid=3293
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3293:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/RemoteViews.Performance( 1108): com.htc.updater 4 8 1 10
,I/RemoteViews( 1108): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41aee408 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  906): Recipient 3293
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1108): com.htc.updater 1 6 0 10
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 6 times.
,D/PMS     (  906): releaseWL(41b92480): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1298): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1298): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2588): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/Gmail   ( 3562): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3562): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  906): acquireWL(424f52a0): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3562): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3562): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PMS     (  906): releaseWL(424f52a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423cbd78): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423cbd78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424216f8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424216f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42535988): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42535988): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423e3a30): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423e3a30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42401608): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42401608): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42469668): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42469668): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42530c48): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42530c48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41fea098): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41fea098): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425ada10): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425ada10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2588): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3601 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(425fcf70): PARTIAL_WAKE_LOCK  AsyncService 0x1 3601 10160 null
,D/PMS     (  906): releaseWL(425fcf70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(426023a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3601 10160 null
,I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  906): acquireWL(42308e20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3601 10160 null
,D/PMS     (  906): releaseWL(426023a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3601/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3601/10160)
,D/Settings:HtcWirelessFeatureFlags( 3336): id/is att sku: 99/false
,W/SystemReader( 3336): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3336): Cannot find support_harman, use default value instead
,W/SystemReader( 3336): Cannot find effect_manager_id, use default value instead
,D/PMS     (  906): releaseWL(42308e20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
E/Settings:HtcWrapHeaderInfo( 3336): no such activity!
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3628 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3316
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3316:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3336): The wrap header doesn't exist in header list.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3316
D/WifiService(  906): Client connection lost with reason: 4
,E/Settings:HtcWrapHeaderInfo( 3336): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3336): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]support         :false
,W/FingerprintManager( 3336): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3336): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3336): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3628, uid=10074, userID:0
,D/Finsky  ( 3628): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3628/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3336): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3336): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3336): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3336): [supportHomeButton]support         :false
,W/FingerprintManager( 3336): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3336): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3336): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3628/10074)
,D/Finsky  ( 3628): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,W/Settings( 3628): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3628): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3628, uid=10074, userID:0
,D/Finsky  ( 3628): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3628): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 3628): Skipping gmscore version check
,D/Finsky  ( 3628): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3628): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 3628): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  906): killProcessQuiet, pid=3353
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3353:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
D/libc    ( 3628): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
I/ActivityManager(  906): Recipient 3353
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1985): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(425a8338): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425a8338): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425a2880): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425a2880): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(420528e0): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1985): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1985): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1985): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1985): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1985): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1985): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1985): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1985, uid=10029, userID:0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{424061e8 u0 com.google.android.gms/.gcm.GcmService}
,I/PeopleDatabaseHelper( 1985): cleanUpNonGplusAccounts done.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/SensorManager(  906): mEventCount = 600
,D/PMS     (  906): acquireWL(4220d718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3673 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  906): releaseWL(4220d718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 3673): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3673): MmsConfig.loadMmsSettings
,W/dalvikvm( 3673): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3673): VFY: unable to resolve instance field 36
,W/dalvikvm( 3673): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3673): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2472): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2472): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3673): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3673): MmsConfig.loadFromDatabase
,E/Babel   ( 3673): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3673): MmsConfig.loadFromResources
,E/Babel   ( 3673): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3673): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3673, uid=10111, userID:0
,W/Settings( 3673): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3673, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3673, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3673, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3673, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3673, uid=10111, userID:0
D/PMS     (  906): acquireWL(4241d5f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3673 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3673): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(4241d5f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(423a97d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3673 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(423a97d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3195
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): acquireWL(423672b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Killing 3195:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
I/ActivityManager(  906): Recipient 3195
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(423672b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41b39ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(41b39ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1348): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
,I/ActivityManager(  906): Resuming delayed broadcast
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  906): acquireWL(425548b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(425548b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): acquireWL(42613270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(42613270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426541f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(426541f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42673a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(42673a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426f11a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(426f11a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4269aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  906): acquireWL(425cec48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3224 10071 null
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): acquireWL(426a4ed8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3224 10071 null
,V/AlarmManager(  906): sending alarm PendingIntent{425373d8: PendingIntentRecord{4268d6a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456940312328, Int=0
,D/Finsky  ( 3628): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/TodoTaskNotifyService( 3224): java.lang.NullPointerException
,W/System.err( 3224): java.lang.NullPointerException
W/System.err( 3224): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3224): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/dalvikvm( 3628): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
W/System.err( 3224): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3224): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3224): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): releaseWL(425cec48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  906): releaseWL(426a4ed8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3224): stopSelfResult true
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(4269aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425b4ae8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,D/PMS     (  906): releaseWL(425b4ae8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(4266db20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3673 10111 null
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
D/PMS     (  906): releaseWL(4266db20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  906): Done.
,I/WSP     ( 1298): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1298): Weather sync is On
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/WSP     ( 1298): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Mar 02 19:38:32 CET 2016
,W/WSP     ( 1298): [Receiver] can't get active network info
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/WSP     ( 1298): [SyncService] no data connection, stop sync service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
,D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3628): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,I/Icing   ( 1985): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1985): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): releaseWL(420528e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42707030): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3673 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(42707030): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3628): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/[PluginManager]RegisterService( 1298): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1298): handle notify Blinkfeed plugin client changed
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2588): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/MediaManager( 3372): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(4267de98): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4267de98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424d7db8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424d7db8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424f50d8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3372): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): releaseWL(424f50d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4229fa48): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42166fd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3601 10160 null
,D/PMS     (  906): releaseWL(42166fd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(4229fa48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 1985): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1985): Null package name or gms related package.  Ignoreing.
D/PMS     (  906): acquireWL(42422cc8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1985): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3224): update TASK shortcut>
,I/IcingCorporaProvider( 2588): UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3628): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3628): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3628/10074)
,D/Finsky  ( 3628): [1] DailyHygiene.reschedule: Giving up. (failures=6)
V/AlarmManager(  906): sending alarm PendingIntent{425b9f40: PendingIntentRecord{4252d828 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1456940313009, Int=0
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,W/MediaManager( 3372): [DualLensScanUtil]	mmpCursor count is 0
,D/Finsky  ( 3628): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3628): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4261efd0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3390 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3390): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3390, uid=10154, userID:0
,I/MusicLeanback( 3390): Conditions not met for autocaching.
,I/MusicLeanback( 3390): Stop autocaching.
,W/ContextImpl( 3390): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  906): releaseWL(4261efd0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3751 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3751): Loading default preferences
,W/Resources( 3751): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  906): New client listening to asynchronous messages
D/SyncApplication( 3751): Overriding preferences with custom values
,D/SyncApplication( 3751): Updating preferences succeeded
,E/SyncApplication( 3751): Application created.
D/VolumeInfo( 3751): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3751): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3751): Found 0 mount point(s)
V/VolumeInfo( 3751): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3751): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 3751): getNewCalendarAuthority()...
D/VolumeInfo( 3751): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3751): Can not create volume ID for unmounted volume null
D/SyncApplication( 3751): enableAppOperation()+
D/SyncApplication( 3751): enableAppOperation()-
,D/HTCUtilities( 3751): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3751, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3751, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3751): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3751): isNeorSinged() return false
,D/CDMountReceiver( 3751): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3751): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3751): enable CD Auto-mount: true
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3751): enable auto-mount
,D/HTCUtilities( 3751): enable auto-mount
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1108): com.nero.android.htc.sync (false,0)
I/ActivityManager(  906): Resuming delayed broadcast
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41be49f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1108): com.nero.android.htc.sync 2 12 3 11
I/RemoteViews( 1108): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41e2f938 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.nero.android.htc.sync 1 9 2 16
,W/MediaManager( 3372): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=2718
,I/ActivityManager(  906): Killing 2718:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Recipient 2718
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(424f4808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(424f4808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423fcc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(423fcc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423aa648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): acquireWL(4246dcf0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3628 10074 null
,D/Finsky  ( 3628): [391] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
D/PMS     (  906): releaseWL(423aa648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4246dcf0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42501f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/PMS     (  906): acquireWL(422bef10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(422bef10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 1985): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1985): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1985): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42422cc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GAV2    ( 3562): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 7 times.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1985, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1985, uid=10029, userID:0
,I/CheckinService( 1985): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1985, uid=10029, userID:0
,I/GAV4    ( 3673): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1486): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1486): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3783 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3783): onCreate
D/ProviderChangeReceiver( 3783): ---------------------------------------------------
,D/ProviderChangeReceiver( 3783): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3783): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3797 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3460
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3460:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/AlertService( 3783): No fired or scheduled alerts
,D/HtcAlertUtils( 3783): -- cancelReminderNotification --
,D/HtcAlertUtils( 3783): broadcastExistReminder!
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  906): Recipient 3460
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/SensorManager(  906): mEventCount = 750
,V/Settings:HtcSettingsApplication( 3797): [3797/3797] onCreate()
W/ContextImpl( 3797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=3508
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3508:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3508
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{425dc660 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 8 times.
,D/PMS     (  906): acquireWL(42627210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42627210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  906): mEventCount = 900
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 9 times.
,D/AutoSetting( 1298): service - handleMessage() stop self
,D/AutoSetting( 1298): service - onDestroy() END
,D/AutoSetting( 1298): service - handleMessage() quit looper
,I/ActivityManager(  906): Killing 3524:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3524
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3524
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 10 times.
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/PMS     (  906): acquireWL(42719470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4228e7b0: PendingIntentRecord{42378d18 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81791, Int=0
,I/SensorManager(  906): mEventCount = 1050
V/AlarmManager(  906): sending alarm PendingIntent{42520430: PendingIntentRecord{42662850 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456940327643, Int=0
D/PMS     (  906): releaseWL(42719470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3628): [380] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3628): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(42657c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=89074, Int=0
,D/PMS     (  906): releaseWL(42657c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1108): now=1456940340056 next=59944
,D/PMS     (  906): acquireWL(425c99c8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425c99c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426ef270): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426ef270): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4267c4e8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4267c4e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426f8cb8): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426f8cb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 12 times.
,I/SensorManager(  906): mEventCount = 1200
,D/PMS     (  906): acquireWL(42536bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42536bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1486): Don't start project servcice
,D/HtcModeClient( 1486): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1486): connectState: CONNECTION_READY = false
D/SilentMusic( 1486): call stop
,D/HtcModeClient( 1486): close connection
,W/HtcModeClient( 1486): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1486): read the terminate packet, so break
,D/Process (  906): killProcessQuiet, pid=3210
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3210:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3210
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3814 uid=10078 gids={50078}
,D/PMS     (  906): acquireWL(42654cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10078}
,V/AlarmManager(  906): sending alarm PendingIntent{424de0f0: PendingIntentRecord{424d79d0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456940345820, Int=60000
,D/PMS     (  906): releaseWL(42654cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3814): SMSBackupAgentService started
,D/SMSBackup( 3814): Checking restore status
,D/SMSBackup( 3814): Restore complete
,D/SMSBackup( 3814): cancelCheckAlarm
,D/SMSBackup( 3814): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3432
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,I/ActivityManager(  906): Killing 3432:com.htc.sdm/u0a81 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3432
,V/LightsService(  906): setLight #0: color=#24
,V/LightsService(  906): setLight #0: color=#20
,V/LightsService(  906): setLight #0: color=#1a
,V/LightsService(  906): setLight #0: color=#14
,I/SensorManager(  906): mEventCount = 1350
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c0c80
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c0c80, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a0938
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4264d830
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 344ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1233): ScreenObserver: OFF
D/NfcService( 1233): applyRouting - 0
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1233): applyRouting -2
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1249
D/PMS     (  906): acquireWL(4261cd38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
,D/PMS     (  906): releaseWL(4261cd38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42704ab0)
D/PMN     (  906): wakingUp
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WindowManager(  906): No lock screen! windowToken=null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/PMN     (  906): onScreenOn
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906):    returned false
,D/MtpService( 2182): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1233): applyRouting - 0
,D/MtpService( 2182): [MTP][onReceive]-
,D/PMS     (  906): acquireWL(426f2fc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
,D/NfcService( 1233): applyRouting -2
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
D/PMS     (  906): releaseWL(426f2fc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ClockThread( 1108): stop update clock
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3834 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  906): updateScreenOn: false
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(426764e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426764e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42678158): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42678158): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a0938
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a0938, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4264d830
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 3834): isEpsOn(), nState = 0
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(42737248): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3834 1000 null
D/PMS     (  906): acquireWL(427382b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42737248): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1249): [onPause]
,I/FeedProviderManager( 1249): onPause
,I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bafda8
I/SocialFeedProvider( 1249): +onPause
,I/SocialFeedProvider( 1249): -onPause
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20385 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906):    returned false
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: false
D/PMS     (  906): acquireWL(42623340): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(42623340): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  906): releaseWL(427382b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1222): start background delete task...
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3834): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1298): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3336): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3336): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3336): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3336): Cust_ConnectToPC   : spcsc>false
D/        ( 3336): Cust_ConnectToPC   : IPT>true
D/        ( 3336): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3336): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3336): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3336): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3336): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1298): service - onCreate()
,I/PSReceiver( 3336): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1298): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1298): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  906): request 423c0378 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
I/SmartNS_PSService( 3336): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3336): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3336):  defaultType:0
W/ContextImpl( 3336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(427241d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42724d88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427241d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42724d88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 3834): isEpsOn(), nState = 0
D/SmartSyncUtils( 3834): isEpsOn(), nState = 0
D/SmartSyncUtils( 3834): getMobilePolicyEnabled, result = true
,D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4264d830
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4264d830, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4264d830, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4264d830
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4264dda8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4264dda8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  906): killProcessQuiet, pid=3413
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3413:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3413
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1298): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1298): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1298): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42720ca8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(426d3b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426d3b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(426d4d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{423e3628: PendingIntentRecord{422fb278 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121316, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{424ec8d8: PendingIntentRecord{426270f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135938, Int=0
,D/PMS     (  906): acquireWL(426d72d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  906): releaseWL(426d72d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426d4d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1298): service - handleMessage() stop self
,D/AutoSetting( 1298): service - handleMessage() quit looper
,D/AutoSetting( 1298): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3549
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3549:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3549
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/PMS     (  906): acquireWL(426b1780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4228e7b0: PendingIntentRecord{42378d18 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141807, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42427798: PendingIntentRecord{42460b40 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141815, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(426b4148): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(426b1780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(426b4148): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(426b9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1222): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(426bbe10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426bbe10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426bd810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42446b18: PendingIntentRecord{422fb278 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181108, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4228e7b0: PendingIntentRecord{42378d18 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201825, Int=0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  906): [NET] getaddrinfo-, 1
D/PMS     (  906): acquireWL(427742e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,D/PMS     (  906): releaseWL(426bd810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  906): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(42779f38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427742e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42779f38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4277f6a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(4277f6a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42782f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): acquireWL(42748a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1456940453101 tag=VacuumService
D/PMS     (  906): releaseWL(42782f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42748a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4273a8e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(4273a8e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42737a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
,D/PMS     (  906): releaseWL(42737a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427237b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209075, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427237b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4271ffe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4271ffe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...,
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42719b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42719b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42708ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42708ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426fcbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426fcbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-,
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426eab10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=329074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426eab10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426dacd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  906): n_update end
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(426dacd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(42387490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42387490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(425f4d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389075, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f4d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4241a878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4241a878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41fc6820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=449075, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41fc6820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4260bb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4260bb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(423e3dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=509074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423e3dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4233b468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4233b468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41e5b058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=569074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e5b058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42493778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42493778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1222): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1222): sku_id=99
D/ContactMessageStore( 1222): start background delete task...
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
,D/PMS     (  906): acquireWL(41fbec00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=629074, Int=0
,D/PMS     (  906): releaseWL(41fbec00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=2472
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2472:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2472
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4229b838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4229b838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(42650208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42650208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426f45a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=689074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426f45a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4247e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4247e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3336): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3336): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3336): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3336): Cust_ConnectToPC   : spcsc>false
D/        ( 3336): Cust_ConnectToPC   : IPT>true
,D/        ( 3336): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3336): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3336): Index of the first 1 = 3
W/Settings( 3336): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3336): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3336): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3336): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3336): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3336): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3336): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423328b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(423328b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42741a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=749074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42741a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424d6f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424d6f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425bde40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425bde40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426e83f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=809074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426e83f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425e9a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e9a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4269bed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4269bed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425ee910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=869074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425ee910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42600828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42600828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1108): closing low battery warning: level=100
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425d3ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(425d3ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425f10d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=929074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f10d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
,D/libc    ( 3628): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(4265f4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  906): releaseWL(4265f4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4267a1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4267a1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427337c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427337c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426d5f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41d762e0: PendingIntentRecord{42439dc0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781474, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3894 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{41d4ad40: PendingIntentRecord{41d2d408 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1456940461631, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42312850: PendingIntentRecord{4240e018 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456941181980, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{424f6768: PendingIntentRecord{42702b30 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456941256858, Int=0
,W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3834): call getInstance()
,D/SmartSyncUtils( 3834): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3834): MY_DEBUG = false
D/PMS     (  906): releaseWL(426d5f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(427001b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3834 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3834): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3834): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3834): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 3834): SettingOnTime = 1456984800000, randomSettingOnTime = 1456982202000
,D/SmartSyncScreenOnOffTimeReceiver( 3834): SettingOffTime = 1456970400000, randomSettingOffTime = 1456974276000
,D/SmartSyncScreenOnOffTimeReceiver( 3834): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3834): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3834): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(427001b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (3894/10049)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=3673
,I/ActivityManager(  906): Killing 3673:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3673
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(428adb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428adb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428ac470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(428ac470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428a0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428a0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4289d9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4289d9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42891c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42891c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42883590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1109074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42883590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42874f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42874f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42863378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42863378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42857b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1169074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42857b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428577e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(428577e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(428523d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428523d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42849110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4201a5d8: PendingIntentRecord{41f68b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1229074, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42849110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3628): [NET] getaddrinfo-,err=8
D/libc    ( 3628): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3628): [NET] getaddrinfo-, 1
D/libc    ( 3628): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3628): [NET] getaddrinfo_proxy-
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3921): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3921): ====startRecUseTime====
D/htc.customization.log.level( 3921):  is 
W/CustomizationLogLevel( 3921): Level value is invalid, use default level 2
D/CustomizationManager( 3921):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3921): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3921): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3921): Parsing tag category name = system
I/CustomizationCIDLoader( 3921): Parsing tag category name = application
I/CustomizationCIDLoader( 3921): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3921): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3921): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3921): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3921): Parsing tag category name = Settings
D/CustomizationManager( 3921):  Read CID file spent 0.092 (s)
D/CustomizationManager( 3921):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 3921): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3921): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3921): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3921): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=3921, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{4213db38 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{421417a8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1320): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(428bb128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(428bb128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1263): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Scheme: "sms"
I/[PluginManager]RegisterService( 1298): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/[PluginManager]RegisterService( 1298): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1320): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1320): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/IcingCorporaProvider( 2588): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
E/ExternalAccountType( 1320): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3935 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/IcingCorporaProvider( 2588): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  906): Unable to load service info ResolveInfo{4276a650 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
W/GAV2    ( 3935): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3956 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3969 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3601:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3601
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3601
D/AppTag  ( 3969): getInstance(Context context)
D/AppTag  ( 3969): getInstance(Context context)
D/AppTag  ( 3969): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3983 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3224
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3224:com.htc.task/u0a71 (adj 15): empty #17
W/GAV2    ( 3935): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/PMS     (  906): acquireWL(425d8818): PARTIAL_WAKE_LOCK  AsyncService 0x1 3983 10160 null
D/Process (  906): killProcessQuiet, pid=3390
W/dalvikvm( 3628): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3390:com.google.android.music:main/u0a154 (adj 15): empty #17
D/PMS     (  906): releaseWL(425d8818): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  906): acquireWL(42694580): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3983 10160 null
D/PackageBroadcastService( 1985): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1985): Clearing selected account for com.test.thalitest
I/ActivityManager(  906): Recipient 3390
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3390): Died!
D/ChimeraCfgMgr( 1985): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1985): Loading module APK com.google.android.play.games
D/PMS     (  906): acquireWL(42550698): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3983 10160 null
D/PMS     (  906): releaseWL(42694580): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  906): Recipient 3224
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/LocationSettingsChecker( 1985): Removing dialog suppression flag for package com.test.thalitest
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3983/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3983/10160)
W/dalvikvm( 1985): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/PMS     (  906): releaseWL(42550698): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
W/dalvikvm( 1985): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1985): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1985): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 1985): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 1985): App measurement is starting up, version: 8489
I/GMPM-SVC( 1985): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/PMS     (  906): acquireWL(4275f3d0): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 1985): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 1985): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1985): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1985): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1985): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1985): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1985): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1985, uid=10029, userID:0
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1985): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1985): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1985): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/PMS     (  906): releaseWL(4275f3d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1985): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1985): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/PMS     (  906): acquireWL(426ed610): PARTIAL_WAKE_LOCK  Icing 0x1 1985 10029 WorkSource{10029 com.google.android.gms}
D/gH_CompatibleDatabase( 1985): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1985): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1985): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1985): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
W/BaseAppContext( 1985): Using Auth Proxy for data requests.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b32d38 +
I/Prism.WidgetManager( 1249): onLoadItems() +
W/DriveInitializer( 1985): Background init thread started
W/DriveInitializer( 1985): Awaiting to be initialized
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 1985): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
W/DriveInitializer( 1985): Background init thread ended
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1985/10029)
W/dalvikvm( 1985): VFY: unable to find class referenced in signature (Landroid/util/Size;)
D/ChimeraCfgMgr( 1985): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1985): Module APK com.google.android.play.games already loaded
E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b32d38 -
I/ActivityManager(  906): Resuming delayed broadcast
E/NetworkScheduler.SchedulerReceiver( 1348): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1348): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  906): acquireWL(426efd50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1348 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4044 uid=10098 gids={50098, 3003, 5012}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1348/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
D/PMS     (  906): releaseWL(426efd50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PhoneApp( 1222): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1222): -- N1 =0
D/PhoneApp( 1222): -- N2 =0
D/PhoneApp( 1222): -- N3 =0
I/DeviceManagement( 4044): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4044 dbg=false s=true
I/DeviceManagement( 4044): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4044): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4044): WorkflowService: Starting workflow service
I/DeviceManagement( 4044): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ad3050] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4044): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4044): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4044): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4044): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4058 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4044): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4044): SessionStateController: Checking invariants...
I/Icing   ( 1985): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/Icing   ( 1985): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/Documents( 4058): Loading roots for com.android.providers.downloads.documents
D/Process (  906): killProcessQuiet, pid=3751
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(426ed610): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Killing 3751:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Documents( 4058): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  906): Recipient 3751
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4072 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  906): killProcessQuiet, pid=3372
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  906): Killing 3372:com.htc.mediamanager/u0a34 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3372
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4087 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3562
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3562:com.google.android.gm/u0a107 (adj 15): empty #17
D/ExternalStorage( 4072): After updating volumes, found 1 active roots
D/Documents( 4058): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4058): Loading roots for com.android.providers.media.documents
D/Documents( 4058): Loading roots for com.google.android.apps.docs.storage
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024030
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024157
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024229
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028437
I/ActivityManager(  906): Recipient 3562
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4058): Update found 7 roots in 177ms
D/Documents( 4058): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4058): Loading roots for com.android.externalstorage.documents
D/Process (  906): killProcessQuiet, pid=3783
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3783:com.htc.calendar/u0a13 (adj 15): empty #17
D/Documents( 4058): Used cached roots for com.android.providers.media.documents
D/Documents( 4058): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4058): Update found 7 roots in 12ms
I/ActivityManager(  906): Recipient 3783
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4044): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
I/DeviceManagement( 4044): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/DeviceManagement( 4044): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ad3050]
I/DeviceManagement( 4044): WorkflowService: Stopping workflow service
D/Process (  906): killProcessQuiet, pid=3797
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3797:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3797
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(428a4c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(428a4c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
I/GAV2    ( 3935): Thread[GAThread,5,main]: No campaign data found.

```
