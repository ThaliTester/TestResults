#### Test 583805003a0697c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  903): Resuming delayed broadcast
--------- beginning of /dev/log/main
D/Process (  903): killProcessQuiet, pid=3624
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3887 uid=10081 gids={50081, 5001, 1028, 1015}
I/ActivityManager(  903): Killing 3624:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3624
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3887): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3887): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3887): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/CheckinRequestBuilder( 2174): Classify the device as Phone.
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
D/Process (  903): killProcessQuiet, pid=3675
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2174): [NET] getaddrinfo-, 1
D/libc    ( 2174): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
I/ActivityManager(  903): Killing 3675:com.htc.stock/u0a82 (adj 15): empty #17
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8022 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2174): [NET] getaddrinfo_proxy-, success
D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Recipient 3675
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DFPI.ApkInstallService( 3654): onHandleIntent
I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/HtcModeClient( 1516): handler message = 4011
E/HtcModeClient( 1516): Check connection and retry 5 times.
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3887): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3887): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3887): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
D/libc    ( 2174): [NET] getaddrinfo-,err=8
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/CheckinTask( 2174): Sending checkin request (12416 bytes)
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoTaskReceiver
I/ActivityManager(  903): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3913 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
I/EASAppSvc( 3913): [ NA ]- onCreate()
I/EASAppSvc( 3913): [ NA ]> onUpgrade: version = 63
D/ORMLib  ( 3593): put()
E/cutils-trace( 3904): Error opening trace file: No such file or directory (2)
I/EASAppSvc( 3913): [ NA ]- onDestroy()
I/EASAppSvc( 3913): [ NA ]> uninitEASService
D/WifiService(  903): New client listening to asynchronous messages
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (3913/10064)
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (3913/10064)
D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (3913/10064)
D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3654): onHandleIntent
I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Resuming delayed broadcast
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3887): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3887): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3887): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): TurnFileToMediaUriService [checkFileExistence]
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/CustomizationManager( 3904): ====startRecUseTime====
D/htc.customization.log.level( 3904):  is 
W/CustomizationLogLevel( 3904): Level value is invalid, use default level 2
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/EASRequestController( 3913): [ NA ]release
I/EASAppSvc( 3913): [ NA ]< uninitEASService
I/EASAppSvc( 3913): [ NA ]- onCreate()
I/EASAppSvc( 3913): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (3913/10064)
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (3913/10064)
D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (3913/10064)
D/ORMLib  ( 3593): put()
D/WIFI_ICON( 1112): WifiActivity: 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/CustomizationManager( 3904):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3904): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3904): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3904): Parsing tag category name = system
I/EASAppSvc( 3913): [ NA ]- onDestroy()
I/EASAppSvc( 3913): [ NA ]> uninitEASService
I/EASRequestController( 3913): [ NA ]release
I/CustomizationCIDLoader( 3904): Parsing tag category name = application
I/CustomizationCIDLoader( 3904): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3904): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3904): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3904): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3904): Parsing tag category name = Settings
D/CustomizationManager( 3904):  Read CID file spent 0.125 (s)
D/CustomizationManager( 3904):  All configurations done spent 0.125 (s)
I/EASAppSvc( 3913): [ NA ]< uninitEASService
W/HtcNativeFlag( 3904): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3904): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3904): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3904): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  903): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3960 uid=10068 gids={50068, 3003, 5012}
I/MediaStoreImporter( 3844): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  903): Resuming delayed broadcast
D/Process (  903): killProcessQuiet, pid=3688
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3688:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3688
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  903): Resuming delayed broadcast
D/DFPI.PIReciver( 3654): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3654): onHandleIntent
I/DFPI.ApkInstallService( 3654): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3654): check CID = HTC__032
I/DFPI.ApkInstallService( 3654): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3904
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3887): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3887): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3887): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3887): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3887): MODE_GSM access default DB
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2174, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2174, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2174, uid=10029, userID:0
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3887): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
D/ORMLib  ( 3593): put()
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1369): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3887): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
W/AccTypeManager( 1369): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1369): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 3713): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3713): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 3887): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/dalvikvm-heap( 1270): Grow heap (frag case) to 13.250MB for 53840-byte allocation
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3887): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/ActivityManager(  903): Resuming delayed broadcast
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/CheckinResponseProcessor( 2174): From server: 1 gservices updates and 0 deletes
E/ExternalAccountType( 1369): Unsupported attribute readOnly
D/PMS     (  903): releaseWL(4279d4f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/MediaStoreImporter( 3844): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/Process (  903): killProcessQuiet, pid=3713
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3713:com.htc.sense.news/u0a76 (adj 15): empty #17
D/PMS     (  903): acquireWL(42f77ad8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1516 10014 null
I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  903): releaseWL(42f77ad8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1236): bind: false
D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3982 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
I/ActivityManager(  903): Recipient 3713
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CertBlacklister(  903): Certificate blacklist changed, updating...
I/CertBlacklister(  903): Certificate blacklist updated
I/GservicesProvider( 1357): main difference update completed
D/Process (  903): killProcessQuiet, pid=3730
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
D/PMS     (  903): acquireWL(42f14480): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
I/ActivityManager(  903): Killing 3730:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  903): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  903): Recipient 3730
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): releaseWL(42f14480): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=5 [19][1][0]
I/CheckinRequestBuilder( 2174): Classify the device as Phone.
D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
I/CheckinTask( 2174): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
I/CheckinService( 2174): Checking schedule, now: 1455056110754 next: 1455579047735
I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
D/CheckinService( 2174): Recording last checkin time for package unspecified as 1455056110794
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/PMS     (  903): releaseWL(42f14b70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  903): Unable to load service info ResolveInfo{42f20c18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/RemoteDisplayProvider(  903): start
,D/NotificationService(  903): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1112): com.htc.updater (true,33751552)
I/ActivityManager(  903): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4004 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42697240 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=108 rxSum=98} preTxRxSum={txSum=0 rxSum=0}
,D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19865 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19866 delay=15s
,I/RemoteViews.Performance( 1112): com.htc.updater 4 10 1 10
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1112): com.htc.updater (true,33751552)
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{426f4a90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.updater 1 9 0 10
,D/PMS     (  903): acquireWL(42fef1a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fef1a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  903): applying state to connected service
,D/LocationProviderProxy(  903): applying state to connected service
D/PMS     (  903): acquireWL(42ffd710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430008e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(430008e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43005d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43005d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430072a0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42ffd710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(430072a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4004): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 -
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  903): acquireWL(4300ff40): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3747
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3747:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3747
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
D/PMS     (  903): releaseWL(4300ff40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
D/PMS     (  903): acquireWL(42f7fd98): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4004): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4004): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4004): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4004): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  903): releaseWL(42f7fd98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42f7fca8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f7fca8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f7b4a8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f7b4a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f6d2b8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f6d2b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f57ad0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f57ad0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f57940): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f57940): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/PhoneApp( 1236): -- N2 =0
,D/PhoneApp( 1236): -- N3 =0
I/SocialFeedProvider( 1270): +disConnect socialManager
,I/SocialFeedProvider( 1270): disconnect socialManager
,I/SocialFeedProvider( 1270): -disConnect socialManager
D/PMS     (  903): acquireWL(42f577b0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42f577b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f421b0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f421b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(42f17bb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3561 10160 null
,D/PMS     (  903): releaseWL(42f17bb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4044 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3789): id/is att sku: 99/false
,W/SystemReader( 3789): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4044, uid=10074, userID:0
,W/SystemReader( 3789): Cannot find support_harman, use default value instead
,W/SystemReader( 3789): Cannot find effect_manager_id, use default value instead
,D/Finsky  ( 4044): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Settings:HtcWrapHeaderInfo( 3789): no such activity!
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4044/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3789): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3789): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3789): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]support         :false
,W/FingerprintManager( 3789): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3789): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3789): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4044/10074)
,D/Finsky  ( 4044): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4044): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4044): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3789): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3789): updateDevelopment, bPrefShow = true
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4044, uid=10074, userID:0
E/Settings:HtcUmcWidgetEnabler( 3789): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3789): [supportHomeButton]support         :false
W/FingerprintManager( 3789): hasFingerprint() - sSensorCode = 0
,D/Ads     ( 4044): Skipping gmscore version check
E/Settings:HtcVoWifiWidgetEnabler( 3789): isSupportVoWifi: null
D/Finsky  ( 4044): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4044): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4044): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3789): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4044): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  903): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4044): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  903): killProcessQuiet, pid=3400
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3400:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  903): acquireWL(42c400d8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42c400d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42960160): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  903): Recipient 3400
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 2174): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2174): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2174): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2174): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2174): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2174): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2174): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2174, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2174): cleanUpNonGplusAccounts done.
,I/ActivityManager(  903): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4090 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  903): sending alarm PendingIntent{42d053c8: PendingIntentRecord{42dd9240 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455056113291, Int=0
,I/ImageRamCache( 4090): create image Cache, size: 31457280.
I/ImageRamCache( 4090): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4090): create image Cache, size: 12582912.
,I/FeedSettings( 4090): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4090): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4090): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4090): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4090): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4090): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4090): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4090): last commit ulog time 1455021437164
,I/SocialManager[SocialBiLogHelper]( 4090): skip commit this time
,D/Process (  903): killProcessQuiet, pid=3700
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3700:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3700
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  903): releaseWL(42960160): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4106 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4106): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4106): MmsConfig.loadMmsSettings
,W/dalvikvm( 4106): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4106): VFY: unable to resolve instance field 36
,W/dalvikvm( 4106): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4106): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2704): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2704): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4106, uid=10111, userID:0
I/Babel   ( 4106): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4106): MmsConfig.loadFromDatabase
,W/Settings( 4106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 4106): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4106): MmsConfig.loadFromResources
,E/Babel   ( 4106): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4106): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4106, uid=10111, userID:0
D/PMS     (  903): acquireWL(42daf2f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,V/AlarmManager(  903): sending alarm PendingIntent{424b03a0: PendingIntentRecord{42d0a900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59042, Int=0
,I/ProviderInstaller( 4106): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  903): releaseWL(42daf2f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42ea9418): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  903): releaseWL(42ea9418): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3765
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3765:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(425a1138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
I/ActivityManager(  903): Recipient 3765
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
,D/Process (  903): killProcessQuiet, pid=3805
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
I/ActivityManager(  903): Killing 3805:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(425a1138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42f64460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42f64460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
I/ActivityManager(  903): Recipient 3805
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/PMS     (  903): acquireWL(42dc1798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42dc1798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42bba000): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 6 times.
,D/PMS     (  903): releaseWL(42bba000): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3432
,I/ActivityManager(  903): Killing 3432:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  903): acquireWL(42e91118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
I/ActivityManager(  903): Recipient 3432
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42e91118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42cb08f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42cb08f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(430107e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
D/PMS     (  903): releaseWL(430107e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42ef6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(42ef6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42f1c610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4147 uid=10041 gids={50041}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): releaseWL(42f1c610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42e55640): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): releaseWL(42e55640): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  903): acquireWL(42b84fe0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3593 10071 null
,D/PMS     (  903): acquireWL(42ec1c60): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3593 10071 null
,D/ConnectivityService(  903): Done.
D/ConnectivityService(  903): Setting timer for 720seconds
,D/Process (  903): killProcessQuiet, pid=3913
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3913:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
E/TodoTaskNotifyService( 3593): java.lang.NullPointerException
,W/System.err( 3593): java.lang.NullPointerException
W/System.err( 3593): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3593): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3593): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3593): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): releaseWL(42b84fe0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): acquireWL(42f496b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3593 10071 null
,D/PMS     (  903): releaseWL(42ec1c60): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3593): stopSelfResult true
,E/TodoTaskNotifyService( 3593): java.lang.NullPointerException
W/System.err( 3593): java.lang.NullPointerException
W/System.err( 3593): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3593): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3593): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3593): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): acquireWL(42f01528): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3593 10071 null
D/PMS     (  903): releaseWL(42f496b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): acquireWL(42deacc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3593 10071 null
,D/PMS     (  903): releaseWL(42f01528): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3593): stopSelfResult true
E/TodoTaskNotifyService( 3593): java.lang.NullPointerException
W/System.err( 3593): java.lang.NullPointerException
W/System.err( 3593): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 3593): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3593): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3593): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): acquireWL(42f98bc0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3593 10071 null
D/PMS     (  903): releaseWL(42deacc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  903): releaseWL(42f98bc0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3593): stopSelfResult true
,D/LocationInitializer( 2174): Restart initialization of location
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/AuthorizationBluetoothService( 1357): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1357): Proximity feature is not enabled.
,E/MDM     ( 1221): [108] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  903): acquireWL(42fc78a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42fc78a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/WSP     ( 1320): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1320): Weather sync is On
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,I/WSP     ( 1320): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Feb 10 00:15:14 CET 2016
D/PMS     (  903): acquireWL(42fdc018): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/PMS     (  903): releaseWL(42fdc018): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3913
,D/WifiService(  903): Client connection lost with reason: 4
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/PMS     (  903): acquireWL(42fe9430): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1320 10055 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  903): acquireWL(42fe6c88): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fe6c88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fe6af8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fe6af8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fe6968): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fe6968): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fc7b10): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fc7b10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f7fcf8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f7fcf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f7fc08): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f7fc08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f6d2b8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f6d2b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42f57b98): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42f57b98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 304 ms] updated apps [took 304 ms] 
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(42f57940): PARTIAL_WAKE_LOCK  AsyncService 0x1 3561 10160 null
,D/PMS     (  903): releaseWL(42f57940): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
,D/PMS     (  903): acquireWL(42f421b0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 3593): update TASK shortcut>
,V/AlarmManager(  903): sending alarm PendingIntent{42e09e88: PendingIntentRecord{42dafaa0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455056115616, Int=0
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  903): mEventCount = 450
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2174): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  903): releaseWL(42f421b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:137, mTXpacketCount:52, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WIFI_ICON( 1112): WifiActivity: 1
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV2    ( 4004): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  903): sending alarm PendingIntent{424af520: PendingIntentRecord{42ec9a48 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1455056117287, Int=0
,I/iu.UploadsManager( 2174): End new media; added: 0, uploading: 0, time: 52 ms
,D/PMS     (  903): acquireWL(42b5be08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b5be08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/PowerUI ( 1112): closing low battery warning: level=100
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,V/AlarmManager(  903): sending alarm PendingIntent{42ea8218: PendingIntentRecord{42f11fb8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455056117422, Int=0
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GAV4    ( 4106): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 7 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2174, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2174, uid=10029, userID:0
,I/CheckinService( 2174): Done disabling old GoogleServicesFramework version
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,I/CalendarProvider2( 1516): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1516): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4196 uid=10016 gids={50016, 3003, 5012, 2001}
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4196): Update started
,I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4196): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4196): Update started
,I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/DownloadManager( 1942): Download 359 starting
D/PMS     (  903): acquireWL(42d54498): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1942 10021 WorkSource{10016}
D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
W/ActivityThread( 1942): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4196): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
E/UpdateRequestReceiver( 4196): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4196): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 1942): Download 360 starting
D/PMS     (  903): acquireWL(42e3bc58): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1942 10021 WorkSource{10016}
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4227 uid=10032 gids={50032, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3960
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3960:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,I/ActivityManager(  903): Recipient 3960
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1942): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 1942): [NET] getaddrinfo-,err=8
D/libc    ( 1942): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 1942): [NET] getaddrinfo-, 1
D/libc    ( 1942): [NET] getaddrinfo_proxy+
D/libc    ( 1942): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 1942): [NET] getaddrinfo-,err=8
D/libc    ( 1942): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 1942): [NET] getaddrinfo-, 1
D/libc    ( 1942): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =571a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =49c0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [2][0][0]
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1942): [NET] getaddrinfo_proxy-, success
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4227, uid=10032, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4227, uid=10032, userID:0
,D/PMS     (  903): acquireWL(42f037c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4227, uid=10032, userID:0
,D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1942): [NET] getaddrinfo_proxy-, success
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4227, uid=10032, userID:0
D/PMS     (  903): releaseWL(42f037c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4227, uid=10032, userID:0
,D/PMS     (  903): acquireWL(42e8c760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42e8c760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fc6f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fc6f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42db3be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42db3be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f56600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f56600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f304b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f304b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f17650): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f17650): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  903): killProcessQuiet, pid=3654
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3654:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3654
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1369): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/DownloadManager( 1942): Ignoring Content-Length since Transfer-Encoding is also defined
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/DownloadManager( 1942): Ignoring Content-Length since Transfer-Encoding is also defined
,I/Prism.ItemManager( 4090): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4090): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4253 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
,W/AccTypeManager( 1369): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1369): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=7 [14][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
E/ExternalAccountType( 1369): Unsupported attribute readOnly
,D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/PhoneMonitor( 4253): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4253): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  903): killProcessQuiet, pid=3822
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2820): canRun() : Opted Out
I/ActivityManager(  903): Killing 3822:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4253/10079)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4253/10079)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4253/10079)
,D/PMS     (  903): acquireWL(430011a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
I/Search.GservicesUpdateTask( 2820): Updating Gservices keys
,D/PMS     (  903): acquireWL(42ffd550): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(430011a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1455056110794 min interval config: 0 actual interval: 10243
,I/CheckinService( 2174): Checking schedule, now: 1455056121051 next: 1455056140735
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
D/PMS     (  903): releaseWL(42ffd550): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3561, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3561, uid=10160, userID:0
,I/ContactAccountLoggerTas( 2820): canRun() : Opted Out
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3561, uid=10160, userID:0
,I/ContactAccountLoggerTas( 2820): canRun() : Opted Out
I/ActivityManager(  903): Recipient 3822
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ContactAccountLoggerTas( 2820): canRun() : Opted Out
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DownloadManager( 1942): Download 360 finished with status SUCCESS
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  903): releaseWL(42e3bc58): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DownloadManager( 1942): Download 359 finished with status SUCCESS
D/PMS     (  903): releaseWL(42d54498): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/PackageManager(  903): Unable to load service info ResolveInfo{430048b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ContactAccountLoggerTas( 2820): canRun() : Opted Out
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42dc2cb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
,D/PMS     (  903): acquireWL(42e816b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42dc2cb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1455056110794 min interval config: 0 actual interval: 10694
,D/LocationProviderProxy(  903): applying state to connected service
I/CheckinService( 2174): Checking schedule, now: 1455056121494 next: 1455056140735
,I/CheckinService( 2174): active receiver: disabled
D/PMS     (  903): acquireWL(42bce258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42bce258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,D/LocationProviderProxy(  903): applying state to connected service
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42e816b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42dcb488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42dcb488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42df8858): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
D/PMS     (  903): releaseWL(42df8858): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
,D/PMS     (  903): acquireWL(42ddf8e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,I/SystemUpdateService( 2174): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  903): releaseWL(42ddf8e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2174): onCreate
,D/SystemUpdateService( 2174): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/PMS     (  903): acquireWL(42df6c78): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 2174): cancelUpdate (empty URL)
,I/SystemUpdateService( 2174): active receiver: disabled
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,D/SystemUpdateService( 2174): onDestroy
,W/dalvikvm( 2174): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42df6c78): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/SQLiteConnectionPool( 2174): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/DynamiteModule( 2174): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 2174): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 2174): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 2174): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 2174): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 2174): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 2174): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 2174): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 2174): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 2174): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 2174): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 2174): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 2174): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 2174): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 2174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 2174): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 2174): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 2174): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 2174): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 2174): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 2174): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 2174): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 2174): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 2174): Selected local version of com.google.android.gms.flags
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
,D/PMS     (  903): acquireWL(42dcd5e0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,D/PMS     (  903): releaseWL(42dcd5e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/SystemEventReceiver( 2174): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  903): Resuming delayed broadcast
,I/OcrUtils( 2174): Updating ocr activity enabled=false
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2174, uid=10029, userID:0
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42c885f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(42e67bb0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 903 1000 WorkSource{10029}
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/IntentController( 1112): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42c885f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(42f97068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42f97068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1112): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1221, uid=10029, userID:0
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 2174): Updating downloaded model state (gservices changed)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2174, uid=10029, userID:0
,D/GCM     ( 1357): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
D/PMS     (  903): acquireWL(42bb1ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/IntentController( 1112): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42e67bb0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  903): releaseWL(42bb1ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1112): removeIcon slot=sync_active index=7 viewIndex=0
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/Prism.ItemManager( 4090): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4090): loadItems() com.htc.launcher.pageview.WidgetManager@42387870 +
,I/Prism.WidgetManager( 4090): onLoadItems() +
,E/dalvikvm( 1221): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1221): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): acquireWL(42f748b0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,W/AlarmManager(  903): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42f1d530: PendingIntentRecord{42df15b0 com.google.android.gms startService}}) : type=2 triggerAtTime=315360067368 win=-1 tElapsed=315360067368 maxElapsed=551880067367 interval=0 standalone=false
,I/GCoreUlr( 1221): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1221): DispatchingService.onCreate()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42e9f4c8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f55510): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3844 10154 null
,I/ActivityManager(  903): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3844): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3844, uid=10154, userID:0
,I/MusicLeanback( 3844): Conditions not met for autocaching.
,I/MusicLeanback( 3844): Stop autocaching.
D/PMS     (  903): releaseWL(42f55510): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42fa2a08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
W/ContextImpl( 3844): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  903): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4307 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42f0dc28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42fa2a08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(42f0dc28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GCoreUlr( 1221): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1221): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/PMS     (  903): acquireWL(4300f888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(4300f888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 -
,W/ctxmgr  ( 1221): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1221): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  903): releaseWL(42f748b0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.WidgetManager( 4090): onLoadItems() -
,I/Prism.ItemManager( 4090): loadItems() com.htc.launcher.pageview.WidgetManager@42387870 -
,D/PMS     (  903): acquireWL(42ef2888): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42ef2888): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42edbcd8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42edbcd8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1221): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1221): Unbound from all location providers
,I/GCoreUlr( 1221): Place inference reporting - stopped
D/PMS     (  903): acquireWL(42f376e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42f376e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42e9f4c8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/GCoreUlr( 1221): DispatchingService.onDestroy()
,I/GCoreUlr( 1221): Stopping handler for UlrDispSvcFast
D/PMS     (  903): acquireWL(42fe6d50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1221): Unbound from all location providers
,I/GCoreUlr( 1221): Place inference reporting - stopped
D/PMS     (  903): releaseWL(42fe6d50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 4307): [DualLensScanUtil]	mmpCursor count is 0
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/Process (  903): killProcessQuiet, pid=3887
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 3887:com.htc.sdm/u0a81 (adj 15): empty #17
D/PhoneApp( 1236): -- N2 =0
D/PhoneApp( 1236): -- N3 =0
,I/ActivityManager(  903): Recipient 3887
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42f40ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): releaseWL(42f40ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42f17bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42f17bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42e44518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4330 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(42e44518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/SyncApplication( 4330): Loading default preferences
,W/Resources( 4330): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 4330): Overriding preferences with custom values
,D/SyncApplication( 4330): Updating preferences succeeded
,E/SyncApplication( 4330): Application created.
D/VolumeInfo( 4330): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4330): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4330): Found 0 mount point(s)
,V/VolumeInfo( 4330): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4330): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4330): getNewCalendarAuthority()...
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4330, uid=10008, userID:0
D/VolumeInfo( 4330): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4330): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4330): enableAppOperation()+
,D/SyncApplication( 4330): enableAppOperation()-
,D/HTCUtilities( 4330): isNeorSinged() + 
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4330, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4330): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4330): isNeorSinged() return false
,D/CDMountReceiver( 4330): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4330): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4330): enable CD Auto-mount: true
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4330): enable auto-mount
,I/ActivityManager(  903): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/HTCUtilities( 4330): enable auto-mount
,I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42eb2618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{426f6d60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  903): killProcessQuiet, pid=3982
I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4351 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  903): Killing 3982:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 1 12 5 11
I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4249f7c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 0 13 3 16
I/ActivityManager(  903): Recipient 3982
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4351): onCreate
D/ProviderChangeReceiver( 4351): ---------------------------------------------------
,D/ProviderChangeReceiver( 4351): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4351): start to updateAlertNotification!
,I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4365 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=4090
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4090:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/AlertService( 4351): No fired or scheduled alerts
,D/HtcAlertUtils( 4351): -- cancelReminderNotification --
,D/HtcAlertUtils( 4351): broadcastExistReminder!
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  903): Recipient 4090
,V/Settings:HtcSettingsApplication( 4365): [4365/4365] onCreate()
W/ContextImpl( 4365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42dc0508): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  903): releaseWL(42dc0508): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=2704
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2704:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2704
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  903): acquireWL(42e6cde8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42e6cde8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42e11288): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42e11288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42d026e0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42d026e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42c89200): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42c89200): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42e9cb68): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42e9cb68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42e415c0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42f42520 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  903): releaseWL(42e415c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42f44eb8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(42bbc520): PARTIAL_WAKE_LOCK  AsyncService 0x1 3561 10160 null
,D/PMS     (  903): releaseWL(42f44eb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42bbc520): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42fe34e8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  903): releaseWL(42fe34e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  903): acquireWL(42f22290): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 311 ms] updated apps [took 311 ms] 
I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,I/DownloadManager( 1942): Download 361 starting
D/PMS     (  903): acquireWL(42ec8220): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1942 10021 WorkSource{10016}
,D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 1942): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  903): acquireWL(43004fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(43004fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42e6f278): PARTIAL_WAKE_LOCK  DownloadManager 0x1 1942 10021 WorkSource{10016}
,I/DownloadManager( 1942): Download 362 starting
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42f87280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  903): getAllNetworkInfo called by  (1942/10021)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,I/DownloadManager( 1942): Download 361 finished with status SUCCESS
D/PMS     (  903): releaseWL(42ec8220): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/PMS     (  903): releaseWL(42f87280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42ec4338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,I/DownloadManager( 1942): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  903): releaseWL(42ec4338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1942/10021)
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4196): Update downloaded, starting installation
,I/UpdateFetcherService( 4196): Started installation
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/DownloadManager( 1942): Download 362 finished with status SUCCESS
D/PMS     (  903): releaseWL(42e6f278): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
I/UpdateFetcherService( 4196): Update downloaded, starting installation
I/UpdateFetcherService( 4196): Started installation
,I/ActivityManager(  903): Resuming delayed broadcast
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ConfigUpdateInstallReceiver(  903): Not installing, new version is <= current version
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 8 times.
,D/PMS     (  903): releaseWL(42fe9430): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2174): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  903): releaseWL(42f22290): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  903): mEventCount = 600
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=4 [25][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/GAV2    ( 3561): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(4300f650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4300f650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42f6f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42c62558: PendingIntentRecord{42c6c560 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71728, Int=0
D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=170 rxSum=154} preTxRxSum={txSum=108 rxSum=98}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19866 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19867 delay=15s
D/PMS     (  903): releaseWL(42f6f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 9 times.
,D/Finsky  ( 4044): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  903): acquireWL(42f2fdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10074}
,W/dalvikvm( 4044): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  903): sending alarm PendingIntent{42ddeb68: PendingIntentRecord{42d699a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455056129572, Int=0
D/PMS     (  903): releaseWL(42f2fdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.vending (4044/10074)
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4044): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4044): [NET] getaddrinfo-,err=8
D/libc    ( 4044): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4044): [NET] getaddrinfo-, 1
,D/libc    ( 4044): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =83a4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4044): [NET] getaddrinfo_proxy-, success
I/global  ( 4044): call createSocket() return a new socket.
D/libc    ( 4044): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4044): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4044): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4044): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4044): untagSocket(69) failed with errno -22
,D/Finsky  ( 4044): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/NetworkManagementSocketTagger( 4044): untagSocket(69) failed with errno -22
,W/PackageSettings(  903): Skipping PackageSetting{42a7a0f0 com.example.hello/10397} due to missing metadata
,W/PackageSettings(  903): Skipping PackageSetting{42a7f060 com.test.thalitest/10389} due to missing metadata
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4044): untagSocket(69) failed with errno -22
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (4044/10074)
,D/Finsky  ( 4044): [1] DailyHygiene.access$600: Logging device features,
,D/PMS     (  903): acquireWL(42ecb0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10074}
,V/AlarmManager(  903): sending alarm PendingIntent{42b83170: PendingIntentRecord{42e8f2e0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455056131985, Int=0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=7 [64][5][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:273, mTXpacketCount:137, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/Finsky  ( 4044): [428] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1221): client connected with version: 8296000
D/PMS     (  903): acquireWL(42fa16c0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4044 10074 null
D/PMS     (  903): releaseWL(42ecb0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4044): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4044): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4044): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4044): [NET] getaddrinfo-,err=8
D/libc    ( 4044): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4044): [NET] getaddrinfo-, 1
,D/libc    ( 4044): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3867 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4044): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  903): releaseWL(42fa16c0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 10 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=8 [12][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/AutoSetting( 1320): service - has update message, not stop
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/WIFI_ICON( 1112): WifiActivity: 1
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1516): service - mHandler: update timezone
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1516): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1516): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4273cde8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 2 8 2 11
,I/SensorManager(  903): mEventCount = 750
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 11 times.
,D/PMS     (  903): acquireWL(42f65580): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f65580): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42f6d6c8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42f6d6c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fc7de8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fc7de8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42da8260): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42da8260): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/PMS     (  903): acquireWL(42f4da00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  903): sending alarm PendingIntent{42ee9b68: PendingIntentRecord{42c6c560 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=86735, Int=0
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=245 rxSum=220} preTxRxSum={txSum=170 rxSum=154}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19867 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19868 delay=15s
D/PMS     (  903): releaseWL(42f4da00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 12 times.
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:286, mTXpacketCount:273, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1516): Don't start project servcice
,D/HtcModeClient( 1516): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1516): connectState: CONNECTION_READY = false
,D/SilentMusic( 1516): call stop
D/HtcModeClient( 1516): close connection
,W/HtcModeClient( 1516): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1516): read the terminate packet, so break
,D/PMS     (  903): acquireWL(42f13178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029}
,V/AlarmManager(  903): sending alarm PendingIntent{42df75b0: PendingIntentRecord{42e72c90 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455056140735, Int=522937000
,V/AlarmManager(  903): sending alarm PendingIntent{42de5148: PendingIntentRecord{42db4580 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455056146177, Int=0
,D/PMS     (  903): acquireWL(42eca6a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms},
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4425 uid=10078 gids={50078}
,V/AlarmManager(  903): sending alarm PendingIntent{42c00a28: PendingIntentRecord{42c009a8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455056149936, Int=60000
,D/PMS     (  903): releaseWL(42f13178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  903): acquireWL(42f9eab8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1455056110794 min interval config: 0 actual interval: 39186
D/PMS     (  903): releaseWL(42eca6a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checking schedule, now: 1455056149986 next: 1455056140735
,I/CheckinService( 2174): active receiver: enabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2174, uid=10029, userID:0
,I/CheckinService( 2174): Preparing to send checkin request
,I/EventLogService( 2174): Accumulating logs since 1455056105570
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/SMSBackup( 4425): SMSBackupAgentService started
,D/SMSBackup( 4425): Checking restore status
D/SMSBackup( 4425): Restore complete
,D/SMSBackup( 4425): cancelCheckAlarm
,D/SMSBackup( 4425): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,I/CheckinRequestBuilder( 2174): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  903): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4044): [419] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4044): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=879926966
,I/Adreno-EGL( 3642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3642): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3642): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3642): Local Branch: 
I/Adreno-EGL( 3642): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3642): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3642):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 3642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3642): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3642): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3642): Local Branch: 
I/Adreno-EGL( 3642): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3642): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3642):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42f3bba0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3912528363
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 3642): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (3642/10029)
,I/Adreno-EGL( 3642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3642): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3642): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3642): Local Branch: 
I/Adreno-EGL( 3642): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3642): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3642):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2174): [NET] getaddrinfo-, 1
,D/libc    ( 2174): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9ccb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2174): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2174): Sending checkin request (12272 bytes)
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinRequestBuilder( 2174): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  903): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=5 [18][1][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,I/CheckinTask( 2174): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2174): Checking schedule, now: 1455056151861 next: 1455579088857
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,D/CheckinService( 2174): Recording last checkin time for package unspecified as 1455056151882
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(42f9eab8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,V/LightsService(  903): setLight #0: color=#3f
,V/LightsService(  903): setLight #0: color=#3c
,V/LightsService(  903): setLight #0: color=#35
,V/LightsService(  903): setLight #0: color=#2f
,V/LightsService(  903): setLight #0: color=#28
,V/LightsService(  903): setLight #0: color=#21
,V/LightsService(  903): setLight #0: color=#1b
,V/LightsService(  903): setLight #0: color=#14
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Process (  903): killProcessQuiet, pid=3593
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3593:com.htc.task/u0a71 (adj 15): empty #17
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/SensorManager(  903): mEventCount = 900
,I/ActivityManager(  903): Recipient 3593
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=263 rxSum=232} preTxRxSum={txSum=245 rxSum=220}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19868 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19869 delay=15s
D/PMS     (  903): acquireWL(42fcd540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{42d76d00: PendingIntentRecord{42c6c560 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=101745, Int=0
D/PMS     (  903): releaseWL(42fcd540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  903):    returned true
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a26bf8
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/PMS     (  903): mWirelessDisplayManager is null
W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a26bf8, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42967d48
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42f67490
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 312ms
,W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/NfcService( 1248): ScreenObserver: OFF
D/NfcService( 1248): applyRouting - 0
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@430a7940)
,D/NfcService( 1248): applyRouting -2
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=1270
D/PMS     (  903): acquireWL(430a6f68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMN     (  903): wakingUp
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): releaseWL(430a6f68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  903): acquireWL(430a97b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMN     (  903): onScreenOn
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(430a97b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19870 delay=15s
I/HtcPowerSaver(  903): << updateStatus
,I/ClockThread( 1112): stop update clock
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/NfcService( 1248): applyRouting - 0
,D/MtpService( 1942): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
D/MtpService( 1942): [MTP][onReceive]-
,D/NfcService( 1248): applyRouting -2
D/PMS     (  903): acquireWL(4309a5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=104874, Int=0
D/PMS     (  903): acquireWL(43098558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/TetherSettings( 3789): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3789): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3789): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3789): Cust_ConnectToPC   : spcsc>false
D/        ( 3789): Cust_ConnectToPC   : IPT>true
D/        ( 3789): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3789): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3789): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3789): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  903): releaseWL(43098558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1369): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PSReceiver( 3789): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3789): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3789):  defaultType:0
W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
W/AccTypeManager( 1369): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1369): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): SET_SCREEN_ON:On
I/wpa_supplicant( 1151): htc_wext_set_keepalive +
I/wpa_supplicant( 1151): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1151): getPrivFuncNum +	
I/wpa_supplicant( 1151): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING - ret = 0
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1151): Change stage from stage0 to stage3
,I/wpa_supplicant( 1151): wlan0: Background scan every 600 seconds
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 65
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 353
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:306, mTXpacketCount:286, avgLinkspeed:70,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4459 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/ExternalAccountType( 1369): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(42f06be8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4459 1000 null
,D/PMS     (  903): releaseWL(42f06be8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4459): getMobilePolicyEnabled, result = true
,D/Process (  903): killProcessQuiet, pid=4227
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4227:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4227
,W/PackageManager(  903): Unable to load service info ResolveInfo{42f68070 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): acquireWL(430ad258): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  903): updateScreenOn: false
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(430ad258): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/LocationProviderProxy(  903): applying state to connected service
,I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  903): acquireWL(42f82768): PARTIAL_WAKE_LOCK  AsyncService 0x1 3561 10160 null
,D/PMS     (  903): acquireWL(42ff7aa0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(42f82768): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  903): acquireWL(42cf7400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42cf7400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  903): applying state to connected service
D/PMS     (  903): acquireWL(42ee5d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42ee5d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42ee0210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42ee0210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42da0cc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42da0cc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42f972a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
,D/PMS     (  903): releaseWL(42f972a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOn: 1455056160945
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOn: 1455056160945
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42967d48
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  903): pid=903, uid=1000
,W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42967d48, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42f67490
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(42f46e68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@423a49f0
I/SocialFeedProvider( 1270): +onPause
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,I/SocialFeedProvider( 1270): -onPause
,D/PMS     (  903): releaseWL(4309a5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(42f46e68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19870 mDataStallAlarmIntent=PendingIntent{42f7c1f0: PendingIntentRecord{42c6c560 android broadcastIntent}}
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): SET_SCREEN_ON:Off
I/wpa_supplicant( 1151): htc_wext_set_keepalive +
I/wpa_supplicant( 1151): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1151): getPrivFuncNum +	
I/wpa_supplicant( 1151): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1151): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1151): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1151): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
D/PMS     (  903): acquireWL(42ea3c90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/NetworkPolicy(  903): updateScreenOn: false
,W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4459): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f67490
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f67490, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f67490, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f67490
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  903): New client listening to asynchronous messages
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f679d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f679d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): releaseWL(42ea3c90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1236): start background delete task...
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(42ef1c10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42ef1c10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOff
D/PMS     (  903): acquireWL(42f0a0c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42f0a0c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 -
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  903): releaseWL(42ff7aa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/PhoneApp( 1236): -- N2 =0
,D/PhoneApp( 1236): -- N3 =0
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4253
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4253:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4253
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3867
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3867:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3867
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(430ac6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42f03570: PendingIntentRecord{42c1afd0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119457, Int=0
,D/PMS     (  903): releaseWL(430ac6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42fece38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43063030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43063030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42fece38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42ed4478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(42ed4478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(4302a138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43033560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(4303b5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1455056174897 tag=VacuumService
,D/PMS     (  903): releaseWL(4302a138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43033560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430b9688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
D/PMS     (  903): releaseWL(4303b5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(430b9688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430be3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(430be3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(430c5760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(430c5760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430c9cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(430c9cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430d10a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(430da490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(430da490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430e1d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(430d10a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(430e6e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(430e6e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 13520 seconds from now (1455056175786)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cc9d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/PMS     (  903): releaseWL(430e1d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43100d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(43100d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43107ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(43107ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(4310f8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4310f8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(431150f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42bfd120: PendingIntentRecord{42c35730 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135980, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,D/PMS     (  903): releaseWL(431150f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=3844
,I/ActivityManager(  903): Killing 3844:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3844
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.music (pid 3844): Died!
,D/PMS     (  903): acquireWL(4311bce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42c5ad40: PendingIntentRecord{42cb7698 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141478, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(4311cff0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(4311bce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7ecd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success,
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(4311cff0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  903): acquireWL(4314d900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(4314d900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PMS     (  903): acquireWL(43152108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164873, Int=0
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): releaseWL(43152108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43155ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10027}
,V/AlarmManager(  903): sending alarm PendingIntent{42f25160: PendingIntentRecord{42e10678 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170855, Int=0
,D/PMS     (  903): releaseWL(43155ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(43157ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43157ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4315dbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4315dbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4315f660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(4315f660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43165258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43165258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(4316b298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=284873, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4316b298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4316cd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4316cd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  903): << updateStatus
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43172928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43172928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1112): closing low battery warning: level=100
I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/Process (  903): killProcessQuiet, pid=4307
,I/ActivityManager(  903): Killing 4307:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4307
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(4317b310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=344873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4317b310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4317cd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4317cd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43182980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43182980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43188a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=404873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43188a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4318a4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4318a4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43190250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43190250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43191b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=464873, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43191b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(431935c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431935c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43199268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43199268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(4319f358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=524873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4319f358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(431a1b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431a1b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(431a7c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=584873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431a7c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(431a9700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431a9700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(431af3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431af3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1236): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1236): sku_id=99
D/ContactMessageStore( 1236): start background delete task...
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/PMS     (  903): acquireWL(431b1268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=644873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431b1268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(431b2d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(431b2d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(431b8cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431b8cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(431bed08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=704873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431bed08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  903): acquireWL(431c07a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431c07a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-,
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck,
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus,
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1151): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1151): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomn,ess: count=9 entropy=3
D/wpa_supplicant( 1151): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1151): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000707332348
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000021830398
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=4
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-81
I/wpa_supplicant( 1151): tsf=0000000707332360
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiP2pService(  903): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@431cd510 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 707332348, distance: ?(cm), distanceSd: ?(cm),
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431cd510 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@431cd510 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 21830398, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 707332360, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==,
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter,
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1151): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1151): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1151): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1151): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000724642050
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
,I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000724642024
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=4
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-81
,I/wpa_supplicant( 1151): tsf=0000000724642062
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 724642050, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 724642024, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 724642062, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(431e6308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(431e6308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1151): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1151): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1151): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1151): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000742054995
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000742054956
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=4
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-81
I/wpa_supplicant( 1151): tsf=0000000724642062
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000742054983
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 742054995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 742054956, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 724642062, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 742054983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48,
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0,
D/wpa_supplicant( 1151): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1151): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1151): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
,I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1151): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1151): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
,W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (351) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000759442261
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====,
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000742054956
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-52
I/wpa_supplicant( 1151): tsf=0000000759442250
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 759442261, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 742054956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 759442250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/PMS     (  903): acquireWL(42f95a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=764873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  903): releaseWL(42f95a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  903): acquireWL(42f7fd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f7fd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1151): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1151): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
,I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1151): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1151): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (351) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000776824849
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000776824812
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
,I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-52
I/wpa_supplicant( 1151): tsf=0000000776824839
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 776824849, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 776824812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 776824839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42d56858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42d56858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
,I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1151): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1151): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1151): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
,I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1151): Add randomness: count=41 entropy=35
,D/wpa_supplicant( 1151): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1151): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000794239594
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000794239558
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000794239584,
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
I/wpa_supplicant( 1151): tsf=0000000794239604
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 794239594, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 794239558, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 794239584, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 794239604, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1151): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1151): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1151): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1151): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1151): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1151): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000811645485
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
,I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000811645450
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000811645475
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-76
I/wpa_supplicant( 1151): tsf=0000000811645495
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 811645485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 811645450, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 811645475, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 811645495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/PMS     (  903): acquireWL(42c87df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=824873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42c87df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1151): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1151): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1151): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1151): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1151): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1151): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000828732183
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====,
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000828732146
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
,I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000828732172
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-76
I/wpa_supplicant( 1151): tsf=0000000828732192,
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 828732183, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 828732146, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 828732172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 828732192, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49,
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1151): Add randomness: count=61 entropy=55
,D/wpa_supplicant( 1151): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1151): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=64 entropy=58
,D/wpa_supplicant( 1151): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1151): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1151): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000846132138
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000846132101
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000846132127
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000000846132147
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 846132138, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 846132101, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 846132127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 846132147, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e160d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+,
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42e160d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1112): closing low battery warning: level=100,
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1151): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1151): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1151): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1151): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1151): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1151): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000863545089
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
,I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000863545052
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000863545079
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000000863545099
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 863545089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 863545052, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 863545079, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 863545099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList,
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter,
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1151): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1151): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
,I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1151): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1151): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000880970651
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000880970625
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000000863545079
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000000880970661
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
,I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 880970651, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 880970625, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 863545079, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 880970661, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e2d188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000},
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=884873, Int=0,
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42e2d188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42ee2f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42ee2f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1151): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1151): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0,] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000898345104
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000898345078
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000000880970661
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 898345104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 898345078, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 880970661, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42ee71c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  903): releaseWL(42ee71c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1151): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1151): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1151): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1151): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000915442126
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000000898345078
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
I/wpa_supplicant( 1151): tsf=0000000915442136
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 915442126, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 898345078, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 915442136, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1151): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1151): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1151): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1151): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000932811722
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3,
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000898345078
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
I/wpa_supplicant( 1151): tsf=0000000932811733
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 932811722, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 898345078, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 932811733, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/PMS     (  903): acquireWL(431b7830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=944873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431b7830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43155c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{425c09d0: PendingIntentRecord{42ca3ad0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=779626, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{42aa39c0: PendingIntentRecord{42c77b58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=945457, Int=0
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(431cd0e8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(431cd0e8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4537 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{42bc8d58: PendingIntentRecord{42e5cac8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455056265817, Int=10800000
V/AlarmManager(  903): sending alarm PendingIntent{42f4b220: PendingIntentRecord{42ce48b8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455056378782, Int=1800000
,V/AlarmManager(  903): sending alarm PendingIntent{427a3848: PendingIntentRecord{42daf628 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455056986163, Int=900000
,D/PMS     (  903): acquireWL(42f26328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43126dc8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(42f26328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4459): call getInstance()
,D/PMS     (  903): releaseWL(43155c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4459): MY_DEBUG = false
,I/EventLogService( 2174): Aggregate from 1455056150036 (log), 1455054578618 (data)
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4537/10049)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(43126dc8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/Process (  903): killProcessQuiet, pid=4330
,I/ActivityManager(  903): Killing 4330:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4330
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(431bdb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(431bdb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing,
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
,D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1151): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1151): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1151): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
,I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
,D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1151): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1151): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1151): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000949872412
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
,I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-47
I/wpa_supplicant( 1151): tsf=0000000949872387
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
,I/wpa_supplicant( 1151): tsf=0000000949872435
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-53
I/wpa_supplicant( 1151): tsf=0000000949872423
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 949872412, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 949872387, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 949872435, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 949872423, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4300f650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023592
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023991
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024136
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024146
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024150
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025587
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028513
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360029529
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360067368
,D/PMS     (  903): releaseWL(4300f650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1151): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1151): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1151): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1151): Add randomness: count=111 entropy=105
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wl,an0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000967254931
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-47
I/wpa_supplicant( 1151): tsf=0000000967254895
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
I/wpa_supplicant( 1151): tsf=0000000949872435
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-53
I/wpa_supplicant( 1151): tsf=0000000967254921
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 967254931, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 967254895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 949872435, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 967254921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(425f95a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  903): n_update end,
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(425f95a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1151): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1151): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1151): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1151): Add, randomness: count=117 entropy=111
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (351) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000000984572344
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000967254895
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-53
I/wpa_supplicant( 1151): tsf=0000000984572334
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 984572344, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 967254895, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 984572334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1,
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==,
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1151): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1151): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1151): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 ,freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1151): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1151): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1151): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001001892369
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001001892333
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001001892358
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=8
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-79
I/wpa_supplicant( 1151): tsf=0000001001892381
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1001892369, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1001892333, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1001892358, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 1001892381, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42ee2748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1004873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42ee2748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42b67b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
,D/SmartSyncScreenOnOffTimeReceiver( 4459): [updateNmRange] bManual = false
V/AlarmManager(  903): sending alarm PendingIntent{42718850: PendingIntentRecord{42b63770 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455057061025, Int=0
D/PMS     (  903): releaseWL(42b67b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42e14a88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4459 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4459): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4459): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4459): SettingOnTime = 1455084000000, randomSettingOnTime = 1455080818000
D/SmartSyncScreenOnOffTimeReceiver( 4459): SettingOffTime = 1455069600000, randomSettingOffTime = 1455070063000
D/SmartSyncScreenOnOffTimeReceiver( 4459): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4459): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4459): bNightModeTurnOffOnce = false
D/PMS     (  903): releaseWL(42e14a88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  903): acquireWL(427e48e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(427e48e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1151): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1151): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1151): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1151): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1151): Add randomness: count=132 entropy=126
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1151): Add randomness: count=133 entropy=127
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001019295006
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001019294969
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001019294996
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=8
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001019295016
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1019295006, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1019294969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1019294996, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1019295016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42ebe2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(42ebe2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1151): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1151): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1151): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1151): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1151): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1151): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (489) for get BSS: id=1,
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001036342137
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
,I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001036342101
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001036342126
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=8
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001036342147
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1036342137, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1036342101, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1036342126, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1036342147, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
D/WirelessDisplayService(  903): getDiscoveryDongleList
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==,
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1151): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1151): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1151): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1151): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1151): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1151): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001053771810
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-47
I/wpa_supplicant( 1151): tsf=0000001053771773
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-51
I/wpa_supplicant( 1151): tsf=0000001053771800
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=8
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001053771822
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1053771810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1053771773, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 1053771800, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1053771822, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-51], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e5e310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42e5e310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1151): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1151): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1151): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1151): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelemen,t id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001071145311
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-47
I/wpa_supplicant( 1151): tsf=0000001053771773
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-51
I/wpa_supplicant( 1151): tsf=0000001071145301
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=8
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001053771822
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1071145311, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1053771773, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 1071145301, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1053771822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-51], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results,
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1151): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1151): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
,I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1,
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
,I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1151): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1151): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (351) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001088571886
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
,I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001088571850
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-51
I/wpa_supplicant( 1151): tsf=0000001088571876
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1088571886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1088571850, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 1088571876, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-51], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4318a2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4318a2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1151): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1151): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1151): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1151): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1151): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1151): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001105985297
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001105985260
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001105985286,
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-77
I/wpa_supplicant( 1151): tsf=0000001105985307
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1105985297, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1105985260, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1105985286, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1105985307, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults,
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1151): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1151): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1151): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1151): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1151): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1151): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001123381757
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001123381721
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50,
I/wpa_supplicant( 1151): tsf=0000001123381747
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-77
I/wpa_supplicant( 1151): tsf=0000001123381769
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1123381757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1123381721, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1123381747, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1123381769, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42b4f948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1124873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b4f948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43063050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43063050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1151): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1151): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1151): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1151): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1151): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1151): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1151): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001140764865
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001140764829
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001140764855
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-77
I/wpa_supplicant( 1151): tsf=0000001140764875
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1140764865, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1140764829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1140764855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1140764875, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43155f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43155f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available,
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
,D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1151): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1151): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411,
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1151): Add randomness: count=190 entropy=184
,D/wpa_supplicant( 1151): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found,
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (489) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001158174852
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001158174826
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=7
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-50
I/wpa_supplicant( 1151): tsf=0000001140764855
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001158174863
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1158174852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1158174826, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1140764855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1158174863, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1151): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1151): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1151): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1151): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001175571946
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001175571920
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001175571957
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####,
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1175571946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1175571920, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1175571957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42f4f8e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000},
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1184873, Int=0,
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  903): releaseWL(42f4f8e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42fa99e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42fa99e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1151): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1151): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
,I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1151): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1151): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001192995019
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001192994993
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001192995032
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1192995019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1192994993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1192995032, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1151): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1151): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1151): reply (376) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001210421982
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001210421956
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=9
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-78
I/wpa_supplicant( 1151): tsf=0000001192995032
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1210421982, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1210421956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1192995032, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43275140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43275140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory),
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1151): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
,D/wpa_supplicant( 1151): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1151): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (238) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001227824862
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-49
I/wpa_supplicant( 1151): tsf=0000001227824836
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1227824862, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 1227824836, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 2 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (2) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (2) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(4328c370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428ac8f0: PendingIntentRecord{42795d90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1244873, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4328c370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1151): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1151): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1151): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1151): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (377) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001245221909
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001245221883
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=10
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-77
I/wpa_supplicant( 1151): tsf=0000001245221921
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1245221909, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1245221883, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1245221921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(432a2210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(432a2210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
,D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1151): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1151): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 9
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 0
I/wpa_supplicant( 1151): wpa_s->is_screen_on 0
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1151): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1151): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1151): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1151): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1151): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1151): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): clear disabled list - type=1
I/wpa_supplicant( 1151): No suitable network found
W/wpa_supplicant( 1151): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1151): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1151): reply (377) for get BSS: id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-57
I/wpa_supplicant( 1151): tsf=0000001262645100
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000001262645074
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=10
I/wpa_supplicant( 1151): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-77
I/wpa_supplicant( 1151): tsf=0000001262645112
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=Gonzos
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiP2pService(  903): P2pEnabledState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1262645100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1262645074, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1262645112, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4566): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4566): ====startRecUseTime====
D/htc.customization.log.level( 4566):  is 
W/CustomizationLogLevel( 4566): Level value is invalid, use default level 2
D/CustomizationManager( 4566):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4566): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4566): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4566): Parsing tag category name = system
I/CustomizationCIDLoader( 4566): Parsing tag category name = application
I/CustomizationCIDLoader( 4566): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4566): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4566): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4566): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4566): Parsing tag category name = Settings
D/CustomizationManager( 4566):  Read CID file spent 0.175 (s)
D/CustomizationManager( 4566):  All configurations done spent 0.176 (s)
W/HtcNativeFlag( 4566): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4566): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4566): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4566): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4566, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  903): Skipping PackageSetting{42a7a0f0 com.example.hello/10397} due to missing metadata
W/PackageSettings(  903): Skipping PackageSetting{42a7f060 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/PMS     (  903): acquireWL(4334a598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(4334a598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1369): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/PackageManager(  903): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  903): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/VoicemailCleanupService( 1284): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
W/AccTypeManager( 1369): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1369): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4580 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
E/ExternalAccountType( 1369): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 80 ms] updated apps [took 80 ms] 
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  903): Unable to load service info ResolveInfo{42b04070 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4580): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4580): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4580): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4580): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4580): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4580): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4580): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4580): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4580): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4580): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4580): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4580): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4580): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4580): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4580): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4580): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4580): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4580): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4580): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4580): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4580): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4580): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4580): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4580): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4580): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4580): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4580): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4580): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4580): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4580): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4580): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4580): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4580): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4580): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4580): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4580): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4580): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4580): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4580): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4580): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4580): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4580): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4580): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4580): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4580): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4580): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4580): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4580): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4580): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4580): threadid=11: thread exiting with uncaught exception (group=0x41edfe30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4580): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4580): Process: com.google.android.apps.docs, PID: 4580
E/AndroidRuntime( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4580): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4580): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4580): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4580): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4580): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
E/SQLiteDatabase( 4580): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4580): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4580): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4580): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4580): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4580): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4580): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4580): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4580): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4580): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4580): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4580): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4580): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4580): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4580): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4580): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4580): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4580): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4580): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4580): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4580): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4580): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4580): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4580): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4580): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4580): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4580): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4580): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4580): Opened ClientFlag.db in read-only mode
D/Process ( 4580): killProcess, pid=4580
D/Process ( 4580): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4597 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  903): Recipient 4580
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4580) has died.
W/ContextImpl( 4597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4597): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4597): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4597): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4597): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4597): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4597): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4597): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4597): threadid=10: thread exiting with uncaught exception (group=0x41edfe30)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4597): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4597): Process: com.android.keychain, PID: 4597
E/AndroidRuntime( 4597): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4597): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4597): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4597): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4597): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4597): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4611 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4597): killProcess, pid=4597
D/Process ( 4597): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455057322952.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/ActivityManager(  903): Recipient 4597
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.keychain (pid 4597) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4611): getInstance(Context context)
D/AppTag  ( 4611): getInstance(Context context)
D/AppTag  ( 4611): onCreate()
D/PMS     (  903): acquireWL(4311dfd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3561 10160 null
D/PMS     (  903): releaseWL(4311dfd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4044): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2174): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2174): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2174): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2174): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2174): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2174): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2174): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2174): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2174): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2174): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2174): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2174): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2174): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2174): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2174): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2174): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2174): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2174): App measurement is starting up, version: 8489
I/GMPM-SVC( 2174): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteDatabase( 2174): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2174): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2174): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2174): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 2174): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2174): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2174): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2174): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2174): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
I/ActivityManager(  903): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
W/GMPM-SVC( 2174): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 2174): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655a13e0
W/GMPM-SVC( 2174): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 2174): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/DriveAsyncService( 2174): disk I/O error (code 3850)
E/DriveAsyncService( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2174): 	at java.lang.Thread.run(Thread.java:864)
W/GMPM-SVC( 2174): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6eb306b0
E/GMPM-SVC( 2174): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
W/dalvikvm( 2174): threadid=49: thread exiting with uncaught exception (group=0x41edfe30)
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/ActivityManager(  903): App crashed! Process: com.google.android.gms
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 2174): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/AndroidRuntime( 2174): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2174): Process: com.google.android.gms, PID: 2174
E/AndroidRuntime( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2174): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2174): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2174): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2174): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2174): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2174): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2174): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): acquireWL(42ee7560): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/Process ( 2174): killProcess, pid=2174
D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/Process ( 2174): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@423a2d10 +
I/Prism.WidgetManager( 1270): onLoadItems() +
I/ActivityManager(  903): Recipient 2174
I/ActivityManager(  903): Process com.google.android.gms (pid 2174) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20999ms
D/PMS     (  903): handleWLDeath(42ee7560): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30999ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30998ms

```
