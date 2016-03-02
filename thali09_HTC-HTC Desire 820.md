#### Test 613623660556c10_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
--------- beginning of /dev/log/main
D/DFPI.PIReciver( 3184): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  904): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3184): onHandleIntent
I/DFPI.ApkInstallService( 3184): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3184): check CID = HTC__032
I/DFPI.ApkInstallService( 3184): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
W/PackageManager(  904): Unable to load service info ResolveInfo{428e0190 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
V/AlarmManager(  904): sending alarm PendingIntent{42866db0: PendingIntentRecord{42917778 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1456908894114, Int=0
I/Prism.ItemManager( 3237): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3237): loadItems() com.htc.launcher.pageview.WidgetManager@41eeb578 +
I/Prism.WidgetManager( 3237): onLoadItems() +
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1244): loadItems() com.htc.launcher.pageview.WidgetManager@41f03dd8 +
I/Prism.WidgetManager( 1244): onLoadItems() +
E/cutils-trace( 3490): Error opening trace file: No such file or directory (2)
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
I/GCoreNlp( 1196): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/CustomizationManager( 3490): ====startRecUseTime====
D/htc.customization.log.level( 3490):  is 
W/CustomizationLogLevel( 3490): Level value is invalid, use default level 2
D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(42a1fb38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(42a1fb38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
E/Prism.WidgetManager( 1244): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1244): onLoadItems() -
I/Prism.ItemManager( 1244): loadItems() com.htc.launcher.pageview.WidgetManager@41f03dd8 -
D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(42a45dc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(42a45dc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(42972fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(42972fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.WidgetManager( 3237): onLoadItems() -
I/Prism.ItemManager( 3237): loadItems() com.htc.launcher.pageview.WidgetManager@41eeb578 -
D/CustomizationManager( 3490):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3490): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3490): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3490): Parsing tag category name = system
I/CustomizationCIDLoader( 3490): Parsing tag category name = application
I/CustomizationCIDLoader( 3490): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3490): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3490): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3490): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3490): Parsing tag category name = Settings
D/CustomizationManager( 3490):  Read CID file spent 0.101 (s)
D/CustomizationManager( 3490):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 3490): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3490): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3490): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3490): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3490
,D/PhoneApp( 1213): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1213): -- N1 =0
D/PhoneApp( 1213): -- N2 =0
D/PhoneApp( 1213): -- N3 =0
I/ActivityManager(  904): Resuming delayed broadcast
I/SoundPicker( 3404): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3404): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3404): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3404): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3404): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3404): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3404): MODE_GSM access default DB
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3404): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3404): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3404): MODE_GSM access default DB
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3404): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3404): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3404): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3404): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/MediaStoreImporter( 3362): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): acquireWL(42920c28): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1484 10014 null
I/ActivityManager(  904): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  904): releaseWL(42920c28): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1213): bind: false
D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3505 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
I/ActivityManager(  904): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3518 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
D/Process (  904): killProcessQuiet, pid=3253
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 3253:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3253
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/GAV2    ( 3518): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  904): acquireWL(429c5938): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(429c5938): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(42b2b0b8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/NotificationService(  904): notification sound not played, stream=5 volume=0 always=false
,I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,D/Process (  904): killProcessQuiet, pid=3267
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews( 1105): com.htc.updater (true,33751552)
,I/ActivityManager(  904): Killing 3267:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{421f82d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1105): com.htc.updater 1 8 1 10
I/ActivityManager(  904): Recipient 3267
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews( 1105): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41ed3950 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1105): com.htc.updater 2 6 0 10
,D/PMS     (  904): releaseWL(42b2b0b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/IcingCorporaProvider( 2582): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  904): acquireWL(429688c0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(429688c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42968730): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms},
,D/PMS     (  904): releaseWL(42968730): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42968618): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42968618): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42958060): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42958060): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4294d348): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4294d348): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4294aa90): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4294aa90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42948480): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42948480): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42945b90): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42945b90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4292f250): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4292f250): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42928b78): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42928b78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2582): UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3557 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,V/AlarmManager(  904): sending alarm PendingIntent{428e0460: PendingIntentRecord{4296da70 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456908895861, Int=0
,I/iu.UploadsManager( 1963): End new media; added: 0, uploading: 0, time: 83 ms
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  904): acquireWL(427715b0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3557 10160 null
,D/PMS     (  904): acquireWL(4268ade8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3557 10160 null
,D/PMS     (  904): acquireWL(4239a9c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3557 10160 null
D/PMS     (  904): releaseWL(4268ade8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  904): releaseWL(427715b0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3557/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3557/10160)
D/PMS     (  904): releaseWL(4239a9c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3290
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3588 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 3290:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3290
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3310): id/is att sku: 99/false
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3588, uid=10074, userID:0
,W/SystemReader( 3310): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 3588): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3588/10074)
,W/SystemReader( 3310): Cannot find support_harman, use default value instead
,W/SystemReader( 3310): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3310): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3310): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3310): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3310): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]support         :false
,W/FingerprintManager( 3310): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3310): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3310): Failed to find provider info for com.htc.vowifi
W/dalvikvm( 3588): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3588/10074)
,D/Finsky  ( 3588): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,W/Settings( 3588): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3588): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3588): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3588, uid=10074, userID:0
,D/Ads     ( 3588): Skipping gmscore version check
,D/Finsky  ( 3588): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3588): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3588): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 3588): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3310): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3310): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3310): isSupportMusicChannel(): false
,D/Finsky  ( 3588): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportRecentAppsButton]support         :false
I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3327
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3310): [supportHomeButton]support         :false
,W/FingerprintManager( 3310): hasFingerprint() - sSensorCode = 0
I/ActivityManager(  904): Killing 3327:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,E/Settings:HtcVoWifiWidgetEnabler( 3310): isSupportVoWifi: null
I/ActivityManager(  904): Recipient 3327
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3310): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  904): acquireWL(4294b368): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1963): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1963): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1963): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1963): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1963): cleanUpNonGplusAccounts done.
,D/PMS     (  904): acquireWL(42a27d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a27d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 3588): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3588): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  904): sending alarm PendingIntent{42981258: PendingIntentRecord{42a2fd98 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456908897314, Int=0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1337): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3588): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42a54df8 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3636 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1963): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1963): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  904): releaseWL(4294b368): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
D/libc    ( 3588): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3588): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,I/Babel   ( 3636): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3636): MmsConfig.loadMmsSettings
,W/dalvikvm( 3636): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3636): VFY: unable to resolve instance field 36
,W/dalvikvm( 3636): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2465): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2465): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3636): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3636): MmsConfig.loadFromDatabase
,E/Babel   ( 3636): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3636): MmsConfig.loadFromResources
,E/Babel   ( 3636): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3636): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3636, uid=10111, userID:0
,W/Settings( 3636): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3636, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3636, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3636, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3636, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3636, uid=10111, userID:0
D/PMS     (  904): acquireWL(42a89bb0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3636 10111 null
,I/ProviderInstaller( 3636): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,D/PMS     (  904): acquireWL(429c41d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,D/PMS     (  904): releaseWL(429c41d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a27d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42a27d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1196): No location to return for getLastLocation()
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/FusedLocationProvider( 1196): location=null
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  904): acquireWL(429db6b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(429db6b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(42a89bb0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/GCM     ( 1337): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
,D/libc    ( 3588): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3588): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3588): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (3588/10074)
,V/AlarmManager(  904): sending alarm PendingIntent{422e3290: PendingIntentRecord{428b5648 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1456908897947, Int=0
D/Finsky  ( 3588): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/PMS     (  904): acquireWL(42765a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,D/WearableService( 1196): callingUid 10029, callindPid: 1196
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42765a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/DeviceConnectionService( 1196): client connected with version: 8296000
D/PMS     (  904): acquireWL(42a3dfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/Finsky  ( 3588): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3588): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/Process (  904): killProcessQuiet, pid=3169
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): releaseWL(42a3dfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  904): Killing 3169:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  904): acquireWL(42962820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
I/ActivityManager(  904): Recipient 3169
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
D/PMS     (  904): releaseWL(42962820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42632968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42632968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(428d96f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
,D/PMS     (  904): acquireWL(4279aca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(428d96f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  904): acquireWL(4267ffd8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3636 10111 null
,D/PMS     (  904): releaseWL(4279aca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): releaseWL(4267ffd8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  904): acquireWL(4281b3d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3198 10071 null
,D/ConnectivityService(  904): Done.
D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): acquireWL(4296a8a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3198 10071 null
,E/TodoTaskNotifyService( 3198): java.lang.NullPointerException
,W/System.err( 3198): java.lang.NullPointerException
W/System.err( 3198): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3198): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3198): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  904): releaseWL(4281b3d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  904): releaseWL(4296a8a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/WSP     ( 1317): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
W/NotifyReceiver( 3198): stopSelfResult true
D/WeatherUtility( 1317): Weather sync is On
,I/WSP     ( 1317): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Mar 02 10:54:58 CET 2016
,W/WSP     ( 1317): [Receiver] can't get active network info
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/WSP     ( 1317): [SyncService] no data connection, stop sync service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): acquireWL(42a7c908): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3636 10111 null
I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  904): releaseWL(42a7c908): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/IcingCorporaProvider( 2582): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  904): acquireWL(42946880): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42946880): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4294d788): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4294d788): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(429843c8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(429843c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42b62d90): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3344): [DualLensScanUtil]	mmpCursor count is 0
,D/PMS     (  904): releaseWL(42b62d90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a2b6f8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a2b6f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a486f0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a486f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(429ba340): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(429ba340): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42b5a270): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42b5a270): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42992560): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42992560): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3344): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IcingCorporaProvider( 2582): UpdateCorporaTask done [took 302 ms] updated apps [took 302 ms] 
I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  904): Resuming delayed broadcast
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3198): update TASK shortcut>
,D/PMS     (  904): acquireWL(429cfbd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3557 10160 null
,D/PMS     (  904): acquireWL(42b54c78): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(429cfbd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 7 times.
,W/MediaManager( 3344): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42a894f0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3362 10154 null
,I/ActivityManager(  904): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3362): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3362): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3362): Conditions not met for autocaching.
,I/MusicLeanback( 3362): Stop autocaching.
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3362, uid=10154, userID:0
D/PMS     (  904): releaseWL(42a894f0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3710 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3710): Loading default preferences
,W/Resources( 3710): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 3710): Overriding preferences with custom values
,D/SyncApplication( 3710): Updating preferences succeeded
,E/SyncApplication( 3710): Application created.
D/VolumeInfo( 3710): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3710): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3710): Found 0 mount point(s)
,V/VolumeInfo( 3710): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3710): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3710): getNewCalendarAuthority()...
,D/VolumeInfo( 3710): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3710): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3710): enableAppOperation()+
,D/SyncApplication( 3710): enableAppOperation()-
,D/HTCUtilities( 3710): isNeorSinged() + 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3710, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3710, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3710): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3710): isNeorSinged() return false
,D/CDMountReceiver( 3710): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3710): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1105): com.nero.android.htc.sync (false,0)
,D/CDMountReceiver( 3710): enable CD Auto-mount: true
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41fb7b08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/HTCUtilities( 3710): enable auto-mount
,D/HTCUtilities( 3710): enable auto-mount
,I/RemoteViews.Performance( 1105): com.nero.android.htc.sync 1 9 3 11
,I/RemoteViews( 1105): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{421393d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  904): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  904): Resuming delayed broadcast
,I/RemoteViews.Performance( 1105): com.nero.android.htc.sync 1 8 2 16
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3344): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42980d88): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3588 10074 null
,D/Finsky  ( 3588): [384] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
D/PMS     (  904): releaseWL(42980d88): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): releaseWL(42930070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Process (  904): killProcessQuiet, pid=2703
,I/ActivityManager(  904): Killing 2703:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 2703
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42085c90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42085c90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(429ce860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(429ce860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a374e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907,
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42a374e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  904): mEventCount = 600
,I/Icing   ( 1963): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1963): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  904): releaseWL(42b54c78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a6c728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=65198, Int=0
,D/PMS     (  904): releaseWL(42a6c728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1105): now=1456908900044 next=59956
,I/GAV2    ( 3518): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/CheckinService( 1963): Done disabling old GoogleServicesFramework version
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/GAV4    ( 3636): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{41f8a630 u0 com.htc.musicenhancer/.EnhancerService}
,I/CalendarProvider2( 1484): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1484): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3741 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3741): onCreate
D/ProviderChangeReceiver( 3741): ---------------------------------------------------
,D/ProviderChangeReceiver( 3741): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3741): start to updateAlertNotification!
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 8 times.
,D/Process (  904): killProcessQuiet, pid=3237
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3755 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Killing 3237:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/AlertService( 3741): No fired or scheduled alerts
,D/HtcAlertUtils( 3741): -- cancelReminderNotification --
,D/HtcAlertUtils( 3741): broadcastExistReminder!
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3755): [3755/3755] onCreate()
W/ContextImpl( 3755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  904): killProcessQuiet, pid=3427
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3427:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3237
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3427
,D/WifiService(  904): Client connection lost with reason: 4
,D/PMS     (  904): acquireWL(42a80dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(42a80dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  904): mEventCount = 750
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 9 times.
,D/AutoSetting( 1317): service - handleMessage() stop self
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 10 times.
,D/AutoSetting( 1317): service - onDestroy() END
,D/AutoSetting( 1317): service - handleMessage() quit looper
,I/ActivityManager(  904): Killing 3465:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3465
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3465
,D/PMS     (  904): acquireWL(429845f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
V/AlarmManager(  904): sending alarm PendingIntent{426ef040: PendingIntentRecord{427c8030 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81030, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{42940420: PendingIntentRecord{42900a38 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456908912560, Int=0
D/PMS     (  904): releaseWL(429845f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3588): [374] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3588): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  904): mEventCount = 900
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 11 times.
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 12 times.
,D/PMS     (  904): acquireWL(42a6ffd0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a6ffd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a8e718): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a8e718): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a2dc50): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a2dc50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a3c660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a3c660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1484): handler message = 4011
,E/HtcModeClient( 1484): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1484): Don't start project servcice
,D/HtcModeClient( 1484): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1484): connectState: CONNECTION_READY = false
,D/SilentMusic( 1484): call stop
D/HtcModeClient( 1484): close connection
,W/HtcModeClient( 1484): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1484): read the terminate packet, so break
,D/Process (  904): killProcessQuiet, pid=3184
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3184:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3184
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 1050
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3772 uid=10078 gids={50078}
D/PMS     (  904): acquireWL(429c3860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10078}
V/AlarmManager(  904): sending alarm PendingIntent{423a0200: PendingIntentRecord{4292a740 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456908929296, Int=60000
,D/PMS     (  904): releaseWL(429c3860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3772): SMSBackupAgentService started
,D/SMSBackup( 3772): Checking restore status
,D/SMSBackup( 3772): Restore complete
,D/SMSBackup( 3772): cancelCheckAlarm
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,D/SMSBackup( 3772): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3404
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
I/ActivityManager(  904): Killing 3404:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3404
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  904): setLight #0: color=#23
,V/LightsService(  904): setLight #0: color=#1d
,V/LightsService(  904): setLight #0: color=#16
,V/LightsService(  904): setLight #0: color=#14
,I/SensorManager(  904): mEventCount = 1200
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42570748
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  904): pid=904, uid=1000
,W/SensorService(  904): Active sensors: size = 2
,W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42570748, eanble = 0, strlen(mName) = 59
,W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420861f8
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@42999970
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  904): mWirelessDisplayManager is null
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 339ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4296d758)
D/NfcService( 1229): ScreenObserver: OFF
,D/NfcService( 1229): applyRouting - 0
,I/IntentController( 1105): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1229): applyRouting -2
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/HABCtrl (  904): TPE algorithm. remove timeout.
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): OOBE c monitor 11
D/PMN     (  904): wakingUp
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
D/PMS     (  904): acquireWL(42a6c398): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1229 1027 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): releaseWL(42a6c398): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/PMS     (  904): acquireWL(427877b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMN     (  904): onScreenOn
D/PMS     (  904): releaseWL(427877b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/InputMethodManagerService(  904): Disable input method client, pid=1244
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
,D/MtpService( 2148): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2148): [MTP][onReceive]-
,D/NfcService( 1229): applyRouting - 0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,W/XT9_C   ( 1181): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#0
D/NfcService( 1229): applyRouting -2
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1181): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  904): acquireWL(425ac600): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1229 1027 null
D/PMS     (  904): releaseWL(425ac600): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,D/TetherSettings( 3310): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3310): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3310): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3310): Cust_ConnectToPC   : spcsc>false
D/        ( 3310): Cust_ConnectToPC   : IPT>true
D/        ( 3310): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3310): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3310): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3310): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ClockThread( 1105): stop update clock
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1317): service - onCreate()
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  904):    returned false
,I/PSReceiver( 3310): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3310): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1317): service - AddressCache: using context: com.htc.Weather
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3310):  defaultType:0
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  904): request 42843468 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  904): updateScreenOn: false
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3795 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  904): acquireWL(427850c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(427850c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  904): acquireWL(42651408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42651408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420861f8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420861f8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@42999970
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(42992768): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,I/FeedHostManager( 1244): [onPause]
,I/FeedProviderManager( 1244): onPause
,I/FeedHostManager( 1244): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41faf500
,I/SocialFeedProvider( 1244): +onPause
,I/SocialFeedProvider( 1244): -onPause
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19627 mDataStallAlarmIntent=null
D/SmartSyncUtils( 3795): isEpsOn(), nState = 0
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: false
D/PMS     (  904): acquireWL(429bbcd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3795 1000 null
D/PMS     (  904): acquireWL(42993090): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42993090): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  904):    returned false
,D/PMS     (  904): releaseWL(42992768): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
D/NetworkPolicy(  904): updateScreenOn: false
,D/PMS     (  904): releaseWL(429bbcd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3795): getMobilePolicyEnabled, result = true
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/PhoneStatusBar( 1105): removeHeadsNotification.gc: 52
,W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3795): isEpsOn(), nState = 0
D/SmartSyncUtils( 3795): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3795): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42999970
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42999970, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42999970, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42999970
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42999eb8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42999eb8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  904): acquireWL(42a01438): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): releaseWL(42a01438): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(42a4b608): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a4b608): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
,I/ActivityManager(  904): Killing 3385:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3385
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3385
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42326888 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(42a3bab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125199, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a3bab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(429c7af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429c7af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42b13250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42710330: PendingIntentRecord{42989068 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138115, Int=0
,D/PMS     (  904): releaseWL(42b13250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1317): service - handleMessage() stop self
,D/AutoSetting( 1317): service - handleMessage() quit looper
,D/AutoSetting( 1317): service - onDestroy() END
,I/ActivityManager(  904): Killing 3505:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3505
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3505
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(429fb658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{426f1980: PendingIntentRecord{42a5acb0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123198, Int=0
D/PMS     (  904): acquireWL(42a445a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{426ef040: PendingIntentRecord{427c8030 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141041, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42817340: PendingIntentRecord{4280a4f0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141053, Int=0
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024,
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
,D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,D/PMS     (  904): releaseWL(42a445a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(42b52408): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(429fb658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): releaseWL(42b52408): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(42b11e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b11e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(42a861b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185199, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a861b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a88460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a88460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b34228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42971b30: PendingIntentRecord{42a5acb0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182939, Int=0
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
V/AlarmManager(  904): sending alarm PendingIntent{426ef040: PendingIntentRecord{427c8030 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201068, Int=0
,D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): releaseWL(42b34228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): acquireWL(42b1f8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,D/PMS     (  904): acquireWL(4291d138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42b1f8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4291d138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a327e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42a327e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a22dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): acquireWL(429ffb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42a22dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/VacuumService( 1196): Vacuum at: now=1456909036203 tag=VacuumService
,D/PMS     (  904): releaseWL(429ffb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a6b070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42a6b070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42a10e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42a10e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42b22400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b22400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b24748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b24748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b26048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=305199, Int=0
I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b26048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a5db18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a5db18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  904): killProcessQuiet, pid=2465
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2465:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2465
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(42a76b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a76b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a78e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a78e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42a7a708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=425198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a7a708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b36bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b36bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42b384d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=485198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b384d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b3a738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b3a738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b40180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=545199, Int=0
,D/PMS     (  904): releaseWL(42b40180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b42400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(42b42400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42b483a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=605199, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b483a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b4a608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b4a608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1213): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1213): sku_id=99
,D/ContactMessageStore( 1213): start background delete task...
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(42ab8798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=665198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ab8798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42abb320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42abb320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): closing low battery warning: level=100
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3310): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3310): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3310): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3310): Cust_ConnectToPC   : spcsc>false
,D/        ( 3310): Cust_ConnectToPC   : IPT>true
D/        ( 3310): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3310): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3310): Index of the first 1 = 3
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3310): hasRemovableStorageSlot: true
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3310): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3310): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3310): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ac3908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42ac3908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ac9268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=725199, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ac9268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42acb4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(42acb4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ad0b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42ad0b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ad6440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=785199, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ad6440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42ad86a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42ad86a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42addcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42addcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ae3638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=845198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ae3638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42ae5898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(42ae5898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42aeaed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42aeaed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42af0860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=905198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42af0860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42af2ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42af2ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42af8200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42af8200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(42b00910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b00910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b02b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b02b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42b08260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(42b08260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42b0de58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{420a8068: PendingIntentRecord{428076b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783299, Int=0
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{428f99b0: PendingIntentRecord{42a5acb0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=862238, Int=0
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3849 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{42984290: PendingIntentRecord{426adaf8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1456909045226, Int=10800000
,D/PMS     (  904): acquireWL(42b73460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{41f87638: PendingIntentRecord{42a51f48 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1456909171269, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{42649e78: PendingIntentRecord{42965798 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456909765585, Int=900000
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,V/AlarmManager(  904): sending alarm PendingIntent{42a2ce10: PendingIntentRecord{42a1c3c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456909842844, Int=0
,D/PMS     (  904): acquireWL(42b77838): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42b794c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(42b77838): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 3795): call getInstance()
,D/SmartSyncUtils( 3795): isEpsOn(), nState = 0
,D/PMS     (  904): releaseWL(42b73460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 3795): MY_DEBUG = false
D/PMS     (  904): acquireWL(42b7e6f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3795 1000 null
,D/PMS     (  904): releaseWL(42b0de58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 3795): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3795): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3795): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3795): SettingOnTime = 1456984800000, randomSettingOnTime = 1456982094000
D/SmartSyncScreenOnOffTimeReceiver( 3795): SettingOffTime = 1456970400000, randomSettingOffTime = 1456973782000
D/SmartSyncScreenOnOffTimeReceiver( 3795): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3795): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3795): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(42b7e6f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/EventLogService( 1963): Aggregate from 1456907371183 (log), 1456907371183 (data)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (3849/10049)
W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42b794c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/Process (  904): killProcessQuiet, pid=3636
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  904): Killing 3636:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3636
,D/PMS     (  904): acquireWL(42b48448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1025198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b48448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a7b538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a7b538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426f65a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426f65a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1105): closing low battery warning: level=100
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42b36b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1085198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b36b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a78b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a78b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...,
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42adb6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42adb6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(429e8648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1145198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(429e8648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42ad1b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(42ad1b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42acd148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/PMS     (  904): releaseWL(42acd148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ae1518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1205198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ae1518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(429ca420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429ca420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(42a04730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a04730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3588): [NET] getaddrinfo-,err=8
D/libc    ( 3588): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3588): [NET] getaddrinfo-, 1
,D/libc    ( 3588): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3588): [NET] getaddrinfo_proxy-
,I/Scheduler( 1196): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 1196): Found 10029
,D/PMS     (  904): acquireWL(42b83020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023049
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023320
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023408
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023416
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023419
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024907
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360027647
,D/PMS     (  904): releaseWL(42b83020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42b448b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426f2298: PendingIntentRecord{426e0788 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1265198, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b448b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3884): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3884): ====startRecUseTime====
D/htc.customization.log.level( 3884):  is 
W/CustomizationLogLevel( 3884): Level value is invalid, use default level 2
D/CustomizationManager( 3884):  Read ACC file spent 0.125 (s)
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3884): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3884): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3884): Parsing tag category name = system
I/CustomizationCIDLoader( 3884): Parsing tag category name = application
I/CustomizationCIDLoader( 3884): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3884): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3884): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3884): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3884): Parsing tag category name = Settings
D/CustomizationManager( 3884):  Read CID file spent 0.177 (s)
D/CustomizationManager( 3884):  All configurations done spent 0.177 (s)
W/HtcNativeFlag( 3884): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3884): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3884): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3884): Fail to get flag for type 'language', use default value: -1
D/PMS     (  904): acquireWL(42ab5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42ab5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=3884, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  904): Skipping PackageSetting{425319f8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  904): Skipping PackageSetting{42535668 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  904): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  904): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1300): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(42bb5148): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1270): Cleaning up data for package: com.test.thalitest
D/PMS     (  904): releaseWL(42bb5148): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
W/AccTypeManager( 1300): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1300): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1244): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1229): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/IcingCorporaProvider( 2582): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3899 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
E/ExternalAccountType( 1300): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/IcingCorporaProvider( 2582): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  904): Unable to load service info ResolveInfo{42ac3040 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 3899): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3899): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3899): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3899): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3899): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3899): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3899): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3899): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3899): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3899): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3899): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3899): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3899): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3899): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3899): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3899): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3899): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3899): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3899): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3899): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3899): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3899): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3899): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3899): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3899): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3899): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3899): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3899): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3899): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3899): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3899): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3899): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3899): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3899): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3899): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3899): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3899): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3899): threadid=11: thread exiting with uncaught exception (group=0x41a41e30)
E/AndroidRuntime( 3899): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3899): Process: com.google.android.apps.docs, PID: 3899
E/AndroidRuntime( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3899): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3899): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3899): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3899): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3899): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
E/SQLiteDatabase( 3899): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3899): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3899): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3899): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3899): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3899): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3899): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3899): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3899): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3899): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3899): Opened ClientFlag.db in read-only mode
D/Process ( 3899): killProcess, pid=3899
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3918 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 3899): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3899
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
D/Process (  904): killProcessQuiet, pid=3557
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3557:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 3899) has died.
W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 3918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=3931 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 3918): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3918): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 3918): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 3918): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3918): threadid=10: thread exiting with uncaught exception (group=0x41a41e30)
E/AndroidRuntime( 3918): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3918): Process: com.android.keychain, PID: 3918
E/AndroidRuntime( 3918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3918): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 3918): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 3918): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3918): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 3918): killProcess, pid=3918
D/Process ( 3918): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1456910107571.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
I/ActivityManager(  904): Recipient 3918
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 3918) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 3931): getInstance(Context context)
D/AppTag  ( 3931): getInstance(Context context)
D/AppTag  ( 3931): onCreate()
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3557
W/BroadcastQueue(  904): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue(  904): android.os.TransactionTooLargeException
W/BroadcastQueue(  904): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  904): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  904): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  904): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  904): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3946 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  904): Process com.google.android.apps.plus (pid 3557) has died and restarted (pid 3946).
E/SQLiteDatabase( 3946): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3946): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 3946): 	at del.a(PG:264)
E/SQLiteDatabase( 3946): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3946): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  904): acquireWL(42bf6088): PARTIAL_WAKE_LOCK  AsyncService 0x1 3946 10160 null
E/SQLiteDatabase( 3946): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3946): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 3946): 	at del.a(PG:264)
E/SQLiteDatabase( 3946): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3946): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 3588): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  904): releaseWL(42bf6088): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/EsApplication( 3946): Failed app initialization
E/EsApplication( 3946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 3946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 3946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 3946): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 3946): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 3946): 	at del.a(PG:264)
E/EsApplication( 3946): 	at eeq.run(PG:187)
E/EsApplication( 3946): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1963): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 1963): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 1963): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 1963): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1963): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1963): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 1963): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1963): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1963): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 1963): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 1963): App measurement is starting up, version: 8489
I/GMPM-SVC( 1963): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  904): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 1963): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1963): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1963): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x65fa53c0
W/dalvikvm( 1963): threadid=36: thread exiting with uncaught exception (group=0x41a41e30)
E/SQLiteOpenHelper( 1963): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  904): acquireWL(42b3cda8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
W/SQLiteOpenHelper( 1963): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/Icing   ( 1963): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1963): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1963): threadid=33: thread exiting with uncaught exception (group=0x41a41e30)
E/AndroidRuntime( 1963): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1963): Process: com.google.android.gms, PID: 1963
E/AndroidRuntime( 1963): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 1963): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1963): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1963): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1963): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime_2_crash( 1963): crash in the same process: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime_2_crash( 1963): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime_2_crash( 1963): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 1963): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 1963): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 1963): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 1963): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 1963): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime_2_crash( 1963): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime_2_crash( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms

```
