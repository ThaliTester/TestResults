#### Test 6136236661fd38c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
--------- beginning of /dev/log/system
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
I/ActivityManager(  908): Resuming delayed broadcast
D/Process (  908): killProcessQuiet, pid=3334
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/SoundPicker( 3515): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3515): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3515): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3515): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3515): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3515): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/ActivityManager(  908): Killing 3334:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  908): Recipient 3334
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/AutoSetting( 1306): service - mRequestRunnable: screen on delay 10s, request NLP now
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/AutoSetting( 1306): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1306): service - requestNLP() NetworkLocationProvider not enabled
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
E/cutils-trace( 3537): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3537): ====startRecUseTime====
D/htc.customization.log.level( 3537):  is 
W/CustomizationLogLevel( 3537): Level value is invalid, use default level 2
D/CustomizationManager( 3537):  Read ACC file spent 0.073 (s)
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3537): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3537): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3537): Parsing tag category name = system
I/CustomizationCIDLoader( 3537): Parsing tag category name = application
I/CustomizationCIDLoader( 3537): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3537): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3537): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3537): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3537): Parsing tag category name = Settings
D/CustomizationManager( 3537):  Read CID file spent 0.122 (s)
D/CustomizationManager( 3537):  All configurations done spent 0.123 (s)
W/HtcNativeFlag( 3537): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3537): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3537): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3537): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3537
W/PackageManager(  908): Unable to load service info ResolveInfo{426468f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3293): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  908): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3293): onHandleIntent
I/DFPI.ApkInstallService( 3293): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3293): check CID = HTC__032
I/DFPI.ApkInstallService( 3293): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/Prism.ItemManager( 3346): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3346): loadItems() com.htc.launcher.pageview.WidgetManager@41bd5bc8 +
I/Prism.WidgetManager( 3346): onLoadItems() +
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5eb8 +
I/Prism.WidgetManager( 1249): onLoadItems() +
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5eb8 -
,I/Prism.WidgetManager( 3346): onLoadItems() -
,I/Prism.ItemManager( 3346): loadItems() com.htc.launcher.pageview.WidgetManager@41bd5bc8 -
,V/AlarmManager(  908): sending alarm PendingIntent{427550f8: PendingIntentRecord{4277c750 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457013619534, Int=0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/SoundPicker( 3515): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3515): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3515): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3515): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3515): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3515): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/MediaStoreImporter( 3473): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoTaskReceiver
,D/PMS     (  908): acquireWL(42832870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42832870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(4283dc60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4283dc60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428408b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427c3a08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3557 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/PMS     (  908): releaseWL(428408b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427c3a08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3557): [ NA ]- onCreate()
,I/EASAppSvc( 3557): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3307): put()
,I/EASAppSvc( 3557): [ NA ]- onDestroy(),
,I/EASAppSvc( 3557): [ NA ]> uninitEASService
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3557/10064)
,I/EASRequestController( 3557): [ NA ]release
,I/EASAppSvc( 3557): [ NA ]< uninitEASService
,I/EASAppSvc( 3557): [ NA ]- onCreate()
,I/EASAppSvc( 3557): [ NA ]> onUpgrade: version = 63
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3557/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3557/10064)
,D/ORMLib  ( 3307): put()
,I/EASAppSvc( 3557): [ NA ]- onDestroy()
,I/EASAppSvc( 3557): [ NA ]> uninitEASService
,I/EASRequestController( 3557): [ NA ]release
,I/EASAppSvc( 3557): [ NA ]< uninitEASService
,I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3594 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver,
,D/DFPI.PIReciver( 3293): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  908): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3293): onHandleIntent
,I/DFPI.ApkInstallService( 3293): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3293): check CID = HTC__032
,I/DFPI.ApkInstallService( 3293): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/Process (  908): killProcessQuiet, pid=3234
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3234:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3234
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 3307): put()
,I/SensorManager(  908): mEventCount = 600
,I/SocialFeedProvider( 1249): +disConnect socialManager
,I/SocialFeedProvider( 1249): disconnect socialManager
,I/SocialFeedProvider( 1249): -disConnect socialManager
,I/ActivityManager(  908): Resuming delayed broadcast
,I/SoundPicker( 3515): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3515): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3515): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3515): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3515): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3515): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3515): MODE_GSM access default DB
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3515): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3515): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3515): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3515): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3473): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  908): killProcessQuiet, pid=3250
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3250:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/PMS     (  908): acquireWL(426e8430): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1499 10014 null
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/ActivityManager(  908): Recipient 3250
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(426e8430): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1217): bind: false
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3614 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  908): killProcessQuiet, pid=3362
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3362:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3362
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
,D/LocationInitializer( 1963): Restart initialization of location
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Delaying start of: ServiceRecord{426f2ce0 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,E/MDM     ( 1200): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  908): acquireWL(4264c738): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4264c738): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,V/AlarmManager(  908): sending alarm PendingIntent{425b3a70: PendingIntentRecord{41b591d8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457013621915, Int=0
I/SocialManager[SocialBiLogHelper]( 3346): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3346): last commit ulog time 1456906095494
I/SocialManager[SocialBiLogHelper]( 3346): do commit ulog
,I/ActivityManager(  908): Delaying start of: ServiceRecord{4264dda8 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,D/DotMatrix( 1556): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1109): com.htc.updater (true,33751552)
,D/NotificationService(  908): notification sound not played, stream=5 volume=0 always=false
V/SocialManagerService( 1306): getDataSources
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e67a48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/SocialManagerService( 1306): plugin added: com.facebook.auth.login
,I/SocialManagerService( 1306): plugin added: com.twitter.android.auth.login
,I/RemoteViews.Performance( 1109): com.htc.updater 2 12 1 10
,I/SocialManagerService( 1306): plugin added: com.htc.linkedin
I/SocialManagerService( 1306): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1306): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1306): plugin added: com.htc.drive.activator
I/SocialManagerService( 1306): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1306): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1306): plugin added: com.google
,I/SocialManagerService( 1306): device total memory: 1873M
,I/SocialManagerService( 1306): groupAccounts
,I/RemoteViews( 1109): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f4a138 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  908): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=3638 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/RemoteViews.Performance( 1109): com.htc.updater 1 9 0 10
,E/SocialManagerService( 1306): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1306): error when get process name! process name is null!
,E/SocialManagerService( 1306): skip binding the plugin without process namecom.htc.drive.activator
,I/SocialManagerService( 1306): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1306): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1306): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1306): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1306): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1306): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1306): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1306): add com.google to pending queue!
I/SocialManagerService( 1306): consume pending plugin session
,I/SocialManagerService( 1306): add com.facebook.auth.login to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.facebook.auth.login
,I/SocialManagerService( 1306): com.facebook.auth.login connecting, adding msg, has message?true
,I/SocialManagerService( 1306): add com.htc.linkedin to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.htc.linkedin
,I/SocialManagerService( 1306): com.htc.linkedin connecting, adding msg, has message?true
I/SocialManagerService( 1306): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.twitter.android.auth.login
,I/SocialManagerService( 1306): com.twitter.android.auth.login connecting, adding msg, has message?true
I/SocialManagerService( 1306): add com.htc.venuesrecommend to process map!
,V/SocialManagerService( 1306): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1306): com.htc.venuesrecommend connecting, adding msg, has message?true
,I/ActivityManager(  908): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=3652 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
I/SocialManagerService( 1306): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/LocationSocialPlugin( 3346): onBind
I/SocialManagerService( 1306): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1306): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
I/SocialManagerService( 1306): com.htc.venuesrecommend connected, removed msg, has message?false
I/SocialManagerService( 1306): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1306): com.htc.opensense.htcnews connecting, adding msg, has message?true
I/SocialManagerService( 1306): skip to add com.google, plugin per process full!
D/LocationIdentityProvider( 3346): is_approved false
D/LocationSocialPlugin( 3346): account null
I/ImageRamCache( 3638): create image Cache, size: 31457280.
I/ImageRamCache( 3638): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3638): create image Cache, size: 12582912.
D/LocationSocialPlugin( 3346): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
I/FeedSettings( 3638): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3638): GroupBudget 0.500000 0.380000
D/SocialManagerService( 1306): handling plugin: com.htc.venuesrecommend set result in bg
I/FeedSettings( 3638): GroupBudget 60 45 15
I/SocialManagerService( 1306): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
I/SocialManagerService( 1306): remove account type: com.htc.venuesrecommend from process map!
I/Prism.ExternalStringMa_( 3638): changeLocale(): en_GB
D/StreamPluginService( 3346): getDataSources start
V/SocialManagerService( 1306): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1306): consume pending plugin session
I/SocialManagerService( 1306): skip to add com.google, plugin per process full!
I/SocialManagerService( 1306): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1306): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
I/SocialManagerService( 1306): remove account type: com.htc.socialnetwork.rss.octopus from process map!
V/SocialManagerService( 1306): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1306): consume pending plugin session
I/SocialManagerService( 1306): skip to add com.google, plugin per process full!
I/SocialManagerService( 1306): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/Prism.AllAppsOptionsMa_( 3638): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3638): loadGridSize() with Alternative
I/SocialManagerService( 1306): com.htc.opensense.htcnews connected, removed msg, has message?false
D/SocialManagerService( 1306): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1306): remove account type: com.htc.opensense.htcnews from process map!
I/SocialManagerService( 1306): remove process: com.htc.sense.news from process map!
V/SocialManagerService( 1306): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1306): consume pending plugin session
I/SocialManagerService( 1306): skip to add com.google, plugin per process full!
I/SocialManagerService( 1306): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/ActivityManager(  908): Resuming delayed broadcast
D/AuthorizationBluetoothService( 2362): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2362): Proximity feature is not enabled.
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,D/LinkedIn( 3652): contentprovider oncreate getReadableDatabase
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/SocialManagerService( 1306): com.facebook.auth.login connected, removed msg, has message?false
,D/LinkedIn( 3652): service onBind
,I/ActivityManager(  908): Resuming delayed broadcast
I/SocialManagerService( 1306): com.htc.linkedin connected, removed msg, has message?false
D/g       ( 3652): get htcisdemo: false
D/FacebookSocialPluginService( 3652): get htcisdemo: false
I/SocialManagerService( 1306): com.twitter.android.auth.login connected, removed msg, has message?false
D/Facebook_Session( 3652): MSG_QUERY_ACCOUNT
D/Facebook_Session( 3652): queryAccount
D/Facebook_Session( 3652): queryAccount enter lock
D/Facebook_Session( 3652): Facebook Session created
D/Facebook_Session( 3652): queryAccount
,D/SocialManagerService( 1306): handling plugin: com.htc.linkedin set result in bg
,I/SocialManagerService( 1306): remove account type: com.htc.linkedin from process map!
D/Facebook_Session( 3652): Query Facebook account complete
,D/Facebook_Session( 3652): queryAccount enter lock
,V/SocialManagerService( 1306): on plugin completed! plugin session type com.htc.linkedin
,I/SocialManagerService( 1306): consume pending plugin session
I/SocialManagerService( 1306): add com.google to process map!
,V/SocialManagerService( 1306): initiating bind to plugin type com.google
D/Facebook_Session( 3652): Query Facebook account complete
,I/SocialManagerService( 1306): com.google connecting, adding msg, has message?true
I/SocialManagerService( 1306): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,D/SocialManagerService( 1306): handling plugin: com.twitter.android.auth.login set result in bg
,I/SocialManagerService( 1306): remove account type: com.twitter.android.auth.login from process map!
,D/GooglePlusSocialPluginService( 3652): Bind
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4235e2d0 u0 com.google.android.gms/.gcm.GcmService}
V/SocialManagerService( 1306): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1306): consume pending plugin session
I/SocialManagerService( 1306): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1306): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1306): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
D/SocialManagerService( 1306): handling plugin: com.facebook.auth.login set result in bg
I/SocialManagerService( 1306): com.google connected, removed msg, has message?false
I/SocialManagerService( 1306): remove account type: com.facebook.auth.login from process map!
I/GooglePlusSocialPluginService( 3652): getDataSources start
I/SocialManagerService( 1306): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
,V/SocialManagerService( 1306): on plugin completed! plugin session type com.facebook.auth.login
,D/SocialManagerService( 1306): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
,I/SocialManagerService( 1306): remove account type: com.htc.sense.socialnetwork.instagram from process map!
,I/GooglePlusSocialPluginService( 3652): getDataSources end
D/PMS     (  908): acquireWL(427eddf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3684 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
V/SocialManagerService( 1306): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
D/SocialManagerService( 1306): handling plugin: com.google set result in bg
I/SocialManagerService( 1306): remove account type: com.google from process map!
,I/SocialManagerService( 1306): remove process: com.htc.sense.socialplugins from process map!
,V/SocialManagerService( 1306): on plugin completed! plugin session type com.google
,I/SocialManagerService( 1306): onSessionCompleted
,D/GooglePlusSocialPluginService( 3652): Unbind
,D/Process (  908): killProcessQuiet, pid=3376
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,I/ActivityManager(  908): Killing 3376:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/SocialManager[SocialBiLogHelper]( 3346): social manager disconnect
I/ActivityManager(  908): Recipient 3376
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  908): releaseWL(427eddf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=3401
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3401:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3401
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  908): acquireWL(427f6830): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/WifiService(  908): Client connection lost with reason: 4
,D/PMS     (  908): releaseWL(427f6830): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3684): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PMS     (  908): acquireWL(427fd8e0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1306): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1306): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2666): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3420
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3420:com.android.settings/1000 (adj 15): empty #17
D/PMS     (  908): releaseWL(427fd8e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Recipient 3420
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2666): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3711 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  908): acquireWL(4280af68): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4280af68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 6 times.
,I/Gmail   ( 3684): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3684): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3684): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3684): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=3732 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  908): acquireWL(42813728): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3711 10160 null
,D/PMS     (  908): acquireWL(42814248): PARTIAL_WAKE_LOCK  AsyncService 0x1 3711 10160 null
,D/PMS     (  908): acquireWL(4283f778): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3711 10160 null
,D/PMS     (  908): releaseWL(42814248): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  908): releaseWL(42813728): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3711/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3711/10160)
,D/HtcFingerPrintQuickLaunchProvider( 3732): -onCreate()
,V/Settings:HtcSettingsApplication( 3732): [3732/3732] onCreate()
D/PMS     (  908): releaseWL(4283f778): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3758 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2818
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  908): killProcessQuiet, pid=3437
I/ActivityManager(  908): Killing 2818:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Killing 3437:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Recipient 2818
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3437
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3758, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 3732): id/is att sku: 99/false
,W/SystemReader( 3732): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 3758): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3758/10074)
,W/SystemReader( 3732): Cannot find support_harman, use default value instead
,W/SystemReader( 3732): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3732): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3732): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3732): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3732): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]support         :false
,W/FingerprintManager( 3732): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
E/Settings:HtcVoWifiWidgetEnabler( 3732): isSupportVoWifi: null
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3732): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3758/10074)
,D/Finsky  ( 3758): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,W/Settings( 3758): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3758): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3758, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3732): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3732): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3732): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3732): [supportHomeButton]support         :false
,D/Finsky  ( 3758): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3758): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 3758): Skipping gmscore version check
,W/FingerprintManager( 3732): hasFingerprint() - sSensorCode = 0
D/Finsky  ( 3758): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Settings:HtcVoWifiWidgetEnabler( 3732): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3732): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3758): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 3758): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  908): killProcessQuiet, pid=3278
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3278:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3278
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3798 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(41ee8a90): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41ee8a90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42428f58): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 3798): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3798): MmsConfig.loadMmsSettings
,D/PMS     (  908): acquireWL(4247c800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4247c800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
W/dalvikvm( 1963): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1963): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1963): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1963): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1963): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1963, uid=10029, userID:0
W/dalvikvm( 3798): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 3798): VFY: unable to resolve instance field 36
W/dalvikvm( 3798): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3798): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3798): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3798): MmsConfig.loadFromDatabase
,I/PeopleDatabaseHelper( 1963): cleanUpNonGplusAccounts done.
,E/Babel   ( 3798): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3798): MmsConfig.loadFromResources
E/Babel   ( 3798): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3798): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3798, uid=10111, userID:0
,W/Settings( 3798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3798, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3798, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3798, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3798, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3798, uid=10111, userID:0
D/PMS     (  908): acquireWL(42478f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3798 10111 null
,D/PMS     (  908): acquireWL(421a39b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(421a39b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426796a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,I/ProviderInstaller( 3798): Installed default security provider GmsCore_OpenSSL
D/PMS     (  908): releaseWL(426796a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 2362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1200): location=null
D/PMS     (  908): acquireWL(427840a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(427840a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(42478f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  908): killProcessQuiet, pid=3307
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3307:com.htc.task/u0a71 (adj 15): empty #17
,D/Finsky  ( 3758): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  908): sending alarm PendingIntent{424ed110: PendingIntentRecord{427c0c80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457013624116, Int=0
W/dalvikvm( 3758): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  908): Recipient 3307
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 1963): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1963): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  908): releaseWL(42428f58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426dcfc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(426dcfc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  908): acquireWL(41b5a608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(41b5a608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426f4550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(426f4550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42798118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(42798118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3758): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
D/PMS     (  908): acquireWL(425eed48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3851 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(425eed48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  908): acquireWL(426b83e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3851 10071 null
D/PMS     (  908): acquireWL(427e1be8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3851 10071 null
,D/PMS     (  908): releaseWL(426b83e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3851): java.lang.NullPointerException
W/System.err( 3851): java.lang.NullPointerException
W/System.err( 3851): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3851): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3851): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  908): releaseWL(427e1be8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/PMS     (  908): acquireWL(426a70a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
W/NotifyReceiver( 3851): stopSelfResult true
D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(426a70a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/WSP     ( 1306): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1306): Weather sync is On
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
I/WSP     ( 1306): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Mar 03 16:00:24 CET 2016
,W/WSP     ( 1306): [Receiver] can't get active network info
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1306/10055)
,D/PMS     (  908): acquireWL(426f2fc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3798 10111 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1306/10055)
,V/WSP     ( 1306): [SyncService] no data connection, stop sync service
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  908): releaseWL(426f2fc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1306): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1306): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2666): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3758): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
D/PMS     (  908): acquireWL(4261a450): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4261a450): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42695650): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42695650): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426a9ca0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426a9ca0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4283f778): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3456): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(4283f778): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(4280b8c8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427ff6f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3711 10160 null
,D/PMS     (  908): releaseWL(427ff6f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
D/PMS     (  908): releaseWL(4280b8c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/PMS     (  908): acquireWL(427f1b78): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2666): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3891 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,W/MediaManager( 3456): [DualLensScanUtil]	mmpCursor count is 0
,D/SyncApplication( 3891): Loading default preferences
,W/Resources( 3891): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3891): Overriding preferences with custom values
,D/SyncApplication( 3891): Updating preferences succeeded
,E/SyncApplication( 3891): Application created.
D/VolumeInfo( 3891): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3891): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3891): Found 0 mount point(s)
,V/VolumeInfo( 3891): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3891): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3891): getNewCalendarAuthority()...
,D/VolumeInfo( 3891): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3891): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3891): enableAppOperation()+
,D/SyncApplication( 3891): enableAppOperation()-
,D/HTCUtilities( 3891): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3891, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3891, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3891): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3891): isNeorSinged() return false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
,D/CDMountReceiver( 3891): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3891): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1556): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CDMountReceiver( 3891): enable CD Auto-mount: true
,I/RemoteViews( 1109): com.nero.android.htc.sync (false,0)
,D/PMS     (  908): releaseWL(4246e0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/HTCUtilities( 3891): enable auto-mount
V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HTCUtilities( 3891): enable auto-mount
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41cb0a98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  908): Resuming delayed broadcast
I/RemoteViews.Performance( 1109): com.nero.android.htc.sync 1 11 3 11
I/RemoteViews( 1109): com.nero.android.htc.sync (false,0)
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41d8a298 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.nero.android.htc.sync 2 8 2 16
,D/PMS     (  908): acquireWL(4269f178): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3473 10154 null
,D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,W/ContextImpl( 3473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/Finsky  ( 3758): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  908): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3758/10074)
D/Finsky  ( 3758): [1] DailyHygiene.access$600: Logging device features
,W/ContextImpl( 3473): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3473, uid=10154, userID:0
,D/PMS     (  908): acquireWL(426cd6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,D/Finsky  ( 3758): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,I/MusicLeanback( 3473): Conditions not met for autocaching.
V/AlarmManager(  908): sending alarm PendingIntent{426b07a0: PendingIntentRecord{426167c8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1457013625327, Int=0
,D/PMS     (  908): releaseWL(4269f178): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3473): Stop autocaching.
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 3758): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3758): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3851): update TASK shortcut>
,W/MediaManager( 3456): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  908): killProcessQuiet, pid=3557
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3557:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Resuming delayed broadcast
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3557
,D/WifiService(  908): Client connection lost with reason: 4
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3456): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3594:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3594
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  908): Recipient 3594
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4280fe50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(4280fe50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4280fd60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(4280fd60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427ff6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,D/PMS     (  908): acquireWL(424bf710): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3758 10074 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/Finsky  ( 3758): [403] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/PMS     (  908): releaseWL(427ff6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(424bf710): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(426cd6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,I/Icing   ( 1963): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1963): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(427f1b78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/CheckinService( 1963): Done disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/SensorManager(  908): mEventCount = 750
,I/GAV2    ( 3684): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 7 times.
,I/GAV4    ( 3798): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42825778 u0 com.htc.musicenhancer/.EnhancerService}
,I/CalendarProvider2( 1499): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1499): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3931 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3931): onCreate
D/ProviderChangeReceiver( 3931): ---------------------------------------------------
,D/ProviderChangeReceiver( 3931): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3931): start to updateAlertNotification!
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3945 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=3293
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3293:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AlertService( 3931): No fired or scheduled alerts
,D/HtcAlertUtils( 3931): -- cancelReminderNotification --
,D/HtcAlertUtils( 3931): broadcastExistReminder!
I/ActivityManager(  908): Recipient 3293
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3945): [3945/3945] onCreate()
W/ContextImpl( 3945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  908): killProcessQuiet, pid=3515
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3515:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3515
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 8 times.
,D/PMS     (  908): acquireWL(4269d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4269d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  908): mEventCount = 900
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 9 times.
,D/AutoSetting( 1306): service - handleMessage() stop self
,D/AutoSetting( 1306): service - handleMessage() quit looper
,D/AutoSetting( 1306): service - onDestroy() END
D/Process (  908): killProcessQuiet, pid=3614
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3614:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3614
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  908): mEventCount = 1050
,D/PMS     (  908): acquireWL(4282c1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
V/AlarmManager(  908): sending alarm PendingIntent{4239ea88: PendingIntentRecord{4205fb88 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81409, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{427c26e8: PendingIntentRecord{4274be50 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457013639848, Int=0
,D/PMS     (  908): releaseWL(4282c1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 10 times.
,D/Finsky  ( 3758): [392] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3758): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/SensorManager(  908): mEventCount = 1200
,D/PMS     (  908): acquireWL(427fc0b0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427fc0b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425d28e0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425d28e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426af960): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426af960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 12 times.
,I/SensorManager(  908): mEventCount = 1350
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1499): Don't start project servcice
,D/HtcModeClient( 1499): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1499): connectState: CONNECTION_READY = false
D/SilentMusic( 1499): call stop
,D/HtcModeClient( 1499): close connection
,W/HtcModeClient( 1499): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1499): read the terminate packet, so break
,D/Process (  908): killProcessQuiet, pid=3346
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3346:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3346
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3961 uid=10078 gids={50078}
,D/PMS     (  908): acquireWL(425049d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10078}
,V/AlarmManager(  908): sending alarm PendingIntent{4248def0: PendingIntentRecord{424a0220 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457013658749, Int=60000
,D/PMS     (  908): releaseWL(425049d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3961): SMSBackupAgentService started
,D/SMSBackup( 3961): Checking restore status
,D/SMSBackup( 3961): Restore complete
,D/SMSBackup( 3961): cancelCheckAlarm
,D/SMSBackup( 3961): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/Process (  908): killProcessQuiet, pid=3652
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3652:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3652
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  908): setLight #0: color=#24
,V/LightsService(  908): setLight #0: color=#1d
,V/LightsService(  908): setLight #0: color=#17
,V/LightsService(  908): setLight #0: color=#14
,D/PMS     (  908): acquireWL(426c5e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=98878, Int=0
,D/PMS     (  908): releaseWL(426c5e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1109): now=1457013660044 next=59956
,I/SensorManager(  908): mEventCount = 1500
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422e0dd8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422e0dd8, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7d6b8
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42777ee8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  908): mWirelessDisplayManager is null
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 345ms
,W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4270dae8)
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,D/NfcService( 1232): applyRouting -2
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=1249
D/PMN     (  908): wakingUp
D/PMS     (  908): acquireWL(42739c58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  908): releaseWL(42739c58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  908): No lock screen! windowToken=null
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMN     (  908): onScreenOn
D/PMS     (  908): acquireWL(4277ff48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(4277ff48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/MtpService( 2074): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2074): [MTP][onReceive]-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/AutoSetting( 1306): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1232): applyRouting - 0
,D/NfcService( 1232): applyRouting -2
D/HtcPowerSaver(  908): updateBatteryInfo
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): acquireWL(427deb30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  908): releaseWL(427deb30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1306): service - onCreate()
,D/AutoSetting( 1306): service - AddressCache: using context: com.htc.Weather
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/AutoSetting( 1306): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
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
,I/HtcPowerSaver(  908): >> updateStatus
D/LocationManagerService(  908): request 4253ce18 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
D/TetherSettings( 3732): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3732): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3732): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3732): Cust_ConnectToPC   : spcsc>false
D/        ( 3732): Cust_ConnectToPC   : IPT>true
D/        ( 3732): Cust_ConnectToPC   : Singel_USB>false
,I/ClockThread( 1109): stop update clock
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  908):    returned false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/Settings( 3732): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,E/SmartNS_Utility( 3732): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3732): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3732): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/PSReceiver( 3732): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3732): onReceive:android.intent.action.USER_PRESENT
D/NetworkPolicy(  908): updateScreenOn: false
,W/ContextImpl( 3732): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3732): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3732):  defaultType:0
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3987 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): acquireWL(42747678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42747678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42817cc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42817cc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7d6b8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7d6b8, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42777ee8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(4283c340): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,I/FeedHostManager( 1249): [onPause]
,I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41da06e8
I/SocialFeedProvider( 1249): +onPause
,I/SocialFeedProvider( 1249): -onPause
W/ContextImpl( 3987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,I/AlarmManager(  908): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19924 mDataStallAlarmIntent=null
D/PMS     (  908): releaseWL(4283c340): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  908):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  908): acquireWL(42768328): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/PMS     (  908): releaseWL(42768328): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
D/NetworkPolicy(  908): updateScreenOn: false
,D/SmartSyncUtils( 3987): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(4281cdf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3987 1000 null
,D/PMS     (  908): releaseWL(4281cdf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3987): getMobilePolicyEnabled, result = true
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/PhoneStatusBar( 1109): removeHeadsNotification.gc: 51
,W/ContextImpl( 3987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3987): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3987): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3987): getMobilePolicyEnabled, result = true
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  908): New client listening to asynchronous messages
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42777ee8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42777ee8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42777ee8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42777ee8
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42778430 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42778430 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  908): acquireWL(426eb2b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(426eb2b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4279d7a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4279d7a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1306): service - mHandler: cancel location update
,D/AutoSetting( 1306): service -           changes count: 0
,D/Process (  908): killProcessQuiet, pid=3496
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3496:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3496
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{427e0550 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(4276fe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4276fe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42782590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{425b3a70: PendingIntentRecord{42728a50 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136356, Int=0
,D/PMS     (  908): releaseWL(42782590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1306): service - handleMessage() stop self
,D/AutoSetting( 1306): service - onDestroy() END
,D/AutoSetting( 1306): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=3638
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3638:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3638
,D/PMS     (  908): acquireWL(4276a8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4263bd18: PendingIntentRecord{420dd308 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123478, Int=0
,D/PMS     (  908): acquireWL(427b6eb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42220440: PendingIntentRecord{421e3010 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141422, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,V/AlarmManager(  908): sending alarm PendingIntent{4239ea88: PendingIntentRecord{4205fb88 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141422, Int=0
,D/PMS     (  908): releaseWL(427b6eb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-,err=8
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  908): [NET] getaddrinfo-, 1
D/PMS     (  908): acquireWL(427202e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(427202e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  908): releaseWL(4276a8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    (  908): [NET] getaddrinfo_proxy-
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(427cb268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427cb268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426ee300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426ee300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PowerUI ( 1109): closing low battery warning: level=100
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,I/ClearcutLoggerApiImpl( 2362): disconnect managed GoogleApiClient
,D/PMS     (  908): acquireWL(4270f908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(4270f908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(427d5bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4243fe08: PendingIntentRecord{420dd308 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182344, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{4239ea88: PendingIntentRecord{4205fb88 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201544, Int=0
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/PMS     (  908): acquireWL(42740f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
D/PMS     (  908): releaseWL(427d5bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42822dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42740f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42822dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42829050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(42829050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4260a688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): acquireWL(427be1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1457013762958 tag=VacuumService
,D/PMS     (  908): releaseWL(4260a688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427be1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42705660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(42705660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427ab118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147,
,D/PMS     (  908): releaseWL(427ab118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427b0ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427b0ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42835178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42835178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4283a7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4283a7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(4286d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4286d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4286f378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4286f378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42874970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42874970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4287a978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=338878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4287a978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4287cbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4287cbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-,
,D/PMS     (  908): acquireWL(428848d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PowerUI ( 1109): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(428848d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(4288a2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4288a2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4288c530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4288c530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42891ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42891ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(428974a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=458878, Int=0
,D/PMS     (  908): releaseWL(428974a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42899708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42899708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(4289f0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=518878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4289f0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428a1368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(428a1368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(428a6950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428a6950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(428a8250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=578879, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428a8250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428aa4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428aa4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(428afb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428afb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1217): sku_id=99
,D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/PMS     (  908): acquireWL(428b5580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428b5580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  908): killProcessQuiet, pid=2552
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2552:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2552
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(42810ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(42810ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4280cee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=698878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4280cee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4280a090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4280a090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
,D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(427f4268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427f4268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(427d4038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=758879, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427d4038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(427c5388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/PMS     (  908): releaseWL(427c5388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(427972d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=818878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427972d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42794688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42794688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4278fc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4278fc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4277d210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=878878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4277d210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42765450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42765450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4254c050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4254c050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41edf078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=938878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41edf078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42412408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42412408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(424af370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(424af370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(426c48d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998879, Int=0
,D/PMS     (  908): releaseWL(426c48d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42452ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41e1c150: PendingIntentRecord{424fc7c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783654, Int=0
,I/ActivityManager(  908): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4049 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  908): sending alarm PendingIntent{422ab2a0: PendingIntentRecord{41bf9230 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4061 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{425e9238: PendingIntentRecord{425dc650 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457013774593, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{424c0a50: PendingIntentRecord{4249a738 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457014495057, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{424c63d8: PendingIntentRecord{424c7a18 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457014548341, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{4238df90: PendingIntentRecord{427fed20 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457014567422, Int=0
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 3987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  908): Done.
,D/PowerUsageService( 3987): call getInstance()
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PowerUsageList:PowerUsageHelper( 3987): MY_DEBUG = false
D/PMS     (  908): acquireWL(4283d740): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 3987): isEpsOn(), nState = 0
W/BatSI   (  908): Couldn't get kernel wake lock stats
D/PMS     (  908): releaseWL(42452ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  908): acquireWL(427fb298): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(426899a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3987 1000 null
,D/PMS     (  908): releaseWL(4283d740): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncScreenOnOffTimeReceiver( 3987): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3987): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3987): AlarmOnTime = -1
I/ImageRamCache( 4049): create image Cache, size: 31457280.
D/SmartSyncScreenOnOffTimeReceiver( 3987): SettingOnTime = 1457071200000, randomSettingOnTime = 1457070619000
I/ImageRamCache( 4049): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4049): create image Cache, size: 12582912.
D/SmartSyncScreenOnOffTimeReceiver( 3987): SettingOffTime = 1457056800000, randomSettingOffTime = 1457057487000
D/SmartSyncScreenOnOffTimeReceiver( 3987): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3987): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 3987): bNightModeTurnOffOnce = false
I/FeedSettings( 4049): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4049): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4049): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4049): changeLocale(): en_GB
D/PMS     (  908): releaseWL(426899a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4061/10049)
,I/Prism.AllAppsOptionsMa_( 4049): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4049): loadGridSize() with Alternative
,I/EventLogService( 1963): Aggregate from 1457012748272 (log), 1457012748272 (data)
,D/libc    ( 4049): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
,D/libc    ( 4049): [NET] getaddrinfo-,err=8
D/libc    ( 4049): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4049): [NET] getaddrinfo-, 1
D/libc    ( 4049): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4049): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 4049): Exception on getConfig()
W/SocketClient(  364): write error (Broken pipe)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024873
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025002
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025059
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025075
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025083
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026380
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026393
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030147
,D/PMS     (  908): releaseWL(427fb298): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=3798
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3798:com.google.android.talk/u0a111 (adj 15): empty #17
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/ActivityManager(  908): Recipient 3798
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3711
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3711:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3711
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(429b3020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/PowerUI ( 1109): closing low battery warning: level=100
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(429b3020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429b92d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(429b92d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429becb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058879, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429becb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(429c0f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/PMS     (  908): releaseWL(429c0f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429c6ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(429c6ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429cc4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1118879, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429cc4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(429ce710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/PMS     (  908): releaseWL(429ce710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429d3d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(429d3d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429d9768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1178878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429d9768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(429db9c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(429db9c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(429dd890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1238878, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429dd890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(429dfaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(429dfaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3758): [NET] getaddrinfo-,err=8
D/libc    ( 3758): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3758): [NET] getaddrinfo-, 1
,D/libc    ( 3758): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3758): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(4293b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/PMS     (  908): releaseWL(4293b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(429301f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1298878, Int=0
,D/PMS     (  908): releaseWL(429301f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4292e2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4292e2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4292c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  908): releaseWL(4292c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42920948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1358878, Int=0
,D/PMS     (  908): releaseWL(42920948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4291b0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  908): releaseWL(4291b0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4290f3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4290f3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(428f63e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41d2f1f8: PendingIntentRecord{41cfcf08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1418878, Int=0
,D/PMS     (  908): releaseWL(428f63e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(428f3500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428f3500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(428e84e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428e84e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms),E/cutils-trace( 4100): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4100): ====startRecUseTime====
D/htc.customization.log.level( 4100):  is 
W/CustomizationLogLevel( 4100): Level value is invalid, use default level 2
D/CustomizationManager( 4100):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4100): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4100): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4100): Parsing tag category name = system
I/CustomizationCIDLoader( 4100): Parsing tag category name = application
I/CustomizationCIDLoader( 4100): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4100): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4100): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4100): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4100): Parsing tag category name = Settings
D/CustomizationManager( 4100):  Read CID file spent 0.158 (s)
D/CustomizationManager( 4100):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 4100): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4100): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4100): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4100): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4100, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  908): Skipping PackageSetting{422dc0a8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  908): Skipping PackageSetting{422e1bc0 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1556): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 4049): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4049): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  908): acquireWL(427f4730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  908): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  908): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  908): releaseWL(427f4730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/[PluginManager]RegisterService( 1306): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1306): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2666): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4116 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  908):   Scheme: "mms"
E/ExternalAccountType( 1318): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2666): UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/FileUtils(  908): Failed to chmod(/data/system/users/0/package-restrictions.xml): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4116): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4116): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4116): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4116): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4116): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4116): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4116): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4116): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4116): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4116): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4116): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4116): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4116): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4116): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4116): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4116): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4116): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4116): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4116): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4116): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4116): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4116): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4116): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4116): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4116): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4116): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4116): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4116): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4116): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4116): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4116): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4116): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4116): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4116): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4116): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4116): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4116): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4116): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4116): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4116): threadid=11: thread exiting with uncaught exception (group=0x41733e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4116): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4116): Process: com.google.android.apps.docs, PID: 4116
E/AndroidRuntime( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4116): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4116): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4116): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4116): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4116): 	at aho.run(AbstractDatabaseInstance.java:455)
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4133 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
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
E/SQLiteDatabase( 4116): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4116): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4116): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4116): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4116): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4116): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4116): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4116): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4116): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4116): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4116): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4116): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4116): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4116): killProcess, pid=4116
D/Process ( 4116): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Recipient 4116
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4116) has died.
W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4146 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4133): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4133): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4133): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4133): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4133): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4133): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4133): threadid=10: thread exiting with uncaught exception (group=0x41733e30)
E/AndroidRuntime( 4133): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4133): Process: com.android.keychain, PID: 4133
E/AndroidRuntime( 4133): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4133): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4133): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4133): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4133): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5eb8 +
I/Prism.WidgetManager( 1249): onLoadItems() +
I/Prism.ItemManager( 4049): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4049): loadItems() com.htc.launcher.pageview.WidgetManager@41bd29a0 +
I/Prism.WidgetManager( 4049): onLoadItems() +
D/AppTag  ( 4146): getInstance(Context context)
D/Process ( 4133): killProcess, pid=4133
D/Process ( 4133): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457015031909.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Recipient 4133
I/ActivityManager(  908): Process com.android.keychain (pid 4133) has died.
D/AppTag  ( 4146): getInstance(Context context)
D/AppTag  ( 4146): onCreate()
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4161 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  908): killProcessQuiet, pid=3891
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3891:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3891
D/WifiService(  908): Client connection lost with reason: 4

```
