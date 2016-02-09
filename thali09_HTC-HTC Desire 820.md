#### Test 5841644866d9c0e_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
--------- beginning of /dev/log/system
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/EASAppSvc( 3935): [ NA ]- onCreate()
I/EASAppSvc( 3935): [ NA ]> onUpgrade: version = 63
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/Process (  907): killProcessQuiet, pid=3616
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Delay finish: com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent
I/ActivityManager(  907): Killing 3616:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/ORMLib  ( 3431): put()
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3935/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3935/10064)
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3972 uid=10078 gids={50078}
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3935/10064)
D/Process (  907): killProcessQuiet, pid=2894
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2894:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3616
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/EASAppSvc( 3935): [ NA ]- onDestroy()
I/EASAppSvc( 3935): [ NA ]> uninitEASService
I/EASRequestController( 3935): [ NA ]release
I/EASAppSvc( 3935): [ NA ]< uninitEASService
I/EASAppSvc( 3935): [ NA ]- onCreate()
I/EASAppSvc( 3935): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3935/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3935/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3935/10064)
D/SMSBackup( 3972): Got a database change event
D/DFPI.PIReciver( 3863): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3863): onHandleIntent
I/DFPI.ApkInstallService( 3863): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3863): check CID = HTC__032
I/DFPI.ApkInstallService( 3863): There is no Demo.apk in sd card or phone storage
D/Process (  907): killProcessQuiet, pid=3654
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3654:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/SoundPicker( 3913): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3913): SoundPickerReceiver [onReceive] startService
D/ORMLib  ( 3431): put()
I/SoundPicker( 3913): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3913): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3913): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3913): MODE_GSM access default DB
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3913): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3913): MODE_GSM access default DB
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3654
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/EASAppSvc( 3935): [ NA ]- onDestroy()
I/EASAppSvc( 3935): [ NA ]> uninitEASService
I/EASRequestController( 3935): [ NA ]release
I/ActivityManager(  907): Recipient 2894
I/EASAppSvc( 3935): [ NA ]< uninitEASService
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4004 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
I/CheckinRequestBuilder( 2142): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2142): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ORMLib  ( 3431): put()
E/cutils-trace( 3980): Error opening trace file: No such file or directory (2)
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=5 [18][1][0]
I/MediaStoreImporter( 3542): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=3691
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3691:com.htc.calendar/u0a13 (adj 15): empty #17
D/AutoSetting( 1342): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1342): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1342): service - requestNLP() NetworkLocationProvider not enabled
I/ActivityManager(  907): Recipient 3691
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3863): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3863): onHandleIntent
I/DFPI.ApkInstallService( 3863): Media Scan Finished Case 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3863): check CID = HTC__032
I/DFPI.ApkInstallService( 3863): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/SoundPicker( 3913): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3913): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3913): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3913): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3913): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3913): MODE_GSM access default DB
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3913): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3913): MODE_GSM access default DB
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/CustomizationManager( 3980): ====startRecUseTime====
D/htc.customization.log.level( 3980):  is 
W/CustomizationLogLevel( 3980): Level value is invalid, use default level 2
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/CheckinRequestBuilder( 2142): Classify the device as Phone.
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
W/PackageManager(  907): Unable to load service info ResolveInfo{4239dab0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3913): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/CheckinTask( 2142): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/CheckinService( 2142): Checking schedule, now: 1455019751402 next: 1455542688390
I/CheckinService( 2142): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2142, uid=10029, userID:0
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
D/PMS     (  907): releaseWL(424ecf50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/CheckinService( 2142): Recording last checkin time for package unspecified as 1455019751425
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3913): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/PMS     (  907): releaseWL(426f4f38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 3913): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3913): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
D/CustomizationManager( 3980):  Read ACC file spent 0.082 (s)
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3980): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3980): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3980): Parsing tag category name = system
I/CustomizationCIDLoader( 3980): Parsing tag category name = application
I/CustomizationCIDLoader( 3980): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3980): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3980): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3980): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3980): Parsing tag category name = Settings
D/CustomizationManager( 3980):  Read CID file spent 0.138 (s)
D/CustomizationManager( 3980):  All configurations done spent 0.138 (s)
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
W/HtcNativeFlag( 3980): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3980): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3980): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3980): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3980
I/MediaStoreImporter( 3542): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42649508): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1512 10014 null
I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  907): releaseWL(42649508): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1239): bind: false
D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4036 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/Messaging( 3875): mNeedToUpdateDate2 start
D/MmsConfig( 3875): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 3875): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3875): 
D/MmsAsyncWorkHandler( 3875): HM tk = 20001
D/ReportIndicatorCache( 3875): MSG_QUERY_REPORTS >>
D/SettingsManager( 3875): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aa89f8
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
I/Messaging( 3875): mccmnc> 
D/DraftCache( 3875): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3875): [DraftCache/1] refresh
D/MmsConfig( 3875): networkCode: 
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 3875): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 3875): mNeedToUpdateDate2: false
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1239): sku_id=99
D/PhoneStorageUtil( 3875): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3875): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3875): createReceiver
D/MessageCustFlag( 3875): sense_version=6.0
D/Jerry   ( 3875): start to preload cursor >>>>>>>
D/DraftCache( 3875): [DraftCache/394] rebuildCache
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1239): Update uri=content://mms, match=0
V/MmsProvider( 1239): selection=st=129 AND m_type!=134
D/Messaging( 3875): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/Process (  907): killProcessQuiet, pid=3729
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Messaging( 3875): Reset downloading state: 0
V/MmsSystemEventReceiver( 3875): TransactionService is going to be woken up.
I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4056 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3729:com.htc.android.worldclock/u0a90 (adj 15): empty #17
V/TransactionService( 3875): 1-Creating TransactionService
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/Jerry   ( 1239): URI_DRAFT
D/Messaging( 3875): ViewCache CreatePreload
D/Messaging( 3875): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 3875): _has_set_default_values_2=true
V/TransactionService( 3875): onStartCommand: 1
D/MmsSystemEventReceiver( 3875): unRegisterForConnectionStateChanges
V/TransactionService( 3875): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3875): Loading previous transactions.
D/DraftCache( 3875): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3875): [DraftCache/394] rebuildCache time: 2
D/MmsAsyncWorkHandler( 3875): 
D/MmsAsyncWorkHandler( 3875): HM tk = 20002
I/ActivityManager(  907): Delaying start of: ServiceRecord{426c7b50 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
D/MsgPreferenceUtils( 3875): def_index: 0
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1239): device_type: 1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1239): sku_id=99
D/TransactionService( 3875): Force set service start id to 1
V/TransactionService( 3875): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3875): unRegisterForConnectionStateChanges
I/ActivityManager(  907): Recipient 3729
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TransactionService( 3875): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 3875): Destroying TransactionService
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1239): sku_id=99
V/TransactionService( 3875): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/PMS     (  907): acquireWL(42654b20): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42654b20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 4056): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/MsgPreferenceUtils( 3875): globalIndex = 1
D/MsgPreferenceUtils( 3875): phone state: true
D/MsgPreferenceUtils( 3875): sd state: false
D/MsgPreferenceUtils( 3875): vIndex = 0
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  907): acquireWL(426fb520): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  907): releaseWL(426fb520): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 +
I/Prism.WidgetManager( 1273): onLoadItems() +
D/PMS     (  907): acquireWL(426d6708): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426d6708): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1548): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
I/RemoteViews( 1117): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d576a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1117): com.htc.updater 2 7 0 10
I/RemoteViews( 1117): com.htc.updater (true,33751552)
I/ActivityManager(  907): Resuming delayed broadcast
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e433f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1117): com.htc.updater 2 10 0 10
I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
D/Process (  907): killProcessQuiet, pid=3742
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/Gmail   ( 4056): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  907): Killing 3742:com.android.settings:remote/1000 (adj 15): empty #17
I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/Gmail   ( 4056): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  907): Recipient 3742
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Gmail   ( 4056): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4056): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  907): acquireWL(424cb618): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(422c3ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(422c3ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(41cf7dd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/LocationProviderProxy(  907): applying state to connected service
D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): releaseWL(41cf7dd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(425c8730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425c8730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42490508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42490508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(424cb618): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(422cf100): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(422cf100): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(425eafd0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425eafd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42445fa0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42445fa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426a20a8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426a20a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4248d1e8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4248d1e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426522c0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426522c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 -
D/PMS     (  907): acquireWL(4264bf18): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4264bf18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 330 ms] updated apps [took 330 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4110 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(427813c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
,D/PMS     (  907): releaseWL(427813c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425c3af8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4110 10160 null
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4136 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3773
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3773:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/PMS     (  907): acquireWL(426a94c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4110 10160 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(425c3af8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  907): Recipient 3773
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(426a94c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3811): id/is att sku: 99/false
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4136, uid=10074, userID:0
,W/SystemReader( 3811): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0,
,D/PhoneApp( 1239): -- N2 =0
D/PhoneApp( 1239): -- N3 =0
,D/Finsky  ( 4136): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/SystemReader( 3811): Cannot find support_harman, use default value instead
,W/SystemReader( 3811): Cannot find effect_manager_id, use default value instead
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4136/10074)
,E/Settings:HtcWrapHeaderInfo( 3811): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3811): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3811): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3811): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]support         :false
,W/FingerprintManager( 3811): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
E/Settings:HtcVoWifiWidgetEnabler( 3811): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3811): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3811): updateDevelopment, bPrefShow = true
W/dalvikvm( 4136): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
E/Settings:HtcUmcWidgetEnabler( 3811): isSupportMusicChannel(): false
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3811): Failed to find provider info for com.htc.vowifi
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3811): [supportHomeButton]support         :false
W/FingerprintManager( 3811): hasFingerprint() - sSensorCode = 0
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4136/10074)
E/Settings:HtcVoWifiWidgetEnabler( 3811): isSupportVoWifi: null
D/Finsky  ( 4136): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4136): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3811): Failed to find provider info for com.htc.vowifi
W/Settings( 4136): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4136): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4136, uid=10074, userID:0
,D/Ads     ( 4136): Skipping gmscore version check
,D/Finsky  ( 4136): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4136): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4136): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4136): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  907): killProcessQuiet, pid=3790
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3790:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3790
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2142): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  907): acquireWL(424194a8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424194a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4269b520): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/dalvikvm( 2142): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2142): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2142): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2142): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2142): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2142): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2142): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2142, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2142): cleanUpNonGplusAccounts done.
,I/SocialFeedProvider( 1273): +disConnect socialManager
,I/SocialFeedProvider( 1273): disconnect socialManager
,I/SocialFeedProvider( 1273): -disConnect socialManager
,I/ActivityManager(  907): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4180 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{4236b700: PendingIntentRecord{423e4028 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455019753704, Int=0
,I/ImageRamCache( 4180): create image Cache, size: 31457280.
I/ImageRamCache( 4180): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4180): create image Cache, size: 12582912.
,I/FeedSettings( 4180): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4180): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4180): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4180): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4180): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4180): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4180): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4180): last commit ulog time 1454934978643
,I/SocialManager[SocialBiLogHelper]( 4180): skip commit this time
,D/Process (  907): killProcessQuiet, pid=3826
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3826:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3826
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2142): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2142): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A,
D/PMS     (  907): releaseWL(4269b520): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4196 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4196): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4196): MmsConfig.loadMmsSettings
,W/dalvikvm( 4196): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4196): VFY: unable to resolve instance field 36
,W/dalvikvm( 4196): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4196): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3875): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3875): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4196, uid=10111, userID:0
I/Babel   ( 4196): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4196): MmsConfig.loadFromDatabase
W/Settings( 4196): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4196, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4196, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4196, uid=10111, userID:0
E/Babel   ( 4196): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4196): MmsConfig.loadFromResources
,E/Babel   ( 4196): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4196): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4196, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4196, uid=10111, userID:0
D/PMS     (  907): acquireWL(426832f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4196): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  907): releaseWL(426832f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(425d4638): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(425d4638): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(426987d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=3711
,I/ActivityManager(  907): Killing 3711:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3711
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(426987d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(426aba98): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(426aba98): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=60 rxSum=50} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19421 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19422 delay=15s
,D/PMS     (  907): acquireWL(42639ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42639ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42774ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/PMS     (  907): releaseWL(42774ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(426e3188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426e3188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/PMS     (  907): acquireWL(426b4f90): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426b4f90): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  907): acquireWL(426d8d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/PMS     (  907): releaseWL(426d8d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(426d3ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/PMS     (  907): releaseWL(426d3ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4267f6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4267f6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(425304f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(425304f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4244c3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  907): acquireWL(41ab0c98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3431 10071 null
D/PMS     (  907): acquireWL(41c6f478): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3431 10071 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
E/TodoTaskNotifyService( 3431): java.lang.NullPointerException
W/System.err( 3431): java.lang.NullPointerException
,W/System.err( 3431): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3431): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3431): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3431): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3431): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(41ab0c98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(41c6f478): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,W/NotifyReceiver( 3431): stopSelfResult true
D/PMS     (  907): releaseWL(4244c3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): acquireWL(424c09d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3431 10071 null
,D/PMS     (  907): acquireWL(42301ec8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3431 10071 null
,I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 3431): java.lang.NullPointerException
,W/System.err( 3431): java.lang.NullPointerException
W/System.err( 3431): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3431): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3431): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3431): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3431): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): releaseWL(424c09d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
D/PMS     (  907): releaseWL(42301ec8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,W/NotifyReceiver( 3431): stopSelfResult true
D/PMS     (  907): acquireWL(4233b208): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3431 10071 null
D/PMS     (  907): acquireWL(42689a18): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3431 10071 null
E/TodoTaskNotifyService( 3431): java.lang.NullPointerException
W/System.err( 3431): java.lang.NullPointerException
W/System.err( 3431): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3431): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3431): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3431): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3431): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3431): stopSelfResult true
I/ActivityManager(  907): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
D/PMS     (  907): releaseWL(4233b208): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(42689a18): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/LocationInitializer( 2142): Restart initialization of location
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,E/MDM     ( 1222): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  907): acquireWL(424a0b90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(424a0b90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4258f6c0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3542 10154 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,W/ContextImpl( 3542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3542, uid=10154, userID:0
,I/MusicLeanback( 3542): Conditions not met for autocaching.
,I/MusicLeanback( 3542): Stop autocaching.
,I/WSP     ( 1342): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1342): Weather sync is On
,W/ContextImpl( 3542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(4258f6c0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(4252ef50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
D/PMS     (  907): acquireWL(41c61a78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
,I/WSP     ( 1342): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 09 14:09:15 CET 2016
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): releaseWL(41c61a78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  907): acquireWL(4259fa50): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1342 10055 null
,D/Process (  907): killProcessQuiet, pid=3972
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3972:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3972
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(425ec388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c817e0: PendingIntentRecord{42497a48 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59176, Int=0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3935
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3935:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  907): Recipient 3935
,I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(426cb2d8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426cb2d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(424c14d8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424c14d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42583218): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42583218): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4275a938): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4275a938): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(424cc798): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424cc798): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426a8028): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426a8028): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42794d88): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42794d88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4238acc8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 6 times.
D/PMS     (  907): releaseWL(4238acc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 279 ms] updated apps [took 279 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4253db50): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
,D/PMS     (  907): releaseWL(4253db50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2142): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2142): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  907): acquireWL(426a52b0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2142): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 3431): update TASK shortcut>
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/AlarmManager(  907): sending alarm PendingIntent{42586238: PendingIntentRecord{424d4008 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455019756617, Int=0
,I/Icing   ( 2142): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/SQLiteConnectionPool( 2142): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Icing   ( 2142): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2142): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(426a52b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4056): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/AlarmManager(  907): sending alarm PendingIntent{425c2568: PendingIntentRecord{425dbe48 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1455019757608, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42528e98: PendingIntentRecord{425edba0 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455019757657, Int=0
,I/iu.UploadsManager( 2142): End new media; added: 0, uploading: 0, time: 56 ms
,D/PMS     (  907): acquireWL(4276bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4276bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 450
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4196): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2142, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2142, uid=10029, userID:0
,I/CheckinService( 2142): Done disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2142, uid=10029, userID:0
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 7 times.
,I/CalendarProvider2( 1512): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1512): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425f53a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(425f53a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(425c50c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(425c50c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4276bfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425e49d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4260d100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(425e49d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(4260d100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4276bfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/MediaManager( 3844): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4287 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4287): Loading default preferences
,W/Resources( 4287): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4287): Overriding preferences with custom values
,D/SyncApplication( 4287): Updating preferences succeeded
,E/SyncApplication( 4287): Application created.
D/VolumeInfo( 4287): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4287): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4287): Found 0 mount point(s)
,V/VolumeInfo( 4287): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4287): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4287): getNewCalendarAuthority()...
,D/VolumeInfo( 4287): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4287): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4287): enableAppOperation()+
,D/SyncApplication( 4287): enableAppOperation()-
,D/HTCUtilities( 4287): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4287, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4287, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4287): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4287): isNeorSinged() return false
,D/CDMountReceiver( 4287): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4287): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4287): enable CD Auto-mount: true
,D/DotMatrix( 1548): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4287): enable auto-mount
,D/HTCUtilities( 4287): enable auto-mount
,I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(425ec388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c3dd48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 11 3 11
I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ac9908 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 8 3 16
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4308 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/WifiNative-wlan0(  907):    returned true
D/Process (  907): killProcessQuiet, pid=4004
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:101, mTXpacketCount:73, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4004:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4004
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4308): onCreate
D/ProviderChangeReceiver( 4308): ---------------------------------------------------
,D/ProviderChangeReceiver( 4308): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4308): start to updateAlertNotification!
D/Process (  907): killProcessQuiet, pid=3863
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4322 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3863:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3863
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AlertService( 4308): No fired or scheduled alerts
,D/HtcAlertUtils( 4308): -- cancelReminderNotification --
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
D/HtcAlertUtils( 4308): broadcastExistReminder!
I/Prism.ItemManager( 4180): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4180): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,V/Settings:HtcSettingsApplication( 4322): [4322/4322] onCreate()
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
W/ContextImpl( 4322): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  907): acquireWL(4267f9a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  907): releaseWL(4267f9a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3913
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3913:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3913
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(42449020): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42449020): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426ab128): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{426dd920 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  907): releaseWL(426ab128): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425ed2e0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425ed2e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425fff60): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425fff60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426b6988): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426b6988): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42534028): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42534028): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426f6cd8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426f6cd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426ad200): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426ad200): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425d9ed0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425d9ed0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 314 ms] updated apps [took 314 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4253c1a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
,D/PMS     (  907): releaseWL(4253c1a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2142): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2142): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2142): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  907): acquireWL(42668158): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(425d95a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425d95a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42772030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426c8440): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42772030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426c8440): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Prism.ItemManager( 4180): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 4180): loadItems() com.htc.launcher.pageview.WidgetManager@41b11bd0 +
,I/Prism.WidgetManager( 4180): onLoadItems() +
,I/Icing   ( 2142): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 -
,I/Icing   ( 2142): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(42668158): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Prism.WidgetManager( 4180): onLoadItems() -
,I/Prism.ItemManager( 4180): loadItems() com.htc.launcher.pageview.WidgetManager@41b11bd0 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425a4950 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  907): releaseWL(4259fa50): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 8 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(42727240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42727240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  907): mEventCount = 600
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=60 rxSum=50} preTxRxSum={txSum=60 rxSum=50}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19422 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19423 delay=15s
D/PMS     (  907): acquireWL(42729928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4231aca8: PendingIntentRecord{4232fdb8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=73464, Int=0
D/PMS     (  907): releaseWL(42729928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4272cd00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,D/Finsky  ( 4136): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4136): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/AlarmManager(  907): sending alarm PendingIntent{423ef770: PendingIntentRecord{426f14e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455019769835, Int=0
D/PMS     (  907): releaseWL(4272cd00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4136/10074),
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4136): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4136): [NET] getaddrinfo-,err=8
D/libc    ( 4136): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4136): [NET] getaddrinfo-, 1
D/libc    ( 4136): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =448e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4136): [NET] getaddrinfo_proxy-, success
,I/global  ( 4136): call createSocket() return a new socket.
D/libc    ( 4136): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4136): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4136): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4136): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4136): untagSocket(69) failed with errno -22
,D/Finsky  ( 4136): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=9 [21][2][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 9 times.
,W/NetworkManagementSocketTagger( 4136): untagSocket(69) failed with errno -22
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4136): untagSocket(69) failed with errno -22
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4136/10074)
,D/Finsky  ( 4136): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  907): acquireWL(427d0d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{423f3040: PendingIntentRecord{427d0658 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455019772267, Int=0
,D/PMS     (  907): acquireWL(427d7a88): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4136 10074 null
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/Finsky  ( 4136): [452] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1222): client connected with version: 8296000
D/PMS     (  907): releaseWL(427d0d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4136): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4136): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4136): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4136): [NET] getaddrinfo-,err=8
D/libc    ( 4136): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4136): [NET] getaddrinfo-, 1
,D/libc    ( 4136): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5a10 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4136): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  907): releaseWL(427d7a88): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=12 [62][8][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 91
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 10 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 110
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:196, mTXpacketCount:101, avgLinkspeed:22,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/AutoSetting( 1342): service - has update message, not stop
,D/AutoSetting( 1342): service - mHandler: update timezone
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1512): service - mHandler: update timezone
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1548): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1548): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ec4a78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 8 2 11
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 750
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 11 times.
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(427eead8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427eead8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=142 rxSum=127} preTxRxSum={txSum=60 rxSum=50}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19423 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19424 delay=15s
D/PMS     (  907): acquireWL(4276bde8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42234c88: PendingIntentRecord{4232fdb8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88469, Int=0
D/PMS     (  907): releaseWL(4276bde8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times.
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(42656358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PMS     (  907): releaseWL(42656358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1512): Don't start project servcice
,D/HtcModeClient( 1512): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1512): connectState: CONNECTION_READY = false
D/SilentMusic( 1512): call stop
D/HtcModeClient( 1512): close connection
,W/HtcModeClient( 1512): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1512): read the terminate packet, so break
,D/PMS     (  907): acquireWL(4262bdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{42395340: PendingIntentRecord{427446a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455019786425, Int=0
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4366 uid=10078 gids={50078}
V/AlarmManager(  907): sending alarm PendingIntent{41ba39b0: PendingIntentRecord{41ba3978 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455019791146, Int=60000
,D/PMS     (  907): releaseWL(4262bdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/SMSBackup( 4366): SMSBackupAgentService started
,D/SMSBackup( 4366): Checking restore status
D/SMSBackup( 4366): Restore complete
,D/SMSBackup( 4366): cancelCheckAlarm
,D/SMSBackup( 4366): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/Finsky  ( 4136): [443] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4136): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  907): killProcessQuiet, pid=4036
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4036:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4036
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Waited long enough for: ServiceRecord{427e48e8 u0 com.htc.htclocationservice/.AutoSettingService}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:196, mTXpacketCount:196, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  907): setLight #0: color=#3e
,V/LightsService(  907): setLight #0: color=#3b
,V/LightsService(  907): setLight #0: color=#34
,V/LightsService(  907): setLight #0: color=#2e
,V/LightsService(  907): setLight #0: color=#27
,V/LightsService(  907): setLight #0: color=#20
,V/LightsService(  907): setLight #0: color=#1a
,V/LightsService(  907): setLight #0: color=#14
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  907):    returned true,
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=142 rxSum=127} preTxRxSum={txSum=142 rxSum=127}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19424 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19425 delay=15s
D/PMS     (  907): acquireWL(423babb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{426afe60: PendingIntentRecord{4232fdb8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103478, Int=0
D/PMS     (  907): releaseWL(423babb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421bdbb0
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421bdbb0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41edc678
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@426a0df0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/PMS     (  907): acquireWL(426d9690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=103990, Int=0
,D/PMS     (  907): releaseWL(426d9690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1117): now=1455019800030 next=59970
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 342ms
,W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426874b0)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/InputMethodManagerService(  907): Disable input method client, pid=1273
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): acquireWL(41c6c098): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(41c6c098): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
I/WindowManager(  907): No lock screen! windowToken=null
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(4269c680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4269c680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2721): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2721): [MTP][onReceive]-
I/HtcPowerSaver(  907): << updateStatus
,D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1342): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  907): acquireWL(427a6c20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): releaseWL(427a6c20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3811): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3811): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3811): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3811): Cust_ConnectToPC   : spcsc>false
D/        ( 3811): Cust_ConnectToPC   : IPT>true
D/        ( 3811): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3811): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3811): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3811): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3811): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19426 delay=15s
,I/PSReceiver( 3811): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3811): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3811): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3811):  defaultType:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): BG scan when screen On
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): Match BG scan, scan!
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
I/ClockThread( 1117): stop update clock
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/WIFI_ICON( 1117): WifiActivity: 0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  907): updateScreenOn: false
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4389 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(42624600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42624600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(427d0eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1733): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1733): onScreenOn: 1455019800487
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1733): onScreenOn: 1455019800487
D/PMS     (  907): releaseWL(427d0eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41edc678
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41edc678, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@426a0df0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(425d96a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/SensorManager(  907): mEventCount = 900
I/FeedHostManager( 1273): [onPause]
,I/FeedProviderManager( 1273): onPause
,I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
,I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bde660
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19426 mDataStallAlarmIntent=PendingIntent{425db5c8: PendingIntentRecord{4232fdb8 android broadcastIntent}}
W/ContextImpl( 4389): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/PMS     (  907): acquireWL(4275b6d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/PMS     (  907): releaseWL(425d96a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  907): acquireWL(426e17d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4389 1000 null
,D/SmartSyncUtils( 4389): isEpsOn(), nState = 0
,D/PMS     (  907): releaseWL(426e17d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4389): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=4180
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4180:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4180
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,W/ContextImpl( 4389): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4389): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4389): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4389): getMobilePolicyEnabled, result = true
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a0df0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a0df0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  907): New client listening to asynchronous messages
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a0df0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a0df0
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a1380 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a1380 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/PhoneStatusBar( 1117): removeHeadsNotification.gc: 61
,D/AutoSetting( 1342): service - mHandler: cancel location update
,D/AutoSetting( 1342): service -           changes count: 0
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(4272b808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4272b808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(427e93f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427e93f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1733): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1733): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1733): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1733): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1733): onScreenOff
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4275b6d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1183): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1183): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1183): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1183): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-5,9
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1183): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1183): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1183): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000106475216
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000106475240
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000106475250
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000106475260
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42733020 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 106475216, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42733020 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42733020 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 106475240, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 106475250, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 106475260, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3875
I/ActivityManager(  907): Killing 3875:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3875
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  907): killProcessQuiet, pid=3890
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3890:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3890
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4263da00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{426e7d60: PendingIntentRecord{42504bc0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=118819, Int=0
,D/PMS     (  907): acquireWL(4263f0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4263da00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(427d3bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(427d3bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4263f0b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426fdea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(426fdea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426dfb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(4277d4f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427216d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1455019815106 tag=VacuumService
,D/PMS     (  907): releaseWL(426dfb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4277d4f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426b9738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  907): releaseWL(427216d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(426b9738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42761588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(42761588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427960d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(427960d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4279a070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4279a070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42751738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(427868b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427868b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427c2bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42751738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427c7ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(427c7ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 1774 seconds from now (1455019815856)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8e96 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(427c2bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427b6260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(427b6260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427bc908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(427bc908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1183): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1183): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1183): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1183): Add randomnes,s: count=24 entropy=13
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000123562128
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000106475240
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000123562152
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000123562163
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 123562128, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 106475240, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 123562152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 123562163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42838f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42838f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42839fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42414b40: PendingIntentRecord{426108a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135209, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  907): releaseWL(42839fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1342): service - handleMessage() stop self
,D/AutoSetting( 1342): service - handleMessage() quit looper
,D/AutoSetting( 1342): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3949
,I/ActivityManager(  907): Killing 3949:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3949
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42840758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235f290: PendingIntentRecord{4235fbd8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140881, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42841a60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42840758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4fa0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1183): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1183): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 le,n=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000140972339
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000140972359
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000123562163
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 140972339, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 140972359, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 123562163, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3234302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(42841a60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1183): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1183): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1183): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1183): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000158385481
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000158385506
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000158385517
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos,
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 158385481, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 158385506, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 158385517, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4289b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163989, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4289b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4289e1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
V/AlarmManager(  907): sending alarm PendingIntent{425a21e8: PendingIntentRecord{426a4780 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171162, Int=0
,D/PMS     (  907): releaseWL(4289e1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1183): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1183): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1183): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1183): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000158385481
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000175755000
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000175755013
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 158385481, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 175755000, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 175755013, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(428b4f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428b4f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1183): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1183): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1183): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1183): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000158385481
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000193169743
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000193169754
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 158385481, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 193169743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 193169754, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1183): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1183): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1183): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1183): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000210584462
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000210584488
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000210584500
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 210584462, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 210584488, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 210584500, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428df4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428df4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1183): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1183): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1183): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1183): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000227950648
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000227950674
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000227950685
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 227950648, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 227950674, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 227950685, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1183): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1183): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1183): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1183): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000245324872
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000245324898
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000245324909
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 245324872, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 245324898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 245324909, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/PMS     (  907): acquireWL(42614dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42614dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1183): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1183): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1183): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1183): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000262715192
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000262715230
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000245324909
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-60
I/wpa_supplicant( 1183): tsf=0000000262715218
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 262715192, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 262715230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 245324909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 262715218, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == (4) end of scan result ==
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1183): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1183): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1183): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1183): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (351) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000280140884
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000280140919
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-60
I/wpa_supplicant( 1183): tsf=0000000280140909
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 280140884, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 280140919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 280140909, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(424c1210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=283990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424c1210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1183): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1183): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1183): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1183): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1183): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1183): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1183): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000297555135
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000297555171
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-60
I/wpa_supplicant( 1183): tsf=0000000297555161
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=5
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000297555181
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 297555135, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 297555171, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 297555161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 297555181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(424d0d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424d0d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1183): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1183): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1183): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1183): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1183): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1183): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1183): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000314944778
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
,I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000314944814
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-60
I/wpa_supplicant( 1183): tsf=0000000314944804
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=5
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
,I/wpa_supplicant( 1183): tsf=0000000314944824
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 314944778, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 314944814, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 314944804, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 314944824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1183): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1183): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1183): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1183): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000332062073
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000332062097
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-60
I/wpa_supplicant( 1183): tsf=0000000314944804
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=5
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000332062107
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 332062073, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 332062097, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 314944804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 332062107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428f2b58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343990, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428f2b58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1183): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1183): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1183): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1183): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=,0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000349454858
,I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000349454884
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=5
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000349454895
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 349454858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 349454884, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 349454895, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1183): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1183): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: ,AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000366824907
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000366824932
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=5
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000349454895
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 366824907, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 366824932, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 349454895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426e5cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426e5cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=109 entropy=98
D/wpa_supplicant( 1183): Add randomness: count=110 entropy=99
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=111 entropy=100
D/wpa_supplicant( 1183): Add randomness: count=112 entropy=101
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS,: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000384214737
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000384214764
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 384214737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 384214764, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): add 2 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=113 entropy=102
D/wpa_supplicant( 1183): Add randomness: count=114 entropy=103
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=115 entropy=104
D/wpa_supplicant( 1183): Add randomness: count=116 entropy=105
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000401634939
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000401634965
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 401634939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 401634965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42848a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=403990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42848a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=117 entropy=106
D/wpa_supplicant( 1183): Add randomness: count=118 entropy=107
D/wpa_supplicant( 1183): Add randomness: count=119 entropy=108
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=120 entropy=109
D/wpa_supplicant( 1183): Add randomness: count=121 entropy=110
D/wpa_supplicant( 1183): Add randomness: count=122 entropy=111
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000419061915
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000419061941
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=6
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000419061952
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 419061915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 419061941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 419061952, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42858830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42858830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=123 entropy=112
D/wpa_supplicant( 1183): Add randomness: count=124 entropy=113
D/wpa_supplicant( 1183): Add randomness: count=125 entropy=114
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=126 entropy=115
D/wpa_supplicant( 1183): Add randomness: count=127 entropy=116
D/wpa_supplicant( 1183): Add randomness: count=128 entropy=117
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000436434746
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000436434771
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=6
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000436434782
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 436434746, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 436434771, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 436434782, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=129 entropy=118
D/wpa_supplicant( 1183): Add randomness: count=130 entropy=119
D/wpa_supplicant( 1183): Add randomness: count=131 entropy=120
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=132 entropy=121
D/wpa_supplicant( 1183): Add randomness: count=133 entropy=122
D/wpa_supplicant( 1183): Add randomness: count=134 entropy=123
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000453801786
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000453801812
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=6
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000453801823
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 453801786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 453801812, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 453801823, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/PMS     (  907): acquireWL(428cc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428cc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=135 entropy=124
D/wpa_supplicant( 1183): Add randomness: count=136 entropy=125
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=137 entropy=126
D/wpa_supplicant( 1183): Add randomness: count=138 entropy=127
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000471184801
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000471184828
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=6
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000453801823
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 471184801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 471184828, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 453801823, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=139 entropy=128
D/wpa_supplicant( 1183): Add randomness: count=140 entropy=129
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
,I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=141 entropy=130
D/wpa_supplicant( 1183): Add randomness: count=142 entropy=131
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
,I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000488544901
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000488544927
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 488544901, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 488544927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/PMS     (  907): acquireWL(428d7270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428d7270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=143 entropy=132
D/wpa_supplicant( 1183): Add randomness: count=144 entropy=133
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=145 entropy=134
D/wpa_supplicant( 1183): Add randomness: count=146 entropy=135
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000505924647
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000505924673
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 505924647, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 505924673, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 2 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=147 entropy=136
D/wpa_supplicant( 1183): Add randomness: count=148 entropy=137
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=149 entropy=138
D/wpa_supplicant( 1183): Add randomness: count=150 entropy=139
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000523344732
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000523344758
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 523344732, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 523344758, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 2 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/PMS     (  907): acquireWL(42742658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=523990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42742658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=151 entropy=140
D/wpa_supplicant( 1183): Add randomness: count=152 entropy=141
D/wpa_supplicant( 1183): Add randomness: count=153 entropy=142
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=154 entropy=143
D/wpa_supplicant( 1183): Add randomness: count=155 entropy=144
D/wpa_supplicant( 1183): Add randomness: count=156 entropy=145
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000540742167
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000540742193
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=7
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-87
I/wpa_supplicant( 1183): tsf=0000000540742204
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 540742167, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 540742193, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 540742204, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4288c590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4288c590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=157 entropy=146
D/wpa_supplicant( 1183): Add randomness: count=158 entropy=147
D/wpa_supplicant( 1183): Add randomness: count=159 entropy=148
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=160 entropy=149
D/wpa_supplicant( 1183): Add randomness: count=161 entropy=150
D/wpa_supplicant( 1183): Add randomness: count=162 entropy=151
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000558174275
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000558174301
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=7
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-87
I/wpa_supplicant( 1183): tsf=0000000558174312
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 558174275, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 558174301, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 558174312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=163 entropy=152
D/wpa_supplicant( 1183): Add randomness: count=164 entropy=153
D/wpa_supplicant( 1183): Add randomness: count=165 entropy=154
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=166 entropy=155
D/wpa_supplicant( 1183): Add randomness: count=167 entropy=156
D/wpa_supplicant( 1183): Add randomness: count=168 entropy=157
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplic,ant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000575602110
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000575602136
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=7
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-87
I/wpa_supplicant( 1183): tsf=0000000575602148
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 575602110, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 575602136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 575602148, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(426e0b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=583990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426e0b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=169 entropy=158
D/wpa_supplicant( 1183): Add randomness: count=170 entropy=159
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=171 entropy=160
D/wpa_supplicant( 1183): Add randomness: count=172 entropy=161
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
,I/wpa_supplicant( 1183): tsf=0000000592964741
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000592964767
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=7
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-87
I/wpa_supplicant( 1183): tsf=0000000575602148
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos,
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 592964741, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 592964767, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 575602148, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=173 entropy=162
D/wpa_supplicant( 1183): Add randomness: count=174 entropy=163
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=175 entropy=164
D/wpa_supplicant( 1183): Add randomness: count=176 entropy=165
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000610351927
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000610351953
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 610351927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 610351953, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42860c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42860c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=177 entropy=166
D/wpa_supplicant( 1183): Add randomness: count=178 entropy=167
D/wpa_supplicant( 1183): Add randomness: count=179 entropy=168
D/wpa_supplicant( 1183): Add randomness: count=180 entropy=169
D/wpa_supplicant( 1183): Add randomness: count=181 entropy=170
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1183): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49,
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=182 entropy=171
D/wpa_supplicant( 1183): Add randomness: count=183 entropy=172
D/wpa_supplicant( 1183): Add randomness: count=184 entropy=173
D/wpa_supplicant( 1183): Add randomness: count=185 entropy=174
D/wpa_supplicant( 1183): Add randomness: count=186 entropy=175
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (643) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000627775056
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000627775081
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=8
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000627775092
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=9
I/wpa_supplicant( 1183): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000627775103
I/wpa_supplicant( 1183): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC Wi-Free
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=10
,I/wpa_supplicant( 1183): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000627775112
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC0039325
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 627775056, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 627775081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 627775092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 627775103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 627775112, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=3542
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3542:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3542): Died!
,I/ActivityManager(  907): Recipient 3542
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427b9858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=643990, Int=0
,D/PMS     (  907): releaseWL(427b9858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=187 entropy=176
D/wpa_supplicant( 1183): Add randomness: count=188 entropy=177
D/wpa_supplicant( 1183): Add randomness: count=189 entropy=178
D/wpa_supplicant( 1183): Add randomness: count=190 entropy=179
D/wpa_supplicant( 1183): Add randomness: count=191 entropy=180
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1183): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49,
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=192 entropy=181
D/wpa_supplicant( 1183): Add randomness: count=193 entropy=182
D/wpa_supplicant( 1183): Add randomness: count=194 entropy=183
D/wpa_supplicant( 1183): Add randomness: count=195 entropy=184
D/wpa_supplicant( 1183): Add randomness: count=196 entropy=185
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (643) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000645206829
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000645206854
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=8
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000645206865
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=9
I/wpa_supplicant( 1183): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000645206874
I/wpa_supplicant( 1183): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC Wi-Free
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=10
I/wpa_supplicant( 1183): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000645206884
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC0039325
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 645206829, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 645206854, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 645206865, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 645206874, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 645206884, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=197 entropy=186
D/wpa_supplicant( 1183): Add randomness: count=198 entropy=187
D/wpa_supplicant( 1183): Add randomness: count=199 entropy=188
D/wpa_supplicant( 1183): Add randomness: count=200 entropy=189
D/wpa_supplicant( 1183): Add randomness: count=201 entropy=190
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1183): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49,
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1183): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1183): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1183): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=202 entropy=191
D/wpa_supplicant( 1183): Add randomness: count=203 entropy=192
D/wpa_supplicant( 1183): Add randomness: count=204 entropy=193
D/wpa_supplicant( 1183): Add randomness: count=205 entropy=194
D/wpa_supplicant( 1183): Add randomness: count=206 entropy=195
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (643) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000662581737
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000662581763
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=8
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000662581774
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=9
I/wpa_supplicant( 1183): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000662581783
I/wpa_supplicant( 1183): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC Wi-Free
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=10
I/wpa_supplicant( 1183): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000662581792
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC0039325
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 662581737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 662581763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 662581774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 662581783, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 662581792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427fe3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427fe3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=207 entropy=196
D/wpa_supplicant( 1183): Add randomness: count=208 entropy=197
D/wpa_supplicant( 1183): Add randomness: count=209 entropy=198
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=210 entropy=199
D/wpa_supplicant( 1183): Add randomness: count=211 entropy=200
D/wpa_supplicant( 1183): Add randomness: count=212 entropy=201
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (643) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000679965016
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000679965042
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=8
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000679965053
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=9
I/wpa_supplicant( 1183): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91,
I/wpa_supplicant( 1183): tsf=0000000662581783
I/wpa_supplicant( 1183): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC Wi-Free
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=10
I/wpa_supplicant( 1183): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1183): freq=2462
I/wpa_supplicant( 1183): level=-91
I/wpa_supplicant( 1183): tsf=0000000662581792
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=UPC0039325
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 679965016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 679965042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 679965053, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 662581783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 662581792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=213 entropy=202
D/wpa_supplicant( 1183): Add randomness: count=214 entropy=203
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=215 entropy=204
D/wpa_supplicant( 1183): Add randomness: count=216 entropy=205
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000697340860
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000697340886
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=8
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000679965053
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 697340860, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 697340886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 679965053, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/PMS     (  907): acquireWL(429064e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=703989, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(429064e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=217 entropy=206
D/wpa_supplicant( 1183): Add randomness: count=218 entropy=207
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=219 entropy=208
D/wpa_supplicant( 1183): Add randomness: count=220 entropy=209
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000714694802
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000714694828
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 714694802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 714694828, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(429198c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429198c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
W/ContextImpl( 4389): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3811): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3811): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3811): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3811): Cust_ConnectToPC   : spcsc>false
D/        ( 3811): Cust_ConnectToPC   : IPT>true
,D/        ( 3811): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3811): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3811): Index of the first 1 = 3
W/ContextImpl( 3811): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3811): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3811): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3811): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3811): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 3811): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3811): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=221 entropy=210
D/wpa_supplicant( 1183): Add randomness: count=222 entropy=211
D/wpa_supplicant( 1183): Add randomness: count=223 entropy=212
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=224 entropy=213
D/wpa_supplicant( 1183): Add randomness: count=225 entropy=214
D/wpa_supplicant( 1183): Add randomness: count=226 entropy=215
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000732111635
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000732111661
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=11
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-86
I/wpa_supplicant( 1183): tsf=0000000732111672
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 732111635, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 732111661, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 732111672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=227 entropy=216
D/wpa_supplicant( 1183): Add randomness: count=228 entropy=217
D/wpa_supplicant( 1183): Add randomness: count=229 entropy=218
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=230 entropy=219
D/wpa_supplicant( 1183): Add randomness: count=231 entropy=220
D/wpa_supplicant( 1183): Add randomness: count=232 entropy=221
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000749464932
,I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000749464957
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=11
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000749464968
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 749464932, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 749464957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 749464968, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(4294b588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=763990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4294b588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=233 entropy=222
D/wpa_supplicant( 1183): Add randomness: count=234 entropy=223
D/wpa_supplicant( 1183): Add randomness: count=235 entropy=224
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=236 entropy=225
D/wpa_supplicant( 1183): Add randomness: count=237 entropy=226
D/wpa_supplicant( 1183): Add randomness: count=238 entropy=227
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000766841813
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000766841839
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=11
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000766841850
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 766841813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 766841839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 766841850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42962618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42962618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=239 entropy=228
D/wpa_supplicant( 1183): Add randomness: count=240 entropy=229
D/wpa_supplicant( 1183): Add randomness: count=241 entropy=230
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=242 entropy=231
D/wpa_supplicant( 1183): Add randomness: count=243 entropy=232
D/wpa_supplicant( 1183): Add randomness: count=244 entropy=233
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000784224819,
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000784224846
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=11
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000784224857
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 784224819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 784224846, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 784224857, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4297c368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4297c368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=245 entropy=234
D/wpa_supplicant( 1183): Add randomness: count=246 entropy=235
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=247 entropy=236
D/wpa_supplicant( 1183): Add randomness: count=248 entropy=237
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000801605131
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000801605156
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=11
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000784224857
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 801605131, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 801605156, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 784224857, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=249 entropy=238
D/wpa_supplicant( 1183): Add randomness: count=250 entropy=239
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=251 entropy=240
D/wpa_supplicant( 1183): Add randomness: count=252 entropy=241
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000818981081
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000818981107
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 818981081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 818981107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42642170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=823990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42642170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=253 entropy=242
D/wpa_supplicant( 1183): Add randomness: count=254 entropy=243
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1183): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=255 entropy=244
D/wpa_supplicant( 1183): Add randomness: count=256 entropy=245
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000836354976
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000836355002
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 836354976, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 836355002, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 2 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Disconnect event
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1183): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7716bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1183): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:,00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/PMS     (  907): acquireWL(4259ea50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41ce7458: PendingIntentRecord{42430f60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778937, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4442 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{41f9b3c8: PendingIntentRecord{423fc988 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455019906979, Int=10800000
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
,D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19427 mDataStallAlarmIntent=null
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): releaseWL(4259ea50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(4248d9d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 3811): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3811): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3811): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3811): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  907): New client listening to asynchronous messages
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,V/NativeCrypto( 1367): Read error: ssl=0x65ed3db0: I/O error during system call, Connection timed out
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:3   entry:0xb87d5590  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb87d9e40  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb87d9d90  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb87d5988  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb87d9f70  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb87d0c20  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb87d5458  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb87d52a8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x65ed3db0: I/O error during system call, Broken pipe
D/PMS     (  907): acquireWL(425f00b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
D/PMS     (  907): acquireWL(42633070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1367/10029)
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 76
,D/wpa_supplicant( 1183): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SCAN
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  907): releaseWL(425f00b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/Process (  907): killProcessQuiet, pid=3760
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4442/10049)
I/ActivityManager(  907): Killing 3760:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/PMS     (  907): releaseWL(42633070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ActivityManager(  907): Recipient 3760
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
,I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:2
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
V/Tethering(  907): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4461 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4279abf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(4279abf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/CaptivePortalTracker(  907): NoActiveNetworkState
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,I/MusicStore( 4461): Database version: 95
,W/ContextImpl( 4461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4461, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4461): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 4461): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2721/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4461/10154)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4481 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4461): getSelectedRoute
,I/NetworkMonitor( 4461): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4461/10154)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4461, uid=10154, userID:0
,D/ACRA    ( 4481): ACRA is enabled for com.facebook.katana, intializing...
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(427ee1c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/PMS     (  907): releaseWL(427ee1c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/Process (  907): killProcessQuiet, pid=3431
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3431:com.htc.task/u0a71 (adj 15): empty #17
,W/SystemClassLoaderAdder( 4481): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4481): Preparing secondary program dexes.
V/DexLibLoader( 4481): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4481): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4481): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4481): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.,
V/DexLibLoader( 4481): Creating class loader
V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
V/DexLibLoader( 4481): Creating class loader
V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader
,V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader
V/DexLibLoader( 4481): Finished creating class loader
,V/DexLibLoader( 4481): Verifying classes from secondary dexes.
,D/DexLibLoader( 4481): DexLibLoader.ensureDexLoaded took 17 ms
,I/ActivityManager(  907): Recipient 3431
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4481): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
,I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=257 entropy=246
D/wpa_supplicant( 1183): Add randomness: count=258 entropy=247
D/wpa_supplicant( 1183): Add randomness: count=259 entropy=248
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1183):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): No APs found - clear blacklist and try again
E/wpa_supplicant( 1183): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1183): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 2
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb77184e8  current_ssid=0x0
D/wpa_supplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed,, trigger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb77184e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1183): nl80211: Unsubscribe mgmt frames handle 0xb7717718 (mode change)
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7717718
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7717718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1183):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183):   * freq=2412
D/wpa_supplicant( 1183):   * Auth Type 0
D/wpa_supplicant( 1183):   * WPA Versions 0x2
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1183): nl80211: Connect request send successfully
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/HTCRequest(,  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
,E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (377) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000842231512
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000842231532
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=12
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-85
I/wpa_supplicant( 1183): tsf=0000000842231542
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 842231512, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 842231532, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 842231542, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Connect event
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1183): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Add randomness: count=260 entropy=249
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1183): EAPOL: enable timer tick
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): Get randomness: len=32 entropy=250
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplic,antStateChange(): SSIDNG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/dalvikvm( 4481): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb77179f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f71b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1183): set send_ind_to_ndc = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1183): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WISPrService( 3811): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3811): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,E/FbInjectorInitializer( 4481): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42727970): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1183): nl80211: Event message available
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1183): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1183): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425fb7c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425fb7c8 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4481): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.506MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3844
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3844:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3844
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4510 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,D/AutoSetting( 1342): Util - no network available!
,D/AutoSetting( 1342): service - onCreate()
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/AutoSetting( 1342): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  907): request 424d42c0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1342): service - mHandler: cancel location update
,D/AutoSetting( 1342): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4510): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4510): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4481): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10079)
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4526 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10079)
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4540 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  907): Killing 4287:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4287
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  907): Recipient 4287
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.955MB for 84664-byte allocation
,E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4540): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.969MB for 28144-byte allocation
,E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4481): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4481): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4481): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4481): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4481): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.035MB for 39954-byte allocation
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.111MB for 79892-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
,V/WebViewChromiumFactoryProvider( 4540): Binding Chromium to main looper Looper (main, tid 1) {41aa0238}
,I/LibraryLoader( 4540): Expected native library version number "",actual native library version number ""
I/chromium( 4540): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4540): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(4273c488): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  907): acquireWL(426e6a70): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4540): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(4273c488): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4540): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4540): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4540): Local Branch: 
I/Adreno-EGL( 4540): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4540): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4540):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4540): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,I/iu.Environment( 2142): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2142): num queued entries: 0
,I/iu.UploadsManager( 2142): num updated entries: 0
,I/iu.SyncManager( 2142): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4292b700 u0 ReceiverList{4292b5e0 4481 com.facebook.katana/10027/u0 remote:4292b228}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4292b700 u0 ReceiverList{4292b5e0 4481 com.facebook.katana/10027/u0 remote:4292b228}}
,D/Process (  907): killProcessQuiet, pid=4308
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4298b370 u0 ReceiverList{4298b310 4481 com.facebook.katana/10027/u0 remote:42988338}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
I/ActivityManager(  907): Killing 4308:com.htc.calendar/u0a13 (adj 15): empty #17
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,I/ActivityManager(  907): Recipient 4308
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  907): acquireWL(428fa868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428fa868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): acquireWL(426bf270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(426bf270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(42727970): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  907): default: setTeardownRequested(true)
,D/WISPrService( 3811): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1183): Change stage from stage0 to stage3
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424267a8
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(42718cc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10079)
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:4
,D/PMS     (  907): acquireWL(42982730): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,D/PMS     (  907): acquireWL(428c39e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2142): Checkin interval check for package: unspecified last checkin: 1455019751425 min interval config: 0 actual interval: 789388
D/PMS     (  907): releaseWL(42982730): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2142): Checking schedule, now: 1455020540824 next: 1455019781390
,I/CheckinService( 2142): active receiver: enabled
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2142, uid=10029, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
I/CheckinService( 2142): Preparing to send checkin request
I/EventLogService( 2142): Accumulating logs since 1455019746919
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42718cc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2142): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2142): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2142/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4615 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4615): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4615): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4615): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4615): install
,I/MultiDex( 4615): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4615): loading existing secondary dex files
,I/MultiDex( 4615): load found 3 secondary dex files
,I/MultiDex( 4615): install done
,W/dalvikvm( 4615): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4615): VFY: unable to resolve instance field 36
,W/dalvikvm( 4615): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4615): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4615): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4615): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4615): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4615): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4615): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4615): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4615): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,E/MDM     ( 1222): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 4615): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2142): Restart initialization of location
D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,D/NativeLibraryUtils( 4615): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(4296f9c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4296f9c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=919594092
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  907): releaseWL(4248d9d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,W/Settings( 4615): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 4461): type=WIFI subType= reason=null isConnected=true
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10079)
D/PMS     (  907): acquireWL(4289cef8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4461/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,D/PMS     (  907): releaseWL(4289cef8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/Tethering(  907): Found interface wlan0
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(427a34d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
D/PMS     (  907): releaseWL(427a34d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2721/10021)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1342): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1342): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1342): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4110/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/CheckinService( 2142): Checkin interval check for package: unspecified last checkin: 1455019751425 min interval config: 0 actual interval: 790491
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(426a5958): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426a5958): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2142, uid=10029, userID:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2142): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2142): num queued entries: 0
,I/iu.UploadsManager( 2142): num updated entries: 0
,I/iu.SyncManager( 2142): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =496a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  907): acquireWL(425e22c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4615/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/PMS     (  907): releaseWL(426e6a70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(424e70a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  907): releaseWL(425e22c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(424e70a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4481): Called registerBroadcastReceiver twice.
D/PMS     (  907): acquireWL(4233b280): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(4233b280): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41abe568): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4461 10154 null
,W/ContextImpl( 4461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4461, uid=10154, userID:0
I/MusicLeanback( 4461): Conditions not met for autocaching.
,I/MusicLeanback( 4461): Stop autocaching.
,W/ContextImpl( 4461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(41abe568): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4481/10027)
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2805625403
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4615): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4615): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4615): Local Branch: 
I/Adreno-EGL( 4615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4615): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4615):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4615): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4615): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4615): Local Branch: 
I/Adreno-EGL( 4615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4615): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4615):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/Adreno-EGL( 4615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4615): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4615): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4615): Local Branch: 
I/Adreno-EGL( 4615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4615): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4615):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2142): Classify the device as Phone.
,D/libc    ( 2142): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2142): [NET] getaddrinfo-,err=8
,V/NativeCrypto( 2142): SSL shutdown failed: ssl=0x6e6b9868: I/O error during system call, Connection timed out
D/libc    ( 2142): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2142): [NET] getaddrinfo-, 1
D/libc    ( 2142): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a820 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 140
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2142): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2142): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2142): [NET] getaddrinfo-,err=8
,D/libc    ( 2142): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2142): [NET] getaddrinfo-,err=8
D/libc    ( 2142): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2142): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2142): Sending checkin request (12092 bytes)
,I/CheckinRequestBuilder( 2142): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2142): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2142/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=15 [19][3][0]
,I/CheckinRequestBuilder( 2142): Classify the device as Phone.
,I/CheckinTask( 2142): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2142): Checking schedule, now: 1455020543721 next: 1455543480715
,I/CheckinService( 2142): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2142, uid=10029, userID:0
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =abb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,I/CheckinService( 2142): Checking schedule, now: 1455020543753 next: 1455543480715
,I/CheckinService( 2142): active receiver: disabled
,D/CheckinService( 2142): Recording last checkin time for package unspecified as 1455020543759
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2142, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024627
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024700
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025840
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028543
,D/PMS     (  907): releaseWL(428c39e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2142/10029)
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4540): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=4322
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4322:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4322
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42737ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42737ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireWL(4283ae08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4196 10111 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): releaseWL(4283ae08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  907): acquireWL(427a6be0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
D/PMS     (  907): releaseWL(427a6be0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  907): acquireWL(42652a58): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42652a58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  907): acquireWL(42730d98): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42730d98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(4284b2f0): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): releaseWL(4284b2f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  907): acquireWL(426b92a8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426b92a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(4279eb58): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2142): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2142): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2142): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{428ead90 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 535 ms] updated apps [took 534 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(426b7d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426b7d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(42782948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42782948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(428a4610): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428a4610): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2142): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2142): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(4279eb58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{428cc988 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/AutoSetting( 1342): service - mHandler: update timezone
D/AutoSetting( 1342): service - handleMessage() stop self
,D/AutoSetting( 1342): service - handleMessage() quit looper
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1342): service - onDestroy() END
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  907): batLight: Full, plugged
,V/LightsService(  907): setLight #8: color=#c8c800
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1512): service - mHandler: update timezone
,D/DotMatrix( 1548): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1548): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1548): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1548): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41aefe58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  907): acquireWL(42855338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=883989, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42855338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42760e30 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(428a2ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(428a2ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4056
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4056:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4056
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(427892c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(427892c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42892308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943990, Int=0
,D/PMS     (  907): releaseWL(42892308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42882e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42882e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42851260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42851260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(428874f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003989, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428874f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42740918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,W/ContextImpl( 4389): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  907): sending alarm PendingIntent{422c4590: PendingIntentRecord{425cf8d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455020627342, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{4238db68: PendingIntentRecord{4272a420 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455020701116, Int=0
,D/PowerUsageService( 4389): call getInstance()
,D/SmartSyncUtils( 4389): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4389): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4389): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4389): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4389): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4389): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082016000
,D/SmartSyncScreenOnOffTimeReceiver( 4389): SettingOffTime = 1455069600000, randomSettingOffTime = 1455071813000
D/PMS     (  907): acquireWL(428e7550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4389 1000 null
,D/PMS     (  907): releaseWL(42740918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4389): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4389): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4389): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(428e7550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  907): Grow heap (frag case) to 18.448MB for 171096-byte allocation
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(42343378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42343378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41dea2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1063990, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41dea2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4266b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4266b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(423a5238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(423a5238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41fad240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1123989, Int=0
,D/PMS     (  907): releaseWL(41fad240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41b96398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41b96398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425ecf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(425ecf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4264d3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1183990, Int=0
,D/PMS     (  907): releaseWL(4264d3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4239a960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PMS     (  907): releaseWL(4239a960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42435eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42435eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(42462c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b30fa0: PendingIntentRecord{422a7128 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1243990, Int=0
,D/PMS     (  907): releaseWL(42462c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425cc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(425cc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+,
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1548): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4702): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4702): ====startRecUseTime====
D/htc.customization.log.level( 4702):  is 
W/CustomizationLogLevel( 4702): Level value is invalid, use default level 2
D/CustomizationManager( 4702):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4702): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4702): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4702): Parsing tag category name = system
I/CustomizationCIDLoader( 4702): Parsing tag category name = application
I/CustomizationCIDLoader( 4702): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4702): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4702): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4702): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4702): Parsing tag category name = Settings
D/CustomizationManager( 4702):  Read CID file spent 0.161 (s)
D/CustomizationManager( 4702):  All configurations done spent 0.161 (s)
W/HtcNativeFlag( 4702): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4702): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4702): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4702): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4702, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{42182dc8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  907): Skipping PackageSetting{4218e408 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1548): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1548): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  907): acquireWL(427a5040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1548): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/PackageManager(  907): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  907): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  907): releaseWL(427a5040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1286): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4716 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4716): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4716): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4716): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4716): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4716): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4716): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4716): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4716): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4716): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4716): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4716): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4716): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4716): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4716): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4716): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4716): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4716): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4716): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4716): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4716): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4716): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4716): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4716): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4716): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4716): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4716): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4716): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4716): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4716): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4716): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4716): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4716): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4716): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4716): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4716): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4716): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4716): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4716): threadid=11: thread exiting with uncaught exception (group=0x4166ce30)
E/AndroidRuntime( 4716): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4716): Process: com.google.android.apps.docs, PID: 4716
E/AndroidRuntime( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4716): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4716): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4716): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4716): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4716): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
E/SQLiteDatabase( 4716): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4716): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4716): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4716): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4716): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4716): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4716): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4716): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4716): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4716): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4716): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4716): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4716): Opened ClientFlag.db in read-only mode
D/Process ( 4716): killProcess, pid=4716
D/Process ( 4716): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4734 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4716
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4716) has died.
W/ContextImpl( 4734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4734): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4734): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4734): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4734): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4734): threadid=10: thread exiting with uncaught exception (group=0x4166ce30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4748 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4734): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4734): Process: com.android.keychain, PID: 4734
E/AndroidRuntime( 4734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4734): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4734): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4734): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4734): killProcess, pid=4734
D/Process ( 4734): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455020964874.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
I/ActivityManager(  907): Recipient 4734
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4734) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4748): getInstance(Context context)
W/PackageManager(  907): Unable to load service info ResolveInfo{424289f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/AppTag  ( 4748): getInstance(Context context)
D/AppTag  ( 4748): onCreate()
D/PMS     (  907): acquireWL(426779f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
D/PMS     (  907): releaseWL(426779f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  907): killProcessQuiet, pid=4366
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4366:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4366
W/dalvikvm( 4136): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2142): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2142): Clearing selected account for com.test.thalitest
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2142): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2142): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2142): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2142): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2142): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2142): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2142): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2142): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2142): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2142): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2142): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2142): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2142): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2142): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2142): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2142): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2142): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2142): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2142): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fb30 +
I/Prism.WidgetManager( 1273): onLoadItems() +
W/dalvikvm( 2142): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2142): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2142): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2142): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2142): App measurement is starting up, version: 8489
I/GMPM-SVC( 2142): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteDatabase( 2142): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2142): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2142): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2142): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2142): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2142): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 2142): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2142): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2142): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2142): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2142): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2142): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2142): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2142): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2142): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 2142): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 2142): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 2142): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 2142): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SQLiteLog( 2142): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2142): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655f9a90
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
W/GMPM-SVC( 2142): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/DriveAsyncService( 2142): disk I/O error (code 3850)
E/DriveAsyncService( 2142): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2142): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2142): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2142): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2142): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2142): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2142): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2142): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2142): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2142): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2142): 	at java.lang.Thread.run(Thread.java:864)
E/GMPM-SVC( 2142): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteLog( 2142): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2142): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6e81c088
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
W/dalvikvm( 2142): threadid=49: thread exiting with uncaught exception (group=0x4166ce30)
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2142): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2142): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2142): Process: com.google.android.gms, PID: 2142
E/AndroidRuntime( 2142): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2142): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2142): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2142): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2142): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2142): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2142): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2142): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2142): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2142): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2142): killProcess, pid=2142
D/Process ( 2142): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/PMS     (  907): acquireWL(4254c3e8): PARTIAL_WAKE_LOCK  Icing 0x1 2142 10029 WorkSource{10029 com.google.android.gms}
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Recipient 2142
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2142) has died.
D/PMS     (  907): handleWLDeath(4254c3e8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10996ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10995ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20995ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30995ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 40994ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 50994ms
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start

```
