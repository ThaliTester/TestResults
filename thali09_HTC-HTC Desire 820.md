#### Test 61699762a45f11c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
I/HtcModeClient( 1486): handler message = 4011
E/HtcModeClient( 1486): Check connection and retry 5 times.
E/cutils-trace( 3442): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3442): ====startRecUseTime====
D/htc.customization.log.level( 3442):  is 
W/CustomizationLogLevel( 3442): Level value is invalid, use default level 2
D/CustomizationManager( 3442):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3442): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3442): Parsing tag category name = system
I/CustomizationCIDLoader( 3442): Parsing tag category name = application
I/CustomizationCIDLoader( 3442): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3442): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3442): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3442): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3442): Parsing tag category name = Settings
D/CustomizationManager( 3442):  Read CID file spent 0.107 (s)
D/CustomizationManager( 3442):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3442): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3442): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3442): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3442): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3442
I/ActivityManager(  911): Resuming delayed broadcast
D/Process (  911): killProcessQuiet, pid=3240
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3240:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/SoundPicker( 3421): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3421): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3421): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3421): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3421): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3421): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  911): Recipient 3240
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1312): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 3252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/dalvikvm-heap( 1249): Grow heap (frag case) to 13.329MB for 53840-byte allocation
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1312): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1312): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  911): Resuming delayed broadcast
E/ExternalAccountType( 1312): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Scheme: "mmsto"
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  911): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3459 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3199): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  911): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3199): onHandleIntent
,I/DFPI.ApkInstallService( 3199): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3199): check CID = HTC__032
,I/DFPI.ApkInstallService( 3199): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/AutoSetting( 1296): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1296): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1296): service - requestNLP() NetworkLocationProvider not enabled
,I/EASAppSvc( 3459): [ NA ]- onCreate()
,I/EASAppSvc( 3459): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3213): put()
,I/EASAppSvc( 3459): [ NA ]- onDestroy()
,I/EASAppSvc( 3459): [ NA ]> uninitEASService
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (3459/10064)
,D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (3459/10064)
,D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (3459/10064)
,W/PackageManager(  911): Unable to load service info ResolveInfo{427fa6e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,I/EASRequestController( 3459): [ NA ]release
,I/EASAppSvc( 3459): [ NA ]< uninitEASService
,I/EASAppSvc( 3459): [ NA ]- onCreate()
,I/EASAppSvc( 3459): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (3459/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (3459/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (3459/10064)
,D/ORMLib  ( 3213): put()
,I/EASAppSvc( 3459): [ NA ]- onDestroy()
,I/EASAppSvc( 3459): [ NA ]> uninitEASService
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/EASRequestController( 3459): [ NA ]release
I/ActivityManager(  911): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3492 uid=10068 gids={50068, 3003, 5012}
,I/EASAppSvc( 3459): [ NA ]< uninitEASService
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/Process (  911): killProcessQuiet, pid=3252
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Killing 3252:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/LocationProviderProxy(  911): applying state to connected service
I/SocialFeedProvider( 1249): +disConnect socialManager
,I/SocialFeedProvider( 1249): disconnect socialManager
,I/SocialFeedProvider( 1249): -disConnect socialManager
D/PMS     (  911): acquireWL(4219d278): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4219d278): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Recipient 3252
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3213): put()
D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(42378a88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42378a88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(424440b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(424440b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3513 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  911): sending alarm PendingIntent{42430248: PendingIntentRecord{42439c00 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457092575936, Int=0
,I/ImageRamCache( 3513): create image Cache, size: 31457280.
I/ImageRamCache( 3513): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3513): create image Cache, size: 12582912.
,I/FeedSettings( 3513): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3513): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3513): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3513): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3513): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3513): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3513): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3513): last commit ulog time 1457013622347
,I/SocialManager[SocialBiLogHelper]( 3513): skip commit this time
,D/Process (  911): killProcessQuiet, pid=3140
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3140:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3140
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3155
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3155:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/SoundPicker( 3421): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b3be10 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,W/ContextImpl( 3421): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/ActivityManager(  911): Recipient 3155
,I/SoundPicker( 3421): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3421): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3421): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3421): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
,I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
V/AlarmManager(  911): sending alarm PendingIntent{42602798: PendingIntentRecord{42657b08 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457092576302, Int=0
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3379): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b3be10 -
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/DFPI.PIReciver( 3199): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3199): onHandleIntent
,I/DFPI.ApkInstallService( 3199): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3199): check CID = HTC__032
,I/DFPI.ApkInstallService( 3199): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,I/SensorManager(  911): mEventCount = 600
,I/ActivityManager(  911): Resuming delayed broadcast
,I/SoundPicker( 3421): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3421): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3421): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3421): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3421): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3421): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3421): MODE_GSM access default DB
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3421): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lil,ac.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3421): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3421): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3421): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,V/AlarmManager(  911): sending alarm PendingIntent{423c6d30: PendingIntentRecord{425fd820 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457092578079, Int=0
,I/MediaStoreImporter( 3379): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(425b7048): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1486 10014 null
I/ActivityManager(  911): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  911): releaseWL(425b7048): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1217): bind: false
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3540 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
I/iu.UploadsManager( 1961): End new media; added: 0, uploading: 0, time: 89 ms
,I/ActivityManager(  911): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3553 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3268
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3268:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3268
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42535488): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42535488): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3553): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 6 times.
,D/DotMatrix( 1536): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
D/NotificationService(  911): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41b5a490 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 4 8 0 10
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41d656d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.updater 2 7 0 10
,I/ActivityManager(  911): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  911): acquireWL(427efdf0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  911): killProcessQuiet, pid=3282
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3282:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3282
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(427efdf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.android.providers.contacts/.PackageIntentReceiver
,D/PMS     (  911): acquireWL(42657458): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42657458): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  911): acquireWL(426280d8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3553): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  911): releaseWL(426280d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3553): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  911): acquireWL(425f9cf0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3553): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3553): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PMS     (  911): releaseWL(425f9cf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425164c8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425164c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(421c8620): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(421c8620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41f13bc8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41f13bc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41b8a620): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41b8a620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425228b0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425228b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4237ffb8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4237ffb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41eb2688): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41eb2688): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4238f988): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4238f988): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 307 ms] updated apps [took 307 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3591 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(41f08a00): PARTIAL_WAKE_LOCK  AsyncService 0x1 3591 10160 null
,D/PMS     (  911): releaseWL(41f08a00): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  911): acquireWL(42503800): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3591 10160 null
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  911): acquireWL(42220c38): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3591 10160 null
,D/PMS     (  911): releaseWL(42503800): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3591/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3591/10160)
,D/PMS     (  911): releaseWL(42220c38): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3618 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3305
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3305:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3305
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,D/Settings:HtcWirelessFeatureFlags( 3326): id/is att sku: 99/false
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/SystemReader( 3326): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3618, uid=10074, userID:0
W/SystemReader( 3326): Cannot find support_harman, use default value instead
W/SystemReader( 3326): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3326): no such activity!
,D/Finsky  ( 3618): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3326): The wrap header doesn't exist in header list.
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3618/10074)
,E/Settings:HtcWrapHeaderInfo( 3326): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3326): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]support         :false
,W/FingerprintManager( 3326): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3326): isSupportVoWifi: null
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3326): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3618/10074)
,D/Finsky  ( 3618): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
W/dalvikvm( 3618): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 3618): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3618): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3326): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3326): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3326): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3326): [supportHomeButton]support         :false
,W/FingerprintManager( 3326): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3326): isSupportVoWifi: null
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3326): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3618, uid=10074, userID:0
,D/Finsky  ( 3618): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 3618): Skipping gmscore version check
,D/Finsky  ( 3618): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3618): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/Finsky  ( 3618): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  911): killProcessQuiet, pid=2646
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Killing 2646:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 2646
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  911): acquireWL(426340d0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426340d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42417878): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4265c0a0 u0 com.google.android.gms/.gcm.GcmService}
,D/PMS     (  911): releaseWL(42417878): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(425b24f0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/PMS     (  911): acquireWL(425b44f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,D/PMS     (  911): releaseWL(425b44f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1961): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1961): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1961): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1961): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 1961): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1961): cleanUpNonGplusAccounts done.
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3663 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/dalvikvm( 3663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3663): VFY: unable to resolve instance field 36
,W/dalvikvm( 3663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3663): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 3663): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3663): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 2465): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2465): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3663): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3663): MmsConfig.loadFromDatabase
,E/Babel   ( 3663): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3663): MmsConfig.loadFromResources
,E/Babel   ( 3663): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3663): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3663, uid=10111, userID:0
,W/Settings( 3663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3663, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3663, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3663, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3663, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3663, uid=10111, userID:0
D/PMS     (  911): acquireWL(427e4ec0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3663 10111 null
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3663): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  911): releaseWL(427e4ec0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(427e7fa8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3663 10111 null
,I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  911): releaseWL(427e7fa8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(4275eaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,I/ActivityManager(  911): Killing 3343:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,D/Process (  911): killProcessQuiet, pid=3343
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,I/ActivityManager(  911): Recipient 3343
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(4275eaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42643bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(42643bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1349): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
I/ActivityManager(  911): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,I/ActivityManager(  911): Resuming delayed broadcast
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  911): acquireWL(425b5cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(425b5cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): acquireWL(425b9928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(425b9928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42757b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(42757b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42777260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(42777260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42691418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(42691418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427c7478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 3618): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3618): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  911): sending alarm PendingIntent{4259c850: PendingIntentRecord{425fc010 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457092580359, Int=0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
D/PMS     (  911): acquireWL(42767598): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3213 10071 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
E/TodoTaskNotifyService( 3213): java.lang.NullPointerException
,W/System.err( 3213): java.lang.NullPointerException
W/System.err( 3213): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3213): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3213): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3213): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
D/PMS     (  911): acquireWL(4267f778): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3213 10071 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
I/ActivityManager(  911): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  911): releaseWL(42767598): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/NotifyReceiver( 3213): stopSelfResult true
D/PMS     (  911): releaseWL(4267f778): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): releaseWL(427c7478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42638318): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  911): releaseWL(42638318): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  911): acquireWL(425c2e18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3663 10111 null
,I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  911): releaseWL(425c2e18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,I/WSP     ( 1296): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1296): Weather sync is On
,I/WSP     ( 1296): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 13:56:20 CET 2016
,W/WSP     ( 1296): [Receiver] can't get active network info
D/ConnectivityService(  911): Done.
D/ConnectivityService(  911): Setting timer for 720seconds
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1296/10055)
,V/WSP     ( 1296): [SyncService] no data connection, stop sync service
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1296/10055)
,D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,W/Finsky  ( 3618): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3618): [NET] getaddrinfo-,err=8
,D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3618): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,I/Icing   ( 1961): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/MediaManager( 3362): [DualLensScanUtil]	mmpCursor count is 0
,I/ActivityManager(  911): Resuming delayed broadcast
,I/Icing   ( 1961): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  911): releaseWL(425b24f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(4251c8b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3663 10111 null
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  911): releaseWL(4251c8b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  911): acquireWL(42371e00): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42371e00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426735a8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3362): [DualLensScanUtil]	mmpCursor count is 0
D/PMS     (  911): releaseWL(426735a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42530860): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(425b6228): PARTIAL_WAKE_LOCK  AsyncService 0x1 3591 10160 null
,D/PMS     (  911): releaseWL(42530860): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425b6228): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(425b3868): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1961): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  911): Delay finish: com.htc.task/.TodoReceiver
,I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 3213): update TASK shortcut>
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3618): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3618): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,D/Finsky  ( 3618): [1] DailyHygiene.reschedule: Giving up. (failures=6)
V/AlarmManager(  911): sending alarm PendingIntent{41f52368: PendingIntentRecord{4275b7b8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1457092580996, Int=0
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 3618): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3618): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 405 ms] updated apps [took 405 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3362): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(41fa7ad0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3379 10154 null
,I/ActivityManager(  911): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3379): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3379): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3379): Conditions not met for autocaching.
,I/MusicLeanback( 3379): Stop autocaching.
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3379, uid=10154, userID:0
D/PMS     (  911): releaseWL(41fa7ad0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3744 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3744): Loading default preferences
,W/Resources( 3744): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  911): New client listening to asynchronous messages
,D/SyncApplication( 3744): Overriding preferences with custom values
,D/SyncApplication( 3744): Updating preferences succeeded
,E/SyncApplication( 3744): Application created.
D/VolumeInfo( 3744): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3744): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3744): Found 0 mount point(s)
,V/VolumeInfo( 3744): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3744): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3744): getNewCalendarAuthority()...
,D/VolumeInfo( 3744): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3744): Can not create volume ID for unmounted volume null
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3744, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3744, uid=10008, userID:0
,W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3744): enableAppOperation()+
D/SyncApplication( 3744): enableAppOperation()-
D/HTCUtilities( 3744): isNeorSinged() + 
,D/HTCUtilities( 3744): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3744): isNeorSinged() return false
,D/CDMountReceiver( 3744): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3744): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3744): enable CD Auto-mount: true
,D/DotMatrix( 1536): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3744): enable auto-mount
,D/HTCUtilities( 3744): enable auto-mount
,I/RemoteViews( 1110): com.nero.android.htc.sync (false,0)
I/ActivityManager(  911): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  911): Resuming delayed broadcast
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41bf91a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1110): com.nero.android.htc.sync 1 12 3 11
,I/RemoteViews( 1110): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41e8def0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3362): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(425c5b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
I/ActivityManager(  911): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  911): releaseWL(425c5b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3184
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3184:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3184
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
D/PMS     (  911): acquireWL(42647d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(42647d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426819e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(426819e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4269e060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,D/PMS     (  911): acquireWL(42648020): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3618 10074 null
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/Finsky  ( 3618): [388] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/PMS     (  911): releaseWL(4269e060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/PMS     (  911): releaseWL(42648020): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): releaseWL(425ef980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3618): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3618/10074)
,I/Icing   ( 1961): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1961): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1961): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  911): releaseWL(425b3868): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GAV2    ( 3553): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 7 times.
,I/SensorManager(  911): mEventCount = 750
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/CheckinService( 1961): Done disabling old GoogleServicesFramework version
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/GAV4    ( 3663): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1486): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1486): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  911): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3774 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3774): onCreate
D/ProviderChangeReceiver( 3774): ---------------------------------------------------
,D/ProviderChangeReceiver( 3774): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3774): start to updateAlertNotification!
,I/ActivityManager(  911): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3788 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=3459
,I/ActivityManager(  911): Killing 3459:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 3774): No fired or scheduled alerts
,D/HtcAlertUtils( 3774): -- cancelReminderNotification --
,D/HtcAlertUtils( 3774): broadcastExistReminder!
I/ActivityManager(  911): Recipient 3459
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3788): [3788/3788] onCreate()
W/ContextImpl( 3788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  911): killProcessQuiet, pid=3492
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3492:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3492
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{425a8898 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 8 times.
,I/SensorManager(  911): mEventCount = 900
,D/PMS     (  911): acquireWL(42530a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42530a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 9 times.
,D/AutoSetting( 1296): service - handleMessage() stop self
,D/AutoSetting( 1296): service - handleMessage() quit looper
,D/AutoSetting( 1296): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=3513
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3513:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3513
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  911): mEventCount = 1050
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 10 times.
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): acquireWL(4263a448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{421b19e8: PendingIntentRecord{41e78e68 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81543, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{425ce0f0: PendingIntentRecord{42510ab8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457092595562, Int=0
D/PMS     (  911): releaseWL(4263a448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3618): [377] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3618): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 11 times.
,I/SensorManager(  911): mEventCount = 1200
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(427f69d0): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427f69d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 12 times.
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1486): Don't start project servcice
,D/HtcModeClient( 1486): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1486): connectState: CONNECTION_READY = false
,D/SilentMusic( 1486): call stop
,D/HtcModeClient( 1486): close connection
,W/HtcModeClient( 1486): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1486): read the terminate packet, so break
,D/Process (  911): killProcessQuiet, pid=3199
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3199:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3199
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  911): mEventCount = 1350
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3805 uid=10078 gids={50078}
,D/PMS     (  911): acquireWL(4265ed10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10078}
,V/AlarmManager(  911): sending alarm PendingIntent{41aa3b98: PendingIntentRecord{41aacdd0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457092614186, Int=60000,
,D/PMS     (  911): releaseWL(4265ed10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3805): SMSBackupAgentService started
,D/SMSBackup( 3805): Checking restore status
,D/SMSBackup( 3805): Restore complete
,D/SMSBackup( 3805): cancelCheckAlarm
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/SMSBackup( 3805): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  911): killProcessQuiet, pid=3421
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3421:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3421
,V/LightsService(  911): setLight #0: color=#25
,V/LightsService(  911): setLight #0: color=#22
,V/LightsService(  911): setLight #0: color=#1b
,V/LightsService(  911): setLight #0: color=#15
,V/LightsService(  911): setLight #0: color=#14
,D/PMS     (  911): acquireWL(425f82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=100760, Int=0
,D/PMS     (  911): releaseWL(425f82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1110): now=1457092620060 next=59940
,I/SensorManager(  911): mEventCount = 1500
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4212d1e8
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  911): pid=911, uid=1000
,W/SensorService(  911): Active sensors: size = 2
,W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4212d1e8, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ae9058
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@4227b310
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  911): mWirelessDisplayManager is null
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 345ms
,W/PnPMgr  (  352): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
D/NfcService( 1232): applyRouting -2
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  911): OOBE c monitor 11
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=1249
D/PMS     (  911): acquireWL(41ebe788): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4265b628)
V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/PMS     (  911): releaseWL(41ebe788): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  911): acquireWL(41d9d998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMN     (  911): wakingUp
I/WindowManager(  911): No lock screen! windowToken=null
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMN     (  911): onScreenOn
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(41d9d998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
I/HtcPowerSaver(  911): << updateStatus
D/NfcService( 1232): applyRouting - 0
D/WifiNative-wlan0(  911):    returned false
,D/NfcService( 1232): applyRouting -2
,D/MtpService( 2153): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2153): [MTP][onReceive]-
D/PMS     (  911): acquireWL(4235eef0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  911): releaseWL(4235eef0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockThread( 1110): stop update clock
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3825 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  911): [LedInfo] has indicator attribute
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  911): updateScreenOn: false
,W/ContextImpl( 3825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  911): acquireWL(41f19f80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41f19f80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42572200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42572200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42597410): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3825 1000 null
,D/SmartSyncUtils( 3825): isEpsOn(), nState = 0
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ae9058
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ae9058, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@4227b310
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
D/PMS     (  911): acquireWL(423e4710): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,I/FeedHostManager( 1249): [onPause]
,I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cb69d8
I/SocialFeedProvider( 1249): +onPause
,I/SocialFeedProvider( 1249): -onPause
D/PMS     (  911): releaseWL(42597410): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20120 mDataStallAlarmIntent=null
I/AlarmManager(  911): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  911):    returned false
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(424a6888): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(424a6888): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  911): releaseWL(423e4710): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/SmartSyncUtils( 3825): getMobilePolicyEnabled, result = true
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1296): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1296): service - onCreate()
D/TetherSettings( 3326): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3326): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3326): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3326): Cust_ConnectToPC   : spcsc>false
D/        ( 3326): Cust_ConnectToPC   : IPT>true
D/        ( 3326): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3326): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3326): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3326): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3326): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3326): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3326): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3326): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3326):  defaultType:0
,D/AutoSetting( 1296): service - AddressCache: using context: com.htc.Weather
,W/ContextImpl( 3326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1296): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  911): request 424bfa50 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
,I/PhoneStatusBar( 1110): removeHeadsNotification.gc: 52
,D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3825): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3825): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3825): getMobilePolicyEnabled, result = true
D/PMS     (  911): acquireWL(42666df0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42666df0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(425c6d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4227b310
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4227b310, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4227b310, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4227b310
D/PMS     (  911): releaseWL(425c6d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f7af18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f7af18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  911): killProcessQuiet, pid=3402
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3402:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3402
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1296): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1296): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1296): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4266cff8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(42756550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42756550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(427e47d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42641338: PendingIntentRecord{42676b58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120958, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{41f22b78: PendingIntentRecord{425e0778 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135770, Int=0
,D/PMS     (  911): acquireWL(427ae108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,D/AutoSetting( 1296): service - handleMessage() stop self
,D/AutoSetting( 1296): service - handleMessage() quit looper
,D/AutoSetting( 1296): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=3540
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3540:com.htc.updater/u0a85 (adj 15): empty #17
,D/PMS     (  911): releaseWL(427ae108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427e47d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Recipient 3540
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/PMS     (  911): acquireWL(42664b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{421b19e8: PendingIntentRecord{41e78e68 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141555, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{41c1e1c0: PendingIntentRecord{424816f0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141562, Int=0
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  911): [NET] getaddrinfo_proxy-
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(4263bc50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(42664b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): releaseWL(4263bc50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(425e5900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160759, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425e5900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(425e1c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425e1c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(42693ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42693ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4263ece8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42688f80: PendingIntentRecord{42676b58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=180804, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{421b19e8: PendingIntentRecord{41e78e68 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201571, Int=0
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/PMS     (  911): releaseWL(4263ece8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): acquireWL(4267ba70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,D/PMS     (  911): acquireWL(427e5d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4267ba70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427e5d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4266b390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(4266b390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42662388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): acquireWL(425ae200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1457092721118 tag=VacuumService
D/PMS     (  911): releaseWL(42662388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425ae200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4267da78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(4267da78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427ba9b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1349 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1349/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(427ba9b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42687e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42687e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(4279c568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4279c568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(42759a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=280760, Int=0
,D/PMS     (  911): releaseWL(42759a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(42631550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(42631550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(425e9490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=340760, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425e9490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(42629630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(42629630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(42763950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=400760, Int=0
,D/PMS     (  911): releaseWL(42763950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(42720f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42720f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4271e188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=460760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4271e188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(427134e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427134e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(425af100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=520760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425af100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4262c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4262c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4262dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=580760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4262dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42730650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42730650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1217): sku_id=99
D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/Process (  911): killProcessQuiet, pid=2465
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2465:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2465
,D/PMS     (  911): acquireWL(4268e070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=640760, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4268e070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(42752a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42752a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42754378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=700760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42754378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427360b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427360b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42737ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=760760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42737ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42767dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42767dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(427696c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=820760, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(427696c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427aac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427aac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(427ac548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=880760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(427ac548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(425ab9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425ab9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1536): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1536): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(427954a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427954a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42796da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=940759, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42796da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3618): [NET] getaddrinfo-,err=8
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(425a5d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425a5d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(425a7670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1000760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425a7670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427295a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  911): sending alarm PendingIntent{41d62e20: PendingIntentRecord{42421a48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781200, Int=0
,D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3873 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{42558040: PendingIntentRecord{423c3268 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457092730073, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{4227f618: PendingIntentRecord{4266a100 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457092863648, Int=1800000
,V/AlarmManager(  911): sending alarm PendingIntent{4258a150: PendingIntentRecord{425fc278 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457093450481, Int=900000
,V/AlarmManager(  911): sending alarm PendingIntent{41f3d528: PendingIntentRecord{4264a938 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457093524985, Int=0
,D/PMS     (  911): acquireWL(427d0448): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427a1b08): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  911): releaseWL(427d0448): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 3825): call getInstance()
,D/SmartSyncUtils( 3825): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3825): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 3825): [updateNmRange] bManual = false
D/PMS     (  911): acquireWL(427a60a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3825 1000 null
,D/PMS     (  911): releaseWL(427295a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 3825): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3825): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3825): SettingOnTime = 1457157600000, randomSettingOnTime = 1457155546000
D/SmartSyncScreenOnOffTimeReceiver( 3825): SettingOffTime = 1457143200000, randomSettingOffTime = 1457143459000
I/EventLogService( 1961): Aggregate from 1457091063595 (log), 1457091063595 (data)
D/SmartSyncScreenOnOffTimeReceiver( 3825): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3825): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3825): bNightModeTurnOffOnce = false
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(427a60a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (3873/10049)
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023850
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024089
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024091
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024095
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025381
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025395
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028075
,D/PMS     (  911): releaseWL(427a1b08): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=3663
,I/ActivityManager(  911): Killing 3663:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3663
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42816b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42816b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(427b77f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1060759, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(427b77f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427b5b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427b5b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(427b38a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1120759, Int=0
,D/PMS     (  911): releaseWL(427b38a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4276e638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4276e638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4273feb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1180760, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4273feb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4264d448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4264d448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(42614700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41e84128: PendingIntentRecord{41f8fee8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1240760, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42614700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3618): [NET] getaddrinfo-,err=8
D/libc    ( 3618): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3618): [NET] getaddrinfo-, 1
,D/libc    ( 3618): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3618): [NET] getaddrinfo_proxy-
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3894): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3894): ====startRecUseTime====
D/htc.customization.log.level( 3894):  is 
W/CustomizationLogLevel( 3894): Level value is invalid, use default level 2
D/CustomizationManager( 3894):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3894): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3894): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3894): Parsing tag category name = system
I/CustomizationCIDLoader( 3894): Parsing tag category name = application
I/CustomizationCIDLoader( 3894): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3894): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3894): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3894): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3894): Parsing tag category name = Settings
D/CustomizationManager( 3894):  Read CID file spent 0.092 (s)
D/CustomizationManager( 3894):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 3894): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3894): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3894): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3894): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=3894, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  911): Skipping PackageSetting{42113090 com.example.hello/10397} due to missing metadata
W/PackageSettings(  911): Skipping PackageSetting{4211d1e8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  911): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  911): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1536): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1536): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1536): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1312): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): acquireWL(42852be8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42852be8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
W/AccTypeManager( 1312): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1312): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
E/ExternalAccountType( 1312): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3908 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  911): Unable to load service info ResolveInfo{427b3f78 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 3908): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3908): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3908): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3908): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3908): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3908): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3908): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3908): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3908): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3908): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3908): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3908): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3908): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3908): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3908): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3908): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3908): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3908): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3908): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3908): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3908): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3908): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3908): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3908): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3908): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3908): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3908): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3908): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3908): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3908): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3908): Opened ClientFlag.db in read-only mode
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
E/SQLiteDatabase( 3908): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3908): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3908): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3908): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3908): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3908): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3908): threadid=11: thread exiting with uncaught exception (group=0x41677e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 3908): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3908): Process: com.google.android.apps.docs, PID: 3908
E/AndroidRuntime( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3908): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3908): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3908): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3908): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3908): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
E/SQLiteDatabase( 3908): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3908): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3908): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3908): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3908): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3908): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3908): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3908): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3908): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3908): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3908): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3908): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3908): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3908): Opened ClientFlag.db in read-only mode
D/Process ( 3908): killProcess, pid=3908
D/Process ( 3908): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3925 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  911): Recipient 3908
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 3908) has died.
W/ContextImpl( 3925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 3925): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 3925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 3925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3925): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3925): threadid=10: thread exiting with uncaught exception (group=0x41677e30)
E/AndroidRuntime( 3925): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3925): Process: com.android.keychain, PID: 3925
E/AndroidRuntime( 3925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 3925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 3925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3925): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3940 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 3925): killProcess, pid=3925
D/Process ( 3925): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457093787007.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
I/ActivityManager(  911): Recipient 3925
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.android.keychain (pid 3925) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 3940): getInstance(Context context)
D/AppTag  ( 3940): getInstance(Context context)
D/AppTag  ( 3940): onCreate()
D/PMS     (  911): acquireWL(4275c2e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3591 10160 null
D/PMS     (  911): releaseWL(4275c2e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  911): killProcessQuiet, pid=3213
W/dalvikvm( 3618): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  911): Killing 3213:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1961): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1961): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 1961): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 1961): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 1961): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1961): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1961): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 1961): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1961): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1961): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 1961): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/ActivityManager(  911): Recipient 3213
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/GMPM-SVC( 1961): App measurement is starting up, version: 8489
I/GMPM-SVC( 1961): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1961): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1961): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6ce574a0
W/dalvikvm( 1961): threadid=37: thread exiting with uncaught exception (group=0x41677e30)
E/SQLiteDatabase( 1961): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
E/SQLiteOpenHelper( 1961): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1961): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1961): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1961): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1961): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1961): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1961): Process: com.google.android.gms, PID: 1961
E/AndroidRuntime( 1961): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 1961): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1961): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1961): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1961): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1961): killProcess, pid=1961
D/Process ( 1961): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/PMS     (  911): acquireWL(427cb228): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Recipient 1961
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms (pid 1961) has died.
D/PMS     (  911): handleWLDeath(427cb228): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10996ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 20994ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 30993ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 40992ms

```
