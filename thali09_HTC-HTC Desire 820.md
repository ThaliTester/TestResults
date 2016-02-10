#### Test 58918757c0fcaf3_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1470): handler message = 4011
E/HtcModeClient( 1470): Check connection and retry 5 times.
I/MediaStoreImporter( 3878): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
--------- beginning of /dev/log/system
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3677): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  905): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3677): onHandleIntent
I/DFPI.ApkInstallService( 3677): Media Scan Finished Case 
I/EASRequestController( 3940): [ NA ]release
D/DFPI.ApkInstallService( 3677): check CID = HTC__032
I/DFPI.ApkInstallService( 3677): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/EASAppSvc( 3940): [ NA ]< uninitEASService
I/EASAppSvc( 3940): [ NA ]- onCreate()
I/EASAppSvc( 3940): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3919): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3919): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3919): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3919): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3919): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3919): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3919): MODE_GSM access default DB
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.android.mail (3940/10064)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.htc.android.mail (3940/10064)
I/ActivityManager(  905): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/ConnectivityService(  905): getNetworkInfo networkType=55 called by com.htc.android.mail (3940/10064)
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3919): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3919): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3919): MODE_GSM access default DB
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/ORMLib  ( 3613): put()
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/EASAppSvc( 3940): [ NA ]- onDestroy()
I/EASAppSvc( 3940): [ NA ]> uninitEASService
I/EASRequestController( 3940): [ NA ]release
I/EASAppSvc( 3940): [ NA ]< uninitEASService
I/ActivityManager(  905): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3986 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3919): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3919): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3919): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3919): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=2908
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2908:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  905): Recipient 2908
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3613): put()
I/MediaStoreImporter( 3878): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=3733
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3733:com.htc.sense.news/u0a76 (adj 15): empty #17
D/PMS     (  905): acquireWL(42dd0808): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1470 10014 null
I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/ActivityManager(  905): Recipient 3733
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(42dd0808): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1241): bind: false
D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4005 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
E/cutils-trace( 3991): Error opening trace file: No such file or directory (2)
D/PMS     (  905): acquireWL(42ed1ef0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/Process (  905): killProcessQuiet, pid=3752
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3752:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  905): releaseWL(42ed1ef0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=56 rxSum=46} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20737 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20738 delay=15s
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  905): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4028 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Recipient 3752
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3991): ====startRecUseTime====
D/htc.customization.log.level( 3991):  is 
W/CustomizationLogLevel( 3991): Level value is invalid, use default level 2
D/PMS     (  905): acquireWL(42c34430): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42c34430): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 4028): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  905): acquireWL(42aef1d8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 3991):  Read ACC file spent 0.074 (s)
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3991): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3991): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3991): Parsing tag category name = system
I/CustomizationCIDLoader( 3991): Parsing tag category name = application
I/CustomizationCIDLoader( 3991): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3991): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3991): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3991): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3991): Parsing tag category name = Settings
D/CustomizationManager( 3991):  Read CID file spent 0.128 (s)
D/CustomizationManager( 3991):  All configurations done spent 0.129 (s)
W/HtcNativeFlag( 3991): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3991): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3991): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3991): Fail to get flag for type 'language', use default value: -1
D/PMS     (  905): releaseWL(42aef1d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42ddf8b8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42ddf8b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3991
I/Gmail   ( 4028): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4028): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4028): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4028): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  905): notification sound not played, stream=5 volume=0 always=false
I/RemoteViews( 1115): com.htc.updater (true,33751552)
D/PMS     (  905): releaseWL(42e26160): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{422d2a18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.htc.updater 3 10 1 10
I/RemoteViews( 1115): com.htc.updater (true,33751552)
D/Process (  905): killProcessQuiet, pid=3421
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{4242c8f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.htc.updater 1 7 0 10
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3421:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Recipient 3421
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/PMS     (  905): acquireWL(42d271f8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42d271f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e6a538): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e6a538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42f70498): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42f70498): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e3b8e8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e3b8e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e05aa8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e05aa8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42ea7100): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2175, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2175, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2175, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2175, uid=10029, userID:0
D/PMS     (  905): releaseWL(42ea7100): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e02690): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/PMS     (  905): releaseWL(42e02690): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  905): acquireWL(42e57398): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  905): releaseWL(42e57398): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  905): acquireWL(42d99b90): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42d99b90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  905): acquireWL(42ea2d20): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  905): releaseWL(42ea2d20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42cbbce8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42cbbce8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
I/IcingCorporaProvider( 2844): UpdateCorporaTask done [took 694 ms] updated apps [took 693 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(42d512a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3567 10160 null
D/PMS     (  905): releaseWL(42d512a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4071 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/SensorManager(  905): mEventCount = 300
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AutoSetting( 1328): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1328): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1328): service - requestNLP() NetworkLocationProvider not enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4071, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 3808): id/is att sku: 99/false
,D/Finsky  ( 4071): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4071/10074)
,W/SystemReader( 3808): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/PackageManager(  905): Unable to load service info ResolveInfo{42f5a440 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/SystemReader( 3808): Cannot find support_harman, use default value instead
,W/SystemReader( 3808): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3808): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3808): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3808): updateDevelopment, bPrefShow = true
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcUmcWidgetEnabler( 3808): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]support         :false
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/FingerprintManager( 3808): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4071/10074)
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3808): isSupportVoWifi: null
E/ActivityThread( 3808): Failed to find provider info for com.htc.vowifi
,D/Finsky  ( 4071): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4071): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4071): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3808): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3808): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3808): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3808): [supportHomeButton]support         :false
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,W/FingerprintManager( 3808): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3808): isSupportVoWifi: null
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4071, uid=10074, userID:0
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3808): Failed to find provider info for com.htc.vowifi
,D/Ads     ( 4071): Skipping gmscore version check
,D/Finsky  ( 4071): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4071): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4071): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4071): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  905): killProcessQuiet, pid=3720
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3720:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3720
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PackageBroadcastService( 2175): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4111 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  905): acquireWL(42f043f8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4111): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4111): VFY: unable to resolve instance field 36
,W/dalvikvm( 2175): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2175): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 4111): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2175): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2175): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2175): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,W/dalvikvm( 2175): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 2175): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/Babel   ( 4111): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4111): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4111): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2175): cleanUpNonGplusAccounts done.
,D/MmsCustomizationProvider( 2728): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4111, uid=10111, userID:0
D/MmsCustomizationProvider( 2728): query uri: content://htc-mms-customization/mms-ua/ua_profile
W/Settings( 4111): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 4111): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4111): MmsConfig.loadFromDatabase
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4111, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4111, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4111, uid=10111, userID:0
E/Babel   ( 4111): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4111): MmsConfig.loadFromResources
,E/Babel   ( 4111): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4111): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4111, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4111, uid=10111, userID:0
D/PMS     (  905): acquireWL(42f1c1f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4111 10111 null
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4111): Installed default security provider GmsCore_OpenSSL
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1219): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  905): releaseWL(42f1c1f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42f7c4a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4111 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(42f810c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42f810c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42f828d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f828d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f84bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f84bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f7c4a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42f87400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=3770
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3770:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
I/ActivityManager(  905): Recipient 3770
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42f87400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42f90ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
D/PMS     (  905): releaseWL(42f90ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  905): acquireWL(42f9b5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42f9b5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
D/PMS     (  905): acquireWL(42fa1468): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42fa1468): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@4232bc70 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,D/PMS     (  905): acquireWL(42f43b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42f43b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42ed19f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): releaseWL(42ed19f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e81508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42e81508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42dc2960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42dc2960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42bfbbb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
I/SocialFeedProvider( 1270): +disConnect socialManager
I/SocialFeedProvider( 1270): disconnect socialManager
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4158 uid=10041 gids={50041}
,I/SocialFeedProvider( 1270): -disConnect socialManager
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42bfbbb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(426c5a20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4111 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  905): releaseWL(426c5a20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/Process (  905): killProcessQuiet, pid=3785
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3785:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  905): acquireWL(42cbbd38): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3613 10071 null
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(42d936b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3613 10071 null
I/ActivityManager(  905): Recipient 3785
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(42b2e240): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3613 10071 null
,D/PMS     (  905): releaseWL(42cbbd38): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 3613): java.lang.NullPointerException
,W/System.err( 3613): java.lang.NullPointerException
W/System.err( 3613): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3613): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3613): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3613): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  905): acquireWL(42d936b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3613 10071 null
W/NotifyReceiver( 3613): stopSelfResult false
,E/TodoTaskNotifyService( 3613): java.lang.NullPointerException
W/System.err( 3613): java.lang.NullPointerException
W/System.err( 3613): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3613): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3613): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3613): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 3613): mStartingService is null
,W/NotifyReceiver( 3613): stopSelfResult true
D/PMS     (  905): releaseWL(42b2e240): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(42d936b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,D/LocationInitializer( 2175): Restart initialization of location
,D/AuthorizationBluetoothService( 1362): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1362): Proximity feature is not enabled.
,E/MDM     ( 1219): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): acquireWL(42e34bf0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3613 10071 null
,D/PMS     (  905): acquireWL(42d9b098): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3613 10071 null
,I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 3613): java.lang.NullPointerException
W/System.err( 3613): java.lang.NullPointerException
W/System.err( 3613): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 3613): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3613): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3613): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): releaseWL(42e34bf0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(42d9b098): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
W/NotifyReceiver( 3613): stopSelfResult true
I/WSP     ( 1328): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1328): Weather sync is On
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  905): acquireWL(42ef73b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42ef73b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42556070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/ActivityManager(  905): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4184 uid=10016 gids={50016, 3003, 5012, 2001}
,I/WSP     ( 1328): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Feb 10 19:06:38 CET 2016
E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@4232bc70 -
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
D/PMS     (  905): acquireWL(42e9a4b0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1328 10055 null
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,D/Process (  905): killProcessQuiet, pid=3837
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3837:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/UpdateFetcherService( 4184): Update started
I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  905): Recipient 3837
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2175): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2175): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  905): releaseWL(42f043f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,D/Process (  905): killProcessQuiet, pid=3822
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3822:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3822
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DownloadManager( 2708): Download 363 starting
D/PMS     (  905): acquireWL(42ec32c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2708 10021 WorkSource{10016}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
W/ActivityThread( 2708): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/libc    ( 2708): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2708): [NET] getaddrinfo-,err=8
D/libc    ( 2708): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2708): [NET] getaddrinfo-, 1
,D/libc    ( 2708): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =76a8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
,D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2708): [NET] getaddrinfo_proxy-, success
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,I/DownloadManager( 2708): Ignoring Content-Length since Transfer-Encoding is also defined,
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2708): Download 363 finished with status SUCCESS
D/PMS     (  905): releaseWL(42ec32c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ActivityManager(  905): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4210 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  905): acquireWL(42cbd2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10055}
,V/AlarmManager(  905): sending alarm PendingIntent{42c696f0: PendingIntentRecord{42dd36b0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455123999533, Int=0
,D/PMS     (  905): releaseWL(42cbd2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/ImageRamCache( 4210): create image Cache, size: 31457280.
I/ImageRamCache( 4210): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4210): create image Cache, size: 12582912.
,I/FeedSettings( 4210): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4210): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4210): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4210): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4210): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4210): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4210): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4210): last commit ulog time 1455113472444
,I/SocialManager[SocialBiLogHelper]( 4210): skip commit this time
,D/Process (  905): killProcessQuiet, pid=3940
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3940:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3940
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4184): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4184): Update started
,I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4184): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4184): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4184): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4239 uid=10032 gids={50032, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3677
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3677:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3677
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DownloadManager( 2708): Download 364 starting
D/PMS     (  905): acquireWL(42ea47d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2708 10021 WorkSource{10016}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2708): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2708): [NET] getaddrinfo-,err=8
D/libc    ( 2708): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2708): [NET] getaddrinfo-, 1
D/libc    ( 2708): [NET] getaddrinfo_proxy+
D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2f41 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2708): [NET] getaddrinfo_proxy-, success
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/PMS     (  905): acquireWL(42f024d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{424a9e68: PendingIntentRecord{42c93618 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59692, Int=0
,I/DownloadManager( 2708): Ignoring Content-Length since Transfer-Encoding is also defined
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4239, uid=10032, userID:0
,D/PMS     (  905): acquireWL(42ee32e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42ee32e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4239, uid=10032, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4239, uid=10032, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4239, uid=10032, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4239, uid=10032, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42d75c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42d75c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42ecdb18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42ecdb18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42dcf2b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42dcf2b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f85f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2708): Download 364 finished with status SUCCESS
D/PMS     (  905): releaseWL(42f85f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42ea47d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/PMS     (  905): acquireWL(42f54da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f54da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e9deb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e9deb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3856
,I/ActivityManager(  905): Killing 3856:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4262 uid=10079 gids={50079, 3003, 5012}
,I/ActivityManager(  905): Recipient 3856
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 6 times.
,E/PhoneMonitor( 4262): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4262): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  905): killProcessQuiet, pid=3919
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2844): canRun() : Opted Out
I/ActivityManager(  905): Killing 3919:com.htc.sdm/u0a81 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
D/PMS     (  905): acquireWL(42f01988): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f00ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/Search.GservicesUpdateTask( 2844): Updating Gservices keys
D/PMS     (  905): releaseWL(42f01988): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2175): Checkin interval check for package: unspecified last checkin: 1455123995267 min interval config: 0 actual interval: 5257
,I/CheckinService( 2175): Checking schedule, now: 1455124000536 next: 1455124025216
,I/CheckinService( 2175): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2175, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
D/PMS     (  905): releaseWL(42f00ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/ContactAccountLoggerTas( 2844): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2844): canRun() : Opted Out
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ContactAccountLoggerTas( 2844): canRun() : Opted Out
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3567, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3567, uid=10160, userID:0
I/ActivityManager(  905): Recipient 3919
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3567, uid=10160, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3567, uid=10160, userID:0
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6db9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8,
,D/libc    ( 1362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
,D/libc    ( 1362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
,I/ContactAccountLoggerTas( 2844): canRun() : Opted Out
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42b55080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42b2b390): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2175): Checkin interval check for package: unspecified last checkin: 1455123995267 min interval config: 0 actual interval: 5748
D/PMS     (  905): releaseWL(42b55080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2175): Checking schedule, now: 1455124001024 next: 1455124025216
,I/CheckinService( 2175): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2175, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,I/SystemUpdateService( 2175): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 2175): onCreate
D/PMS     (  905): acquireWL(42291040): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42b2b390): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2175): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 2175): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,I/SystemUpdateService( 2175): cancelUpdate (empty URL)
,I/SystemUpdateService( 2175): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/GAV2    ( 4028): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  905): sending alarm PendingIntent{42aa6e68: PendingIntentRecord{42aa3da0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455124001251, Int=0
,W/SQLiteConnectionPool( 2175): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
,D/SystemUpdateService( 2175): onDestroy
D/PMS     (  905): releaseWL(42291040): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,E/DynamiteModule( 2175): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 2175): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 2175): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 2175): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 2175): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 2175): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 2175): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 2175): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 2175): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 2175): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 2175): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 2175): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 2175): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 2175): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 2175): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 2175): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 2175): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 2175): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 2175): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 2175): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 2175): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 2175): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 2175): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 2175): Selected local version of com.google.android.gms.flags
,D/PMS     (  905): acquireWL(42d1afe0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,D/SystemEventReceiver( 2175): Received GSERVICES_CHANGED broadcast
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,I/OcrUtils( 2175): Updating ocr activity enabled=false
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1219, uid=10029, userID:0
,D/PMS     (  905): releaseWL(42d1afe0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2175, uid=10029, userID:0
,D/PMS     (  905): acquireWL(42dc4bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/OcrModelManager( 2175): Updating downloaded model state (gservices changed)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/GCM     ( 1362): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  905): acquireWL(42cb3590): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=11 [9][1][0]
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42dc4bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42e6ff88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42e6ff88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42e33bf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42cb3590): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(42e33bf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1219): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1219): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  905): acquireWL(42d22478): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42ef7420: PendingIntentRecord{42f72fd8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360061406 win=-1 tElapsed=315360061406 maxElapsed=551880061406 interval=0 standalone=false
,I/GCoreUlr( 1219): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1219): DispatchingService.onCreate()
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  905): acquireWL(42d9e788): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/TodoTaskshortcut( 3613): update TASK shortcut>,
,I/GCoreUlr( 1219): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1219): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/PMS     (  905): acquireWL(42e7b660): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e7b660): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/ctxmgr  ( 1219): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1219): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  905): releaseWL(42d22478): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e0ce18): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e0ce18): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e27650): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e27650): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1219): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
D/PMS     (  905): acquireWL(42ecf668): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42ecf668): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42d9e788): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/GCoreUlr( 1219): DispatchingService.onDestroy()
,I/GCoreUlr( 1219): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
D/PMS     (  905): acquireWL(42e84c50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e84c50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4111): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/AlarmManager(  905): sending alarm PendingIntent{42ce0ca0: PendingIntentRecord{42c99320 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1455124003024, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42c8d1b0: PendingIntentRecord{42bebfc8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455124003063, Int=0
,I/iu.UploadsManager( 2175): End new media; added: 0, uploading: 0, time: 66 ms
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:106, mTXpacketCount:50, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  905): acquireWL(42f56638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f56638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 7 times.
,I/GAV2    ( 3567): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/CheckinService( 2175): Done disabling old GoogleServicesFramework version
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2175, uid=10029, userID:0
,I/CalendarProvider2( 1470): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1470): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42e830d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4111 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  905): releaseWL(42e830d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  905): acquireWL(42e567d0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  905): mEventCount = 450
,D/PMS     (  905): releaseWL(42e567d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e3a390): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e3a390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e14c68): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e14c68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e0bb18): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e0bb18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42df25d0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42df25d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42dd0c90): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42dd0c90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42db6668): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42db6668): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42dad230): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42dad230): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42dabef0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42dabef0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2844): UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42d9bc48): PARTIAL_WAKE_LOCK  AsyncService 0x1 3567 10160 null
,D/PMS     (  905): releaseWL(42d9bc48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PackageBroadcastService( 2175): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2175): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  905): acquireWL(42bbbb98): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2175): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 2175): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2175): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2175): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(42bbbb98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42ca4228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42ca4228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42834198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42834198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42e9a4b0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/PMS     (  905): acquireWL(42b5c118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42b5c118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,D/PMS     (  905): acquireWL(42d6a9e8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3878 10154 null
,I/ActivityManager(  905): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4336 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/ContextImpl( 3878): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3878, uid=10154, userID:0
,W/ContextImpl( 3878): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3878): Conditions not met for autocaching.
,I/MusicLeanback( 3878): Stop autocaching.
,I/DownloadManager( 2708): Download 365 starting
D/PMS     (  905): releaseWL(42d6a9e8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/PMS     (  905): acquireWL(42e96f38): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2708 10021 WorkSource{10016}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2708): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=6 [30][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42d4d9c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42e88bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42d4d9c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42e88bb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DownloadManager( 2708): Download 365 finished with status SUCCESS
D/PMS     (  905): releaseWL(42e96f38): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2708): Download 366 starting
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL,
D/PMS     (  905): acquireWL(42e8fdb0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2708 10021 WorkSource{10016}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2708/10021)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/PMS     (  905): acquireWL(42e76140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/DownloadManager( 2708): Ignoring Content-Length since Transfer-Encoding is also defined
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4368 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [9][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,W/MediaManager( 4336): [DualLensScanUtil]	mmpCursor count is 0
D/PMS     (  905): releaseWL(42e76140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=3986
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3986:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3986
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 4368): Loading default preferences
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2708/10021)
W/Resources( 4368): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 4368): Overriding preferences with custom values
,D/SyncApplication( 4368): Updating preferences succeeded
,E/SyncApplication( 4368): Application created.
D/VolumeInfo( 4368): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4368): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4368): Found 0 mount point(s)
V/VolumeInfo( 4368): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4368): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4368): getNewCalendarAuthority()...
I/DownloadManager( 2708): Download 366 finished with status SUCCESS
D/VolumeInfo( 4368): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4368): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4368): enableAppOperation()+
,D/SyncApplication( 4368): enableAppOperation()-
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4368, uid=10008, userID:0
D/PMS     (  905): releaseWL(42e8fdb0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4368, uid=10008, userID:0
,W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 4368): isNeorSinged() + 
,D/HTCUtilities( 4368): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4368): isNeorSinged() return false
,D/CDMountReceiver( 4368): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4368): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4368): enable CD Auto-mount: true
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/PMS     (  905): releaseWL(42f024d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/HTCUtilities( 4368): enable auto-mount
D/HTCUtilities( 4368): enable auto-mount
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(42ba6e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{425d3350 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/Process (  905): killProcessQuiet, pid=4005
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 9 4 11
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
I/ActivityManager(  905): Killing 4005:com.htc.updater/u0a85 (adj 15): empty #17
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42550c78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 0 8 2 16
I/ActivityManager(  905): Recipient 4005
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(42ba6e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(425c1648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4392 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/PMS     (  905): releaseWL(425c1648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarApplication( 4392): onCreate
D/ProviderChangeReceiver( 4392): ---------------------------------------------------
,D/ProviderChangeReceiver( 4392): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4392): start to updateAlertNotification!
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4406 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2728
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2728:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/AlertService( 4392): No fired or scheduled alerts
,D/HtcAlertUtils( 4392): -- cancelReminderNotification --
,D/HtcAlertUtils( 4392): broadcastExistReminder!
I/ActivityManager(  905): Waited long enough for: ServiceRecord{42efd1b0 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  905): Recipient 2728
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4406): [4406/4406] onCreate()
W/ContextImpl( 4406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 ,
,I/UpdateFetcherService( 4184): Update downloaded, starting installation
,I/UpdateFetcherService( 4184): Started installation
,W/ContextImpl( 4184): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4184): Update downloaded, starting installation
,I/UpdateFetcherService( 4184): Started installation
,I/ConfigUpdateInstallReceiver(  905): Not installing, new version is <= current version
,D/Process (  905): killProcessQuiet, pid=3625
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3625:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3625
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageSettings(  905): Skipping PackageSetting{42959b78 com.example.hello/10397} due to missing metadata
,W/PackageSettings(  905): Skipping PackageSetting{429613a8 com.test.thalitest/10389} due to missing metadata
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 8 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=121 rxSum=106} preTxRxSum={txSum=56 rxSum=46}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20738 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20739 delay=15s
D/PMS     (  905): acquireWL(42f06fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42d4eb70: PendingIntentRecord{42cfd5e8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70592, Int=0
D/PMS     (  905): releaseWL(42f06fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(42e03900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e03900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 9 times.
,D/Finsky  ( 4071): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4071): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  905): acquireWL(42e0b088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{42cd67d8: PendingIntentRecord{42ce5ca8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455124016196, Int=0
D/PMS     (  905): releaseWL(42e0b088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4071/10074)
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4071): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4071): [NET] getaddrinfo-,err=8
D/libc    ( 4071): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4071): [NET] getaddrinfo-, 1
D/libc    ( 4071): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =24b1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4071): [NET] getaddrinfo_proxy-, success
I/global  ( 4071): call createSocket() return a new socket.
D/libc    ( 4071): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4071): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4071): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4071): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4071): untagSocket(69) failed with errno -22
,D/Finsky  ( 4071): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4071): untagSocket(69) failed with errno -22
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  905): mEventCount = 600
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4071): untagSocket(69) failed with errno -22
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4071/10074)
,D/Finsky  ( 4071): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  905): acquireWL(42ede1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{4282b0c0: PendingIntentRecord{42eddb00 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455124018234, Int=0
,D/PMS     (  905): acquireWL(42e67340): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4071 10074 null
,D/PMS     (  905): releaseWL(42ede1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/WearableService( 1219): callingUid 10029, callindPid: 1219
D/Finsky  ( 4071): [435] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1219): client connected with version: 8296000
,D/Finsky  ( 4071): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4071): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4071): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4071): [NET] getaddrinfo-,err=8
D/libc    ( 4071): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4071): [NET] getaddrinfo-, 1
D/libc    ( 4071): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3f89 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=9 [65][6][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:221, mTXpacketCount:106, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 293
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4071): [NET] getaddrinfo_proxy-, success
,D/PMS     (  905): releaseWL(42e67340): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/ClockThread( 1115): now=1455124019527 next=473
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ClockThread( 1115): now=1455124020001 next=59999
D/PMS     (  905): acquireWL(42f60790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=79533, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f60790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 10 times.
,D/AutoSetting( 1328): service - has update message, not stop
,D/AutoSetting( 1328): service - mHandler: update timezone
,D/AutoSetting( 1470): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1470): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1470): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1470): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1470): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1470): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1470): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1470): service - mHandler: update timezone
,D/AutoSetting( 1470): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1470): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1470): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1470): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{422c1658 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 7 2 11
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [11][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 11 times.
,D/PMS     (  905): acquireWL(42f960a0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f960a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42eda078): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42eda078): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f75528): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f75528): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f77888): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f77888): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=196 rxSum=174} preTxRxSum={txSum=121 rxSum=106}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20739 Sent 0 pkts since last received, < watchdogTrigger=5
,D/PMS     (  905): acquireWL(42f79880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20740 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{42e73fe8: PendingIntentRecord{42cfd5e8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=85597, Int=0
D/PMS     (  905): releaseWL(42f79880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 12 times.
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:233, mTXpacketCount:221, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1470): Don't start project servcice
,D/HtcModeClient( 1470): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1470): connectState: CONNECTION_READY = false
,D/SilentMusic( 1470): call stop
D/HtcModeClient( 1470): close connection
W/HtcModeClient( 1470): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1470): read the terminate packet, so break
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42f500e8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  905): acquireWL(42f37de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029}
,V/AlarmManager(  905): sending alarm PendingIntent{42c839a8: PendingIntentRecord{42de6228 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455124025216, Int=522937000
,V/AlarmManager(  905): sending alarm PendingIntent{42cb78b8: PendingIntentRecord{42e56668 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455124032515, Int=0
,D/PMS     (  905): acquireWL(42f3b328): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4444 uid=10078 gids={50078}
,V/AlarmManager(  905): sending alarm PendingIntent{42d19a40: PendingIntentRecord{42cfea00 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455124036359, Int=60000
,D/PMS     (  905): releaseWL(42f37de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  905): acquireWL(42fa9b68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f3b328): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2175): Checkin interval check for package: unspecified last checkin: 1455123995267 min interval config: 0 actual interval: 41141
,I/CheckinService( 2175): Checking schedule, now: 1455124036416 next: 1455124025216
,I/CheckinService( 2175): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2175, uid=10029, userID:0
,D/SMSBackup( 4444): SMSBackupAgentService started
,I/CheckinService( 2175): Preparing to send checkin request
I/EventLogService( 2175): Accumulating logs since 1455123990929
,D/SMSBackup( 4444): Checking restore status
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
D/SMSBackup( 4444): Restore complete
D/SMSBackup( 4444): cancelCheckAlarm
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,D/SMSBackup( 4444): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/CheckinRequestBuilder( 2175): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2175): Failed to find provider info for com.google.android.wearable.settings
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/Finsky  ( 4071): [425] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4071): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  905): killProcessQuiet, pid=4210
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4210:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4210
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2175/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4458 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4458): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4458): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4458): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4458): install
,I/MultiDex( 4458): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4458): loading existing secondary dex files
,I/MultiDex( 4458): load found 3 secondary dex files
,I/MultiDex( 4458): install done
,W/dalvikvm( 4458): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4458): VFY: unable to resolve instance field 36
,W/dalvikvm( 4458): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4458): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4458): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,D/LocationInitializer( 2175): Restart initialization of location
,W/dalvikvm( 4458): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4458): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AuthorizationBluetoothService( 1362): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1362): Proximity feature is not enabled.
,E/MDM     ( 1219): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 4458): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4458): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4458): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4458): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4458): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  905): acquireWL(42e8d298): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e8d298): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4458): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=678066843
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG (),
I/Adreno-EGL( 4458): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4458): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4458): Local Branch: 
I/Adreno-EGL( 4458): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4458): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4458):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4458): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4458): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4458): Local Branch: 
I/Adreno-EGL( 4458): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4458): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4458):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4458): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4458/10029)
,I/Adreno-EGL( 4458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4458): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4458): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4458): Local Branch: 
I/Adreno-EGL( 4458): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4458): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4458):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1935782840
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2175): Classify the device as Phone.
,D/libc    ( 2175): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2175): [NET] getaddrinfo-,err=8
D/libc    ( 2175): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2175): [NET] getaddrinfo-, 1
,D/libc    ( 2175): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7479 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2175): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2175): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2175): [NET] getaddrinfo-,err=8
,D/libc    ( 2175): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2175): [NET] getaddrinfo-,err=8
D/libc    ( 2175): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2175): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2175): Sending checkin request (12260 bytes)
,I/SensorManager(  905): mEventCount = 750
,I/CheckinRequestBuilder( 2175): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2175): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2175/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=18 [16][3][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
,I/CheckinRequestBuilder( 2175): Classify the device as Phone.
,I/CheckinTask( 2175): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2175): Checking schedule, now: 1455124038841 next: 1455646975837
,I/CheckinService( 2175): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2175, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,D/CheckinService( 2175): Recording last checkin time for package unspecified as 1455124038871
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42fa9b68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2175/10029)
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/LightsService(  905): setLight #0: color=#24
,V/LightsService(  905): setLight #0: color=#20
,V/LightsService(  905): setLight #0: color=#1a
,V/LightsService(  905): setLight #0: color=#14
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  905): acquireWL(425d3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=212 rxSum=185} preTxRxSum={txSum=196 rxSum=174}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20740 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20741 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{42c601a0: PendingIntentRecord{42cfd5e8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100600, Int=0
D/PMS     (  905): releaseWL(425d3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/Process (  905): killProcessQuiet, pid=4239
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4239:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4239
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a31c78
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a31c78, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42bc4370
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42e4f590
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  905): mWirelessDisplayManager is null
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  905): acquireWL(42e87268): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4111 10111 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 317ms
,W/PnPMgr  (  354): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
,D/PMS     (  905): nativeSetAutoSuspend:true done
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): acquireWL(42ead970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/PMS     (  905): OOBE c monitor 11
,I/BatteryService(  905): n_update end
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
D/PMS     (  905): releaseWL(42ead970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/InputMethodManagerService(  905): Disable input method client, pid=1270
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/NfcService( 1253): applyRouting -2
D/PMS     (  905): acquireWL(42ee46b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
D/PMS     (  905): releaseWL(42ee46b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PMS     (  905): releaseWL(42e87268): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  905): acquireWL(42e60a00): PARTIAL_WAKE_LOCK  AsyncService 0x1 3567 10160 null
D/PMS     (  905): releaseWL(42e60a00): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  905): acquireWL(42fac0a0): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42fac0a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2175): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2175): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  905): acquireWL(42e640d8): PARTIAL_WAKE_LOCK  Icing 0x1 2175 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2175): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  905): Unable to load service info ResolveInfo{42e87ce0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
,I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42ca1358)
D/PMN     (  905): wakingUp
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,D/MtpService( 2708): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1253): applyRouting - 0
,D/MtpService( 2708): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting -2
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): acquireWL(42ef0610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/AutoSetting( 1328): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  905): releaseWL(42ef0610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
I/ClockThread( 1115): stop update clock
D/TetherSettings( 3808): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3808): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3808): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3808): Cust_ConnectToPC   : spcsc>false
D/        ( 3808): Cust_ConnectToPC   : IPT>true
D/        ( 3808): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3808): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3808): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3808): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3808): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/PSReceiver( 3808): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/SmartNS_PSService( 3808): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3808): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3808):  defaultType:0
I/ActivityManager(  905): Resuming delayed broadcast
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
,D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20742 delay=15s
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:On
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
I/IcingCorporaProvider( 2844): UpdateCorporaTask done [took 630 ms] updated apps [took 630 ms] 
,D/WifiNative-wlan0(  905):    returned true
,I/GCoreNlp( 1219): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:252, mTXpacketCount:233, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/NotificationService(  905): batLight: Full, plugged
,V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/LocationProviderProxy(  905): applying state to connected service
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4513 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  905): acquireWL(4303ac10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): releaseWL(4303ac10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/NetworkPolicy(  905): updateScreenOn: false
,D/PMS     (  905): acquireWL(43044098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43044098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43047dc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43047dc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43049b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(4304b9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(4304cde8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4513 1000 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(43049b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4513): getMobilePolicyEnabled, result = true
D/PMS     (  905): releaseWL(4304cde8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1766): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): onScreenOn: 1455124047492
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1766): onScreenOn: 1455124047492
,D/Process (  905): killProcessQuiet, pid=4262
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(4304b9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Killing 4262:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4262
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42bc4370
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
,W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42bc4370, eanble = 0, strlen(mName) = 91
,W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42e4f590
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(4305b1d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42394538
,I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
D/AlarmManager(  905): ACTION_SCREEN_OFF
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20742 mDataStallAlarmIntent=PendingIntent{424601b8: PendingIntentRecord{42cfd5e8 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:Off
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1156): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  905):    returned true
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
D/PMS     (  905): acquireWL(43062ba8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4305b1d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4513): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1241): start background delete task...
D/NetworkPolicy(  905): updateScreenOn: false
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e4f590
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e4f590, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e4f590, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e4f590
D/WifiService(  905): New client listening to asynchronous messages
,E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e4fad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e4fad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43062ba8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1328): service - mHandler: cancel location update
,D/AutoSetting( 1328): service -           changes count: 0
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1766): onScreenOff.
D/PMS     (  905): acquireWL(4307a288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4307a288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4307b710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4307b710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1766): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1766): onScreenOff
,I/Icing   ( 2175): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@4232bc70 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/Icing   ( 2175): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(42e640d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@4232bc70 -
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/AutoSetting( 1470): service - handleMessage() stop self
,D/AutoSetting( 1470): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3613
,I/ActivityManager(  905): Killing 3613:com.htc.task/u0a71 (adj 15): empty #17
D/AutoSetting( 1470): service - handleMessage() quit looper
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3613
,I/ActivityManager(  905): Killing 3901:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3901
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3901
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4309f288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42bb0ba8: PendingIntentRecord{42c23ea0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=117954, Int=0
,D/PMS     (  905): releaseWL(4309f288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  905): acquireWL(430a1018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(430a6ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430a6ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430a1018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430aceb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(430aceb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430b1250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(430ba4a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430c2528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1219): Vacuum at: now=1455124058704 tag=VacuumService
,D/PMS     (  905): releaseWL(430b1250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430c2528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430c8958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(430c8958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430ccdc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(430ccdc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430ba4a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4302f2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(4302f2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42fb57a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
D/PMS     (  905): releaseWL(42fb57a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42f82590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42f56d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f56d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f2dba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f82590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f2aa08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42f2aa08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 1988 seconds from now (1455124059413)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1219): [NET] getaddrinfo-, 1
,D/libc    ( 1219): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5d4a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1219): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42f2dba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f1d158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42f1d158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  905): acquireWL(42e047a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(42e047a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42f03f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(42f03f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42f29420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42bd5f90: PendingIntentRecord{42e8c3c0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137205, Int=0
,D/PMS     (  905): releaseWL(42f29420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,D/AutoSetting( 1328): service - handleMessage() stop self
,D/AutoSetting( 1328): service - handleMessage() quit looper
,D/AutoSetting( 1328): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3878
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3878:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3878
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3878): Died!
,D/PMS     (  905): acquireWL(42ecbd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ecbd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42ef1be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42b5dd78: PendingIntentRecord{42832360 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142227, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(42fa7920): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42ef1be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4b66 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(42fa7920): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(430863e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(430863e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42f4ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{42dc49c8: PendingIntentRecord{42efb340 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170908, Int=0
,D/PMS     (  905): releaseWL(42f4ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(42e1a3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e1a3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42edaf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42edaf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42f542c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f542c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42d4df20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d4df20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(42ecd6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ecd6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42e769d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e769d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(430d2f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(430d2f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4306f278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=319533, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4306f278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=4336
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4336:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4336
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42e93d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42e93d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(430066c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(430066c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43040018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43040018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42f037d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f037d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42ea34c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=439532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ea34c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4307d938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4307d938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(423ae788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(423ae788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4306f100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=499532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4306f100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42e5ebf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42e5ebf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43085950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43085950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(430788b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=559532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(430788b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e8dcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e8dcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e3c738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(42e3c738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42f4b2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=619532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f4b2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  905): acquireWL(42e5be98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e5be98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42f4b848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f4b848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42edf0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=679533, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42edf0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e40978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e40978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42df96f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=739532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42df96f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4301ae10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4301ae10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42ccf7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42ccf7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42f79fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=799532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f79fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42da10d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42da10d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42f285b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=859532, Int=0
,D/PMS     (  905): releaseWL(42f285b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e46a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e46a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42ef05e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42ef05e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4305a188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=919532, Int=0
,D/PMS     (  905): releaseWL(4305a188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
D/PMS     (  905): acquireWL(43045a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{4254f540: PendingIntentRecord{42c2d2c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778139, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{423b1970: PendingIntentRecord{42e78c00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=946681, Int=0
D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(42b7bdd0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42b7bdd0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4572 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42dc62c8: PendingIntentRecord{42e2dbd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455124152243, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42c4fd98: PendingIntentRecord{42c27e50 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455124872684, Int=900000
,W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(43045a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4513): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4513): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4572/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=4368
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4368:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4368
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(4316f4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(4316f4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(431405b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1362/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024804
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024946
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025009
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025012
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025015
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025020
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026421
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026437
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029290
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360061406
,D/PMS     (  905): releaseWL(431405b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  905): acquireWL(431390d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(431390d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43132e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43132e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(431307f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
V/AlarmManager(  905): sending alarm PendingIntent{42c310d8: PendingIntentRecord{4304e798 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455124947570, Int=0
D/PMS     (  905): releaseWL(431307f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4312ef98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4513 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4513): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4513): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4513): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4513): SettingOnTime = 1455170400000, randomSettingOnTime = 1455169174000
D/SmartSyncScreenOnOffTimeReceiver( 4513): SettingOffTime = 1455156000000, randomSettingOffTime = 1455163167000
D/SmartSyncScreenOnOffTimeReceiver( 4513): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4513): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4513): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(4312ef98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(430bf530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(430bf530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43028728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43028728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42f1ae10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039532, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f1ae10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42f07e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f07e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42e7d1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e7d1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42d43ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1099532, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d43ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42d41e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d41e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42ab6f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42ab6f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42df3f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1159533, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42df3f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42cad548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42cad548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42be2330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42be2330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42fc3d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42316db0: PendingIntentRecord{4230ca18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1219533, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42fc3d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4598): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4598): ====startRecUseTime====
D/htc.customization.log.level( 4598):  is 
W/CustomizationLogLevel( 4598): Level value is invalid, use default level 2
D/CustomizationManager( 4598):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4598): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4598): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4598): Parsing tag category name = system
I/CustomizationCIDLoader( 4598): Parsing tag category name = application
I/CustomizationCIDLoader( 4598): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4598): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4598): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4598): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4598): Parsing tag category name = Settings
D/CustomizationManager( 4598):  Read CID file spent 0.153 (s)
D/CustomizationManager( 4598):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4598): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4598): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4598): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4598): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4598, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  905): Skipping PackageSetting{42959b78 com.example.hello/10397} due to missing metadata
W/PackageSettings(  905): Skipping PackageSetting{429613a8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(43041108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  905): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  905): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  905): releaseWL(43041108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4613 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
F/PackageManager(  905): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  905): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  905): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  905): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  905): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  905): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  905): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  905): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  905): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  905): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  905): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1193)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  905): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  905): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  905): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  905): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  905): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  905): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  905): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  905): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  905): 	... 14 more
E/SQLiteLog( 2844): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2844): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63657230
W/dalvikvm( 2844): threadid=14: thread exiting with uncaught exception (group=0x41e68e30)
E/AndroidRuntime( 2844): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2844): Process: com.google.android.googlequicksearchbox:search, PID: 2844
E/AndroidRuntime( 2844): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2844): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2844): 	at cid.d(PG:186)
E/AndroidRuntime( 2844): 	at clo.g(PG:594)
E/AndroidRuntime( 2844): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2844): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2844): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2844): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2844): 	at clr.tL(PG:827)
E/AndroidRuntime( 2844): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2844): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2844): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2844): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  905): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1455125208848.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2844): killProcess, pid=2844
D/Process ( 2844): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 2844
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2844): Died!
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2844) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4613): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4613): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4613): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4613): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4613): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4613): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4613): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4613): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4613): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4613): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4613): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4613): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4613): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4613): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4613): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4613): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4613): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4613): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4613): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4613): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4613): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4613): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4613): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4613): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4613): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4613): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4613): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4613): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4613): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4613): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4613): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4613): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4613): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4613): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4613): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4613): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4613): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4613): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4613): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4613): threadid=11: thread exiting with uncaught exception (group=0x41e68e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
W/PackageManager(  905): Unable to load service info ResolveInfo{42df2008 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 4613): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4613): Process: com.google.android.apps.docs, PID: 4613
E/AndroidRuntime( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4613): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4613): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4613): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4613): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4613): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4613): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4613): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4613): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4613): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4613): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4613): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4613): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4613): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4613): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4613): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4613): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4613): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4613): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4613): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4613): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4613): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4613): Opened ClientFlag.db in read-only mode
D/Process ( 4613): killProcess, pid=4613
D/Process ( 4613): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4630 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4613
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4613) has died.
W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4630): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4630): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4630): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4630): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4630): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4630): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4644 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
W/dalvikvm( 4630): threadid=10: thread exiting with uncaught exception (group=0x41e68e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4630): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4630): Process: com.android.keychain, PID: 4630
E/AndroidRuntime( 4630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4630): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4630): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4630): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4630): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4630): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4630): killProcess, pid=4630
D/Process ( 4630): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455125209531.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4644): getInstance(Context context)
I/ActivityManager(  905): Recipient 4630
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4630) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10427ms
D/AppTag  ( 4644): getInstance(Context context)
D/AppTag  ( 4644): onCreate()
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
D/PMS     (  905): acquireWL(42fc1ab8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3567 10160 null
D/PMS     (  905): releaseWL(42fc1ab8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/Process (  905): killProcessQuiet, pid=4158
W/dalvikvm( 4071): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  905): Killing 4158:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4158
D/PackageBroadcastService( 2175): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccountUtils( 2175): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2175): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2175): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2175): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2175): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2175): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2175): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2175): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2175): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2175): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2175): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2175): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2175): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2175): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2175): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2175): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2175): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2175): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2175): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2175): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2175): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2175): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2175): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2175): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2175): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2175): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@4232bc70 +
I/Prism.WidgetManager( 1270): onLoadItems() +
E/dalvikvm( 2175): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2175): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2175): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2175): App measurement is starting up, version: 8489
I/GMPM-SVC( 2175): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2175): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2175): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb5e788
E/DriveAsyncService( 2175): disk I/O error (code 3850)
E/DriveAsyncService( 2175): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2175): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2175): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2175): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2175): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2175): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2175): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2175): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2175): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2175): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2175): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2175): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2175): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x664d63c8
D/ChimeraCfgMgr( 2175): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2175): Module APK com.google.android.play.games already loaded
W/dalvikvm( 2175): threadid=49: thread exiting with uncaught exception (group=0x41e68e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2175): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2175): Process: com.google.android.gms, PID: 2175
E/AndroidRuntime( 2175): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2175): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2175): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2175): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2175): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2175): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2175): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2175): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2175): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2175): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2175): killProcess, pid=2175
E/SQLiteDatabase( 2175): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2175): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2175): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2175): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2175): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2175): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2175): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2175): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2175): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2175): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2175): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2175): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2175): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2175): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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

```
