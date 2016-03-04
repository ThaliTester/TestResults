#### Test 61432979f791f6f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3388 uid=10081 gids={50081, 5001, 1028, 1015}
--------- beginning of /dev/log/main
D/Process (  906): killProcessQuiet, pid=3180
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3180:com.htc.stock/u0a82 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3180
I/SoundPicker( 3388): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3388): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3388): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3388): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3388): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3388): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  906): releaseWL(426ca428): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1319): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AccTypeManager( 1319): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1319): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/dalvikvm-heap( 1250): Grow heap (frag case) to 13.195MB for 53840-byte allocation
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1250): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/SystemReader( 1227): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/Prism.ItemManager( 3204): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3204): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/ExternalAccountType( 1319): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
E/cutils-trace( 3400): Error opening trace file: No such file or directory (2)
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/CustomizationManager( 3400): ====startRecUseTime====
D/htc.customization.log.level( 3400):  is 
W/CustomizationLogLevel( 3400): Level value is invalid, use default level 2
D/CustomizationManager( 3400):  Read ACC file spent 0.087 (s)
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3400): Parsing tag item name = HTC__031
D/Process (  906): killProcessQuiet, pid=3192
V/CustomizationCIDLoader( 3400): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3400): Parsing tag category name = system
I/CustomizationCIDLoader( 3400): Parsing tag category name = application
I/CustomizationCIDLoader( 3400): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3400): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3400): Parsing tag category name = AudioService
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/CustomizationCIDLoader( 3400): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3400): Parsing tag category name = Settings
D/CustomizationManager( 3400):  Read CID file spent 0.146 (s)
D/CustomizationManager( 3400):  All configurations done spent 0.146 (s)
I/ActivityManager(  906): Killing 3192:com.htc.stock:remote/u0a82 (adj 15): empty #17
W/HtcNativeFlag( 3400): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3400): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3400): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3400): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): Recipient 3192
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
D/DFPI.PIReciver( 3151): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3151): onHandleIntent
I/DFPI.ApkInstallService( 3151): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3151): check CID = HTC__032
I/DFPI.ApkInstallService( 3151): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3400
,W/PackageManager(  906): Unable to load service info ResolveInfo{427c4368 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  906): acquireWL(42813528): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42813528): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(4281d158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4281d158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4281f990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42820478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42820478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4281f990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  906): mEventCount = 450
I/HtcModeClient( 1502): handler message = 4011
E/HtcModeClient( 1502): Check connection and retry 5 times.
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3095
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/ActivityManager(  906): Killing 3095:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b4fe50 +
I/Prism.WidgetManager( 1250): onLoadItems() +
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3388): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3388): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3388): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3388): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  906): Recipient 3095
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/Prism.ItemManager( 3204): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3204): loadItems() com.htc.launcher.pageview.WidgetManager@41b356f0 +
,I/Prism.WidgetManager( 3204): onLoadItems() +
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/Prism.WidgetManager( 1250): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1250): onLoadItems() -
,I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b4fe50 -
,I/Prism.WidgetManager( 3204): onLoadItems() -
,I/Prism.ItemManager( 3204): loadItems() com.htc.launcher.pageview.WidgetManager@41b356f0 -
,D/AutoSetting( 1301): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1301): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3422 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3151): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Resuming delayed broadcast
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
I/DFPI.ApkInstallService( 3151): onHandleIntent
,I/DFPI.ApkInstallService( 3151): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3151): check CID = HTC__032
,I/DFPI.ApkInstallService( 3151): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/PhoneApp( 1217): -- N3 =0
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3422): [ NA ]- onCreate()
,I/EASAppSvc( 3422): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3165): put()
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3422/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3422/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3422/10064)
,I/EASAppSvc( 3422): [ NA ]- onDestroy()
I/EASAppSvc( 3422): [ NA ]> uninitEASService
I/EASRequestController( 3422): [ NA ]release
I/EASAppSvc( 3422): [ NA ]< uninitEASService
I/EASAppSvc( 3422): [ NA ]- onCreate()
,I/EASAppSvc( 3422): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3422/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3422/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3422/10064)
,D/ORMLib  ( 3165): put()
,I/EASAppSvc( 3422): [ NA ]- onDestroy()
,I/EASAppSvc( 3422): [ NA ]> uninitEASService
,I/EASRequestController( 3422): [ NA ]release
,I/EASAppSvc( 3422): [ NA ]< uninitEASService
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3454 uid=10068 gids={50068, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3109
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3109:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3109
,D/ORMLib  ( 3165): put()
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3204
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3204:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3388): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3388): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3388): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3388): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content:,//media/internal/audio/media/262 type=2
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3342): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3204
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1250): +disConnect socialManager
,I/SocialFeedProvider( 1250): disconnect socialManager
,I/SocialFeedProvider( 1250): -disConnect socialManager
,I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3477 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{41c217d0: PendingIntentRecord{424cfdf8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457078829568, Int=0
,I/ImageRamCache( 3477): create image Cache, size: 31457280.
I/ImageRamCache( 3477): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3477): create image Cache, size: 12582912.
,I/FeedSettings( 3477): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3477): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3477): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3477): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3477): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3477): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3477): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3477): last commit ulog time 1457013622347
,I/SocialManager[SocialBiLogHelper]( 3477): skip commit this time
,V/AlarmManager(  906): sending alarm PendingIntent{42693340: PendingIntentRecord{4266ab28 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457078829749, Int=0
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3151): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3151): onHandleIntent
,I/DFPI.ApkInstallService( 3151): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3151): check CID = HTC__032
,I/DFPI.ApkInstallService( 3151): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{424ad2f8 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3388): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3388): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3388): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3388): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3388): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3388): MODE_GSM access default DB
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3388): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3388): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3388): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3388): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3342): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  906): killProcessQuiet, pid=3220
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(425fcc20): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1502 10014 null
,I/ActivityManager(  906): Killing 3220:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TelephonyReceiver( 1217): bind: false
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Recipient 3220
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3499 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  906): releaseWL(425fcc20): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3512 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3234
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3234:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3234
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 3247): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,W/GAV2    ( 3512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  906): acquireWL(425345f8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425345f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  906): acquireWL(4280b310): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 3247): Storage manager: low false usage 2.10MB avail 8.76GB capacity 9.23GB
,W/dalvikvm( 3247): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,I/Gmail   ( 3512): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3512): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3512): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3512): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1109): com.htc.updater (true,33751552)
,D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c402d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1109): com.htc.updater 1 6 0 10
I/RemoteViews( 1109): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e7b380 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.htc.updater 1 5 0 10
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(425c1f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3551 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Icing   ( 3247): updateResources: need to parse f{com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  906): releaseWL(425c1f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 3551): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3551): MmsConfig.loadMmsSettings
,W/dalvikvm( 3551): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3551): VFY: unable to resolve instance field 36
,W/dalvikvm( 3551): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3551): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2437): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2437): query uri: content://htc-mms-customization/mms-ua/ua_profile,
I/Babel   ( 3551): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3551): MmsConfig.loadFromDatabase
,E/Babel   ( 3551): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3551): MmsConfig.loadFromResources
,E/Babel   ( 3551): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3551): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3551, uid=10111, userID:0
,W/Settings( 3551): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3551, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3551, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3551, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3551, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3551, uid=10111, userID:0
D/PMS     (  906): acquireWL(42596328): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3551 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3551): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 3247): Internal init done: storage state 0
,I/Icing   ( 3247): Post-init done
,D/PMS     (  906): releaseWL(42596328): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(41e9d678): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3551 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(4280b310): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3284
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3284:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Recipient 3284
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
D/WifiService(  906): Client connection lost with reason: 4
,I/IcingCorporaProvider( 2551): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/PMS     (  906): releaseWL(41e9d678): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=2847
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2847:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2847
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3593 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  906): acquireWL(423289e0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423289e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42568ed8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42568ed8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(421c7550): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(421c7550): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(420224d8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(41f4ae58): PARTIAL_WAKE_LOCK  AsyncService 0x1 3593 10160 null
,D/PMS     (  906): releaseWL(41f4ae58): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): acquireWL(4251d9e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3593 10160 null
,I/ActivityManager(  906): Delaying start of: ServiceRecord{41f39e60 u0 com.google.android.apps.plus/.service.FingerprintScannerIntentService}
,D/PMS     (  906): releaseWL(420224d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4241a898): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42327dd0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3593 10160 null
,D/PMS     (  906): releaseWL(4251d9e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3593/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3593/10160)
,D/PMS     (  906): releaseWL(4241a898): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424ac5d0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424ac5d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41e14bd0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41e14bd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424e7f88): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424e7f88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42327dd0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=3619 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  906): acquireWL(424abe58): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424abe58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 6 times.
,D/PMS     (  906): acquireWL(426acb20): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426acb20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/HtcFingerPrintQuickLaunchProvider( 3619): -onCreate()
,V/Settings:HtcSettingsApplication( 3619): [3619/3619] onCreate()
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3634 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2604
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2604:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2604
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2551): UpdateCorporaTask done [took 607 ms] updated apps [took 607 ms] 
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3619): id/is att sku: 99/false
D/PMS     (  906): acquireWL(4259d828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3634, uid=10074, userID:0
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4259d828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,W/SystemReader( 3619): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/Finsky  ( 3634): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/SystemReader( 3619): Cannot find support_harman, use default value instead
,W/SystemReader( 3619): Cannot find effect_manager_id, use default value instead
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3634/10074)
,E/Settings:HtcWrapHeaderInfo( 3619): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3619): The wrap header doesn't exist in header list.
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/Settings:HtcWrapHeaderInfo( 3619): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3619): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]support         :false
,W/FingerprintManager( 3619): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3619): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3619): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3634/10074)
,D/Finsky  ( 3634): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,W/Settings( 3634): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3634): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3619): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3619): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3619): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportRecentAppsButton]support         :false
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3619): [supportHomeButton]support         :false
,W/FingerprintManager( 3619): hasFingerprint() - sSensorCode = 0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3634, uid=10074, userID:0
,E/Settings:HtcVoWifiWidgetEnabler( 3619): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3619): Failed to find provider info for com.htc.vowifi
,D/Finsky  ( 3634): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3634): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 3634): Skipping gmscore version check
,D/Finsky  ( 3634): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3634): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 3634): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  906): killProcessQuiet, pid=3306
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3306:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,D/PackageBroadcastService( 3247): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/PMS     (  906): acquireWL(425bb288): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3551 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(425bb288): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/PMS     (  906): acquireWL(4272be68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  906): acquireWL(426a3c20): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(4272be68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426a3c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(425fdd70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/PMS     (  906): acquireWL(427e20b8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
I/ActivityManager(  906): Recipient 3306
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(425fdd70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 3247): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 3247): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 3247): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 3247): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 3247): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 3247): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 3247): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=3247, uid=10029, userID:0
,I/PeopleDatabaseHelper( 3247): cleanUpNonGplusAccounts done.
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3247/10029)
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42808570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42808570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427e7550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  906): acquireWL(427da240): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427da240): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,W/InstanceID/Rpc( 3247): Found 10029
D/PMS     (  906): releaseWL(427e7550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42698df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42698df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41efe1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(41efe1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42416bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  906): acquireWL(42349c18): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3165 10071 null
,D/PMS     (  906): acquireWL(421a5090): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3165 10071 null
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,I/ActivityManager(  906): Delay finish: com.htc.task/.notification.NotifyReceiver
,E/TodoTaskNotifyService( 3165): java.lang.NullPointerException
,W/System.err( 3165): java.lang.NullPointerException
W/System.err( 3165): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3165): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3165): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3165): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): releaseWL(42349c18): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/NotifyReceiver( 3165): stopSelfResult true
D/PMS     (  906): releaseWL(421a5090): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(42416bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/LocationInitializer( 3247): Restart initialization of location
,D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,E/MDM     ( 1200): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  906): acquireWL(42400d28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42400d28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(425cbfb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/PMS     (  906): releaseWL(425cbfb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/WSP     ( 1301): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1301): Weather sync is On
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,I/WSP     ( 1301): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 10:07:13 CET 2016
,W/WSP     ( 1301): [Receiver] can't get active network info
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/WSP     ( 1301): [SyncService] no data connection, stop sync service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
,W/MediaManager( 3325): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(4257e1b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3551 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(4257e1b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2551): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/Finsky  ( 3634): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3634): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  906): sending alarm PendingIntent{42697038: PendingIntentRecord{423a2de0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457078833715, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/dalvikvm( 3247): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 3247): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3634): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3634): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,I/IcingCorporaProvider( 2551): UpdateCorporaTask done [took 221 ms] updated apps [took 221 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(427dae60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3593 10160 null
,D/PMS     (  906): releaseWL(427dae60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 3247): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3247): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/Icing   ( 3247): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 3247): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 3247): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3247): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/MediaManager( 3325): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3634): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/TodoTaskshortcut( 3165): update TASK shortcut>
,D/Finsky  ( 3634): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,D/Finsky  ( 3634): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
V/AlarmManager(  906): sending alarm PendingIntent{424756c8: PendingIntentRecord{426814e8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1457078834205, Int=0
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 3634): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3634): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/Icing   ( 3247): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 3247): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(427e20b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3325): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(424deae8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3342 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3342): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3342, uid=10154, userID:0
,I/MusicLeanback( 3342): Conditions not met for autocaching.
,I/MusicLeanback( 3342): Stop autocaching.
D/PMS     (  906): releaseWL(424deae8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 3342): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3732 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3732): Loading default preferences
,W/Resources( 3732): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 3732): Overriding preferences with custom values
,D/SyncApplication( 3732): Updating preferences succeeded
,E/SyncApplication( 3732): Application created.
D/VolumeInfo( 3732): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3732): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3732): Found 0 mount point(s)
,V/VolumeInfo( 3732): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3732): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3732): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3732): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3732): getNewCalendarAuthority()...
,D/SyncApplication( 3732): enableAppOperation()+
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3732, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3732, uid=10008, userID:0
,W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3732): enableAppOperation()-
D/HTCUtilities( 3732): isNeorSinged() + 
,D/HTCUtilities( 3732): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3732): isNeorSinged() return false
,D/CDMountReceiver( 3732): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3732): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 3732): enable CD Auto-mount: true
,I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 3732): enable auto-mount
D/HTCUtilities( 3732): enable auto-mount
,I/RemoteViews( 1109): com.nero.android.htc.sync (false,0)
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c08b00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
I/RemoteViews.Performance( 1109): com.nero.android.htc.sync 1 14 3 11
I/RemoteViews( 1109): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e92e78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3325): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3136
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3136:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3136
,D/PMS     (  906): acquireWL(42515d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42515d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424ffcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(424ffcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427bbbb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): acquireWL(427e92d8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3634 10074 null
,D/Finsky  ( 3634): [387] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/PMS     (  906): releaseWL(427bbbb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,D/PMS     (  906): releaseWL(427e92d8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(426111b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3634): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (3634/10074)
,I/GAV2    ( 3512): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 3247): Google Analytics 8.4.89 is starting up.
,I/GAV4    ( 3551): Thread[GAThread,5,main]: No campaign data found.
,I/SensorManager(  906): mEventCount = 600
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 7 times.
,D/Process (  906): killProcessQuiet, pid=3422
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3422:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3422
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/CalendarProvider2( 1502): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1502): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3766 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3766): onCreate
D/ProviderChangeReceiver( 3766): ---------------------------------------------------
,D/ProviderChangeReceiver( 3766): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3766): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3780 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3454
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3454:com.htc.task.gtask/u0a68 (adj 15): empty #17
,D/AlertService( 3766): No fired or scheduled alerts
,D/HtcAlertUtils( 3766): -- cancelReminderNotification --
,D/HtcAlertUtils( 3766): broadcastExistReminder!
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3454
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3780): [3780/3780] onCreate()
W/ContextImpl( 3780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=3477
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3477:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3477
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42675fe0 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  906): acquireWL(427bc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427bc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 8 times.
,I/SensorManager(  906): mEventCount = 750
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 9 times.
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - onDestroy() END
,I/ActivityManager(  906): Killing 3151:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3151
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1301): service - handleMessage() quit looper
,I/ActivityManager(  906): Recipient 3151
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 10 times.
,D/PMS     (  906): acquireWL(425d2c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
V/AlarmManager(  906): sending alarm PendingIntent{421af058: PendingIntentRecord{422f9070 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=83164, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41b18b88: PendingIntentRecord{425bae50 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457078848892, Int=0
,D/PMS     (  906): releaseWL(425d2c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3634): [377] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  906): mEventCount = 900
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(424633e0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424633e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4232bfd0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4232bfd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(41e359c8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41e359c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425158b0): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425158b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423fddd8): PARTIAL_WAKE_LOCK  Icing 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423fddd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(41d6a790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41d6a790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 12 times.
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1502): Don't start project servcice
,D/HtcModeClient( 1502): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1502): connectState: CONNECTION_READY = false
,D/SilentMusic( 1502): call stop
D/HtcModeClient( 1502): close connection
,W/HtcModeClient( 1502): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1502): read the terminate packet, so break
,D/Process (  906): killProcessQuiet, pid=3388
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3388:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3388
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  906): mEventCount = 1050
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3801 uid=10078 gids={50078}
,D/PMS     (  906): acquireWL(42383268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10078}
,V/AlarmManager(  906): sending alarm PendingIntent{42612c50: PendingIntentRecord{4257fd20 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457078868037, Int=60000
D/PMS     (  906): releaseWL(42383268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3801): SMSBackupAgentService started
,D/SMSBackup( 3801): Checking restore status
,D/SMSBackup( 3801): Restore complete
,D/SMSBackup( 3801): cancelCheckAlarm
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,D/SMSBackup( 3801): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/Process (  906): killProcessQuiet, pid=3499
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3499:com.htc.updater/u0a85 (adj 15): empty #17
V/LightsService(  906): setLight #0: color=#25
,I/ActivityManager(  906): Recipient 3499
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  906): setLight #0: color=#22
,V/LightsService(  906): setLight #0: color=#1b
,V/LightsService(  906): setLight #0: color=#15
,V/LightsService(  906): setLight #0: color=#14
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421237b8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421237b8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6e280
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42481508
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
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/NfcService( 1227): ScreenObserver: OFF
,D/NfcService( 1227): applyRouting - 0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42670920)
,D/NfcService( 1227): applyRouting -2
I/InputMethodManagerService(  906): Disable input method client, pid=1250
D/PMS     (  906): acquireWL(425ae948): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1227 1027 null
D/PMN     (  906): wakingUp
,D/PMS     (  906): releaseWL(425ae948): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/PMS     (  906): acquireWL(42353980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(42353980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/MtpService( 2140): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2140): [MTP][onReceive]-
,D/NfcService( 1227): applyRouting - 0
,D/NfcService( 1227): applyRouting -2
,D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(42805968): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1227 1027 null
D/PMS     (  906): releaseWL(42805968): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1301): service - onCreate()
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
I/ClockThread( 1109): stop update clock
D/AutoSetting( 1301): service - AddressCache: using context: com.htc.Weather
,D/WifiNative-wlan0(  906):    returned false
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3619): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/        ( 3619): Cust_ConnectToPC   : Internet_Sharing>true
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/LocationManagerService(  906): request 4235f238 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/        ( 3619): Cust_ConnectToPC   : Modem_Link>false
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/        ( 3619): Cust_ConnectToPC   : spcsc>false
D/        ( 3619): Cust_ConnectToPC   : IPT>true
,D/        ( 3619): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3619): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3619): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3619): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3619): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/NetworkPolicy(  906): updateScreenOn: false
,I/PSReceiver( 3619): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3619): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3619): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3619):  defaultType:0
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425d3c08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425d3c08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3828 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(42657ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42657ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6e280
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6e280, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42481508
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
,I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421b7fb8
I/SocialFeedProvider( 1250): +onPause
,I/SocialFeedProvider( 1250): -onPause
D/PMS     (  906): acquireWL(426806b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=21751 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906):    returned false
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: false
D/PMS     (  906): acquireWL(426950a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(426950a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  906): releaseWL(426806b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/PMS     (  906): acquireWL(425d7580): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3828 1000 null
,D/SmartSyncUtils( 3828): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(425d7580): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/PhoneStatusBar( 1109): removeHeadsNotification.gc: 55
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3828): getMobilePolicyEnabled, result = true
,W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3828): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3828): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3828): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/PMS     (  906): acquireWL(426c56b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42481508
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42481508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42481508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  906): releaseWL(426c56b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42481508
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42481a50 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42481a50 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  906): acquireWL(42692048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42692048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - mHandler: cancel location update
,D/AutoSetting( 1301): service -           changes count: 0
,D/PMS     (  906): acquireWL(4266b628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110629, Int=0
,D/PMS     (  906): releaseWL(4266b628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=3365
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3365:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3365
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{425dc248 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42694258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42694258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4256b2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4235e618: PendingIntentRecord{4251c1d0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123938, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{421c4238: PendingIntentRecord{426a2088 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136659, Int=0
,D/PMS     (  906): acquireWL(42689020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  906): releaseWL(42689020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4256b2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1301): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=2437
,I/ActivityManager(  906): Killing 2437:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 2437
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/PMS     (  906): acquireWL(427b41a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{421af058: PendingIntentRecord{422f9070 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=143179, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41c77ca8: PendingIntentRecord{423cd5f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143182, Int=0
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  906): [NET] getaddrinfo_proxy-
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(425ab7c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(427b41a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(425ab7c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(427cdef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427cdef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426a5ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426a5ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42682188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42682188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42685a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{41acf7a8: PendingIntentRecord{4251c1d0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=183506, Int=0
,D/PMS     (  906): acquireWL(427a0a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{421af058: PendingIntentRecord{422f9070 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=203202, Int=0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/PMS     (  906): releaseWL(42685a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4280fee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427a0a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4280fee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42629ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42629ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4260ad50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): acquireWL(42783cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1457078972884 tag=VacuumService
,D/PMS     (  906): releaseWL(4260ad50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42783cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42341a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42341a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4271c390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(4271c390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426781e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230628, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426781e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4271fef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4271fef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427214b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427214b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED,
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4272f510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4272f510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(427d0998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427d0998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(427d2290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=350629, Int=0
,D/PMS     (  906): releaseWL(427d2290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
,D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(427c5fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427c5fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427c78c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427c78c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42816730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42816730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428185f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=470628, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428185f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4281a848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4281a848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42711318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=530629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42711318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42713b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42713b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42715450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=590629, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42715450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427176a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427176a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1217): sku_id=99
D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/PMS     (  906): acquireWL(42614648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=650629, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42614648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(4264fe28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4264fe28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42651720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=710629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42651720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42653f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42653f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42655858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=770629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42655858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426b1be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426b1be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426b3aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=830629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b3aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426b5d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426b5d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426b75f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=890629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b75f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426b9850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426b9850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4262e498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950629, Int=0
,D/PMS     (  906): releaseWL(4262e498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(42779570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42779570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4277b858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41ca1898: PendingIntentRecord{423e0bc8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784131, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3869 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4234c940: PendingIntentRecord{42358cc0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457078983942, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42569280: PendingIntentRecord{424c7040 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457079081911, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{41f6a2e0: PendingIntentRecord{423f8e30 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457079704320, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{423d67e8: PendingIntentRecord{4268b1c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457079775989, Int=0
,D/PMS     (  906): acquireWL(42641be0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(42643640): PARTIAL_WAKE_LOCK  Event Log Service 0x1 3247 10029 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 3828): call getInstance()
,D/SmartSyncUtils( 3828): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(42641be0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 3828): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 3828): [updateNmRange] bManual = false
D/PMS     (  906): releaseWL(4277b858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42646bd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3828 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 3828): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3828): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3828): SettingOnTime = 1457157600000, randomSettingOnTime = 1457156386000
D/SmartSyncScreenOnOffTimeReceiver( 3828): SettingOffTime = 1457143200000, randomSettingOffTime = 1457143358000
,D/SmartSyncScreenOnOffTimeReceiver( 3828): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3828): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3828): bNightModeTurnOffOnce = false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (3869/10049)
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): releaseWL(42646bd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/EventLogService( 3247): Aggregate from 1457077281828 (log), 1457077281828 (data)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025548
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026178
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026183
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026185
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026190
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029275
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029289
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360032129
,D/PMS     (  906): releaseWL(42643640): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=3551
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3551:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3551
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4279f058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4279f058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42756488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42756488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4267c4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4267c4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4263c048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1070628, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4263c048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425e9a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e9a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425a7e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1130628, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425a7e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425091f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425091f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423edbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1190629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423edbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f4f860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f4f860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(41bf2cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4236fb40: PendingIntentRecord{42365190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1250629, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41bf2cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3634): [NET] getaddrinfo_proxy-
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3890): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3890): ====startRecUseTime====
D/htc.customization.log.level( 3890):  is 
W/CustomizationLogLevel( 3890): Level value is invalid, use default level 2
D/CustomizationManager( 3890):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3890): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3890): Parsing tag category name = system
I/CustomizationCIDLoader( 3890): Parsing tag category name = application
I/CustomizationCIDLoader( 3890): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3890): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3890): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3890): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3890): Parsing tag category name = Settings
D/CustomizationManager( 3890):  Read CID file spent 0.150 (s)
D/CustomizationManager( 3890):  All configurations done spent 0.151 (s)
W/HtcNativeFlag( 3890): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3890): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3890): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3890): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=3890, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{420cbc40 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{420cf8b0 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  906): acquireWL(4262d1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1319): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(4262d1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/AccTypeManager( 1319): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1319): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/SystemReader( 1227): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2551): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3904 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1319): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2551): UpdateCorporaTask done [took 151 ms] updated apps [took 150 ms] 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  906):   Scheme: "mmsto"
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 3904): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3904): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3904): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3904): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3904): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3904): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3904): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3904): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3904): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3904): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3904): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3904): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3904): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3904): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3904): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3904): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3904): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3904): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3904): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3904): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3904): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3904): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3904): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3904): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3904): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3904): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3904): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3904): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3904): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3904): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3904): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3904): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3904): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3904): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3904): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3904): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3904): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3904): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3904): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3904): threadid=11: thread exiting with uncaught exception (group=0x4168de30)
E/AndroidRuntime( 3904): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3904): Process: com.google.android.apps.docs, PID: 3904
E/AndroidRuntime( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3904): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3904): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3904): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3904): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3904): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 3904): killProcess, pid=3904
D/Process ( 3904): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3922 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 3904
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 3904) has died.
W/ContextImpl( 3922): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 3922): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3922): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3922): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3922): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3922): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3922): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 3922): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 3922): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3922): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3922): threadid=10: thread exiting with uncaught exception (group=0x4168de30)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3935 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 3922): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3922): Process: com.android.keychain, PID: 3922
E/AndroidRuntime( 3922): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3922): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3922): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3922): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3922): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 3922): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 3922): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3922): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 3922): killProcess, pid=3922
D/Process ( 3922): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/PackageManager(  906): Unable to load service info ResolveInfo{42053808 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457080040296.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3922
I/ActivityManager(  906): Process com.android.keychain (pid 3922) has died.
D/AppTag  ( 3935): getInstance(Context context)
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 3935): getInstance(Context context)
D/AppTag  ( 3935): onCreate()
D/PMS     (  906): acquireWL(426cbfa0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3593 10160 null
D/PMS     (  906): releaseWL(426cbfa0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b4fe50 +
I/Prism.WidgetManager( 1250): onLoadItems() +
D/Process (  906): killProcessQuiet, pid=3165
W/dalvikvm( 3634): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3165:com.htc.task/u0a71 (adj 15): empty #17
D/PackageBroadcastService( 3247): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 3247): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 3247): Reading stored module config
D/ChimeraCfgMgr( 3247): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3247): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 3247): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 3247): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3165
E/SQLiteDatabase( 3247): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3247): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3247): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3247): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3247): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3247): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3247): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3247): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3247): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3247): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3247): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 3247): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3247): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 3247): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 3247): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 3247): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3247): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3247): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3247): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3247): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3247): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 3247): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3247): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 3247): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 3247): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 3247): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 3247): App measurement is starting up, version: 8489
I/GMPM-SVC( 3247): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 3247): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3247): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 3247): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3247): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x65d4f658

```
