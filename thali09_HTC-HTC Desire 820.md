#### Test 58259810381ca4f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3918 uid=10081 gids={50081, 5001, 1028, 1015}
--------- beginning of /dev/log/main
D/Process (  906): killProcessQuiet, pid=3651
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3651:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/SoundPicker( 3918): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3918): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3918): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3918): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3918): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Recipient 3651
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/Messaging( 3725): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 3725): startAsyncQueryReports ---
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/MmsAsyncWorkHandler( 3725): 
D/MmsAsyncWorkHandler( 3725): HM tk = 20001
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/ReportIndicatorCache( 3725): MSG_QUERY_REPORTS >>
I/Messaging( 3725): mccmnc> 
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
D/DraftCache( 3725): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3725): [DraftCache/1] refresh
D/MmsConfig( 3725): networkCode: 
D/Messaging( 3725): ViewCache CreatePreloadOnlyConversationList
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/AccFlag ( 1239): sku_id=99
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
D/DraftCache( 3725): [DraftCache/361] rebuildCache
D/PhoneStorageUtil( 3725): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3725): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3725): createReceiver
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/MessageCustFlag( 3725): sense_version=6.0
D/Jerry   ( 3725): start to preload cursor >>>>>>>
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1239): Update uri=content://mms, match=0
V/MmsProvider( 1239): selection=st=129 AND m_type!=134
D/Messaging( 3725): Reset downloading state: 0
D/Messaging( 3725): mNeedToUpdateDate2: false
V/MmsSystemEventReceiver( 3725): TransactionService is going to be woken up.
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/ActivityManager(  906): Delaying start of: ServiceRecord{42f4ca28 u0 com.htc.sense.mms/.transaction.TransactionService}
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
D/Jerry   ( 1239): URI_DRAFT
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/DraftCache( 3725): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/DraftCache( 3725): [DraftCache/361] rebuildCache time: 3
D/MmsAsyncWorkHandler( 3725): 
D/MmsAsyncWorkHandler( 3725): HM tk = 20002
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/Messaging( 3725): ViewCache CreatePreload
D/Messaging( 3725): ViewCache CreatePreloadOnlyMultipleOpsList
D/Messaging( 3725): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1239): sku_id=99
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/Cust_MMSMS( 3725): _has_set_default_values_2=true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
V/TransactionService( 3725): 1-Creating TransactionService
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/MsgPreferenceUtils( 3725): def_index: 0
V/TransactionService( 3725): onStartCommand: 1
D/MmsSystemEventReceiver( 3725): unRegisterForConnectionStateChanges
V/TransactionService( 3725): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3725): Loading previous transactions.
D/MsgPreferenceUtils( 3725): globalIndex = 1
D/MsgPreferenceUtils( 3725): phone state: true
D/MsgPreferenceUtils( 3725): sd state: false
D/MsgPreferenceUtils( 3725): vIndex = 0
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1239): sku_id=99
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/AccFlag ( 1239): device_type: 1
D/TransactionService( 3725): Force set service start id to 1
V/TransactionService( 3725): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3725): unRegisterForConnectionStateChanges
V/TransactionService( 3725): Destroying TransactionService
D/Process (  906): killProcessQuiet, pid=3105
D/TransactionService( 3725): stopSelfResult: true, mLastHandledServiceId: 1
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3105:com.android.settings:remote/1000 (adj 15): empty #17
V/TransactionService( 3725): 4-Handling incoming message: { when=-12ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/DFPI.PIReciver( 3882): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Recipient 3105
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3882): onHandleIntent
I/DFPI.ApkInstallService( 3882): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3882): check CID = HTC__032
I/DFPI.ApkInstallService( 3882): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/CheckinRequestBuilder( 2179): Classify the device as Phone.
W/ContextImpl( 3918): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3918): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3918): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3918): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/CheckinService( 2179): Checking schedule, now: 1454578880980 next: 1455101817972
I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
D/CheckinService( 2179): Recording last checkin time for package unspecified as 1454578881007
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/PMS     (  906): releaseWL(42f812a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3972 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
D/DFPI.PIReciver( 3882): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3882): onHandleIntent
I/DFPI.ApkInstallService( 3882): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3882): check CID = HTC__032
I/DFPI.ApkInstallService( 3882): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3918): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3918): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3918): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3918): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/EASAppSvc( 3972): [ NA ]- onCreate()
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/EASAppSvc( 3972): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
D/ORMLib  ( 3447): put()
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/EASAppSvc( 3972): [ NA ]- onDestroy()
I/EASAppSvc( 3972): [ NA ]> uninitEASService
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3972/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3972/10064)
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3972/10064)
D/CustomizationManager( 3934): ====startRecUseTime====
D/htc.customization.log.level( 3934):  is 
W/CustomizationLogLevel( 3934): Level value is invalid, use default level 2
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2179, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2179, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2179, uid=10029, userID:0
I/MediaStoreImporter( 3862): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/CustomizationManager( 3934):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3934): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3934): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3934): Parsing tag category name = system
I/CustomizationCIDLoader( 3934): Parsing tag category name = application
I/CustomizationCIDLoader( 3934): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3934): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3934): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3934): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3934): Parsing tag category name = Settings
D/CustomizationManager( 3934):  Read CID file spent 0.118 (s)
D/CustomizationManager( 3934):  All configurations done spent 0.119 (s)
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/HtcNativeFlag( 3934): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3934): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3934): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3934): Fail to get flag for type 'language', use default value: -1
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/Prism.ItemManager( 3708): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3708): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/EASRequestController( 3972): [ NA ]release
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Resuming delayed broadcast
I/EASAppSvc( 3972): [ NA ]< uninitEASService
I/EASAppSvc( 3972): [ NA ]- onCreate()
I/EASAppSvc( 3972): [ NA ]> onUpgrade: version = 63
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
E/cutils-trace( 3934): Error opening trace file: No such file or directory (2)
D/DFPI.PIReciver( 3882): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3934
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/DFPI.ApkInstallService( 3882): onHandleIntent
I/DFPI.ApkInstallService( 3882): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3882): check CID = HTC__032
I/DFPI.ApkInstallService( 3882): There is no Demo.apk in sd card or phone storage
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3972/10064)
D/Process (  906): killProcessQuiet, pid=3666
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3666:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3972/10064)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3972/10064)
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Recipient 3666
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/ORMLib  ( 3447): put()
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3918): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/SoundPicker( 3918): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3918): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3918): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3918): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3918): MODE_GSM access default DB
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/EASAppSvc( 3972): [ NA ]- onDestroy()
I/EASAppSvc( 3972): [ NA ]> uninitEASService
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/EASRequestController( 3972): [ NA ]release
I/EASAppSvc( 3972): [ NA ]< uninitEASService
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4018 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/AutoSetting( 1343): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1343): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1343): service - requestNLP() NetworkLocationProvider not enabled
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3918): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
D/ORMLib  ( 3447): put()
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
D/PMS     (  906): releaseWL(42def628): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3918): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3918): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3918): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/MediaStoreImporter( 3862): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/Process (  906): killProcessQuiet, pid=3745
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3745:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/PMS     (  906): acquireWL(42ea0660): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1523 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/ActivityManager(  906): Recipient 3745
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(42ea0660): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/TelephonyReceiver( 1239): bind: false
D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4034 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/Process (  906): killProcessQuiet, pid=3762
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3762:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/PMS     (  906): acquireWL(42e65560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3762
,D/PMS     (  906): releaseWL(42e65560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/PackageManager(  906): Unable to load service info ResolveInfo{42df0f70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 3708): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3708): loadItems() com.htc.launcher.pageview.WidgetManager@42424c18 +
,I/Prism.WidgetManager( 3708): onLoadItems() +
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@42443cb0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4052 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=46 rxSum=33} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20331 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20332 delay=15s
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42797e10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.updater 3 9 1 10
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42501088 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.updater 1 8 0 10
,D/PMS     (  906): acquireWL(42fd3460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fd3460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42efb8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42efb8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(42f4e588): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42f4e588): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42fbb858): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fbb858): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42eef1e8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42eef1e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4052): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  906): acquireWL(42ede5a8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3708
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3708:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1343): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1343): handle notify Blinkfeed plugin client changed
D/PMS     (  906): releaseWL(42ede5a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
D/PMS     (  906): acquireWL(42ff5318): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ff5318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4052): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  906): acquireWL(42ff5e50): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4052): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4052): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4052): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  906): Recipient 3708
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(42ff5e50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@42443cb0 -
D/PMS     (  906): acquireWL(42e70a58): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e70a58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f15828): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f15828): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42edcce8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42edcce8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f02060): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f02060): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42fd23c8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fd23c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4305a9a0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4305a9a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f98eb0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f98eb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f956c8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f956c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 320 ms] updated apps [took 320 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42f5d810): PARTIAL_WAKE_LOCK  AsyncService 0x1 3596 10160 null
,D/PMS     (  906): releaseWL(42f5d810): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4092 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4092, uid=10074, userID:0
,D/Settings:HtcWirelessFeatureFlags( 3804): id/is att sku: 99/false
,D/Finsky  ( 4092): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/SystemReader( 3804): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4092/10074)
,W/SystemReader( 3804): Cannot find support_harman, use default value instead
,W/SystemReader( 3804): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3804): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3804): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3804): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3804): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]support         :false
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/FingerprintManager( 3804): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3804): isSupportVoWifi: null
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
E/ActivityThread( 3804): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4092/10074)
,D/Finsky  ( 4092): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4092): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4092): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4092, uid=10074, userID:0
,D/Ads     ( 4092): Skipping gmscore version check
,D/Finsky  ( 4092): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4092): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4092): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3804): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3804): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3804): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3804): [supportHomeButton]support         :false
,W/dalvikvm( 4092): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/FingerprintManager( 3804): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3804): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3804): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4092): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  906): killProcessQuiet, pid=3780
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3780:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 3780
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  906): acquireWL(43066320): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43066320): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42fe5c20): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2179): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2179): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2179): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2179): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2179): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2179): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2179): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2179, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2179): cleanUpNonGplusAccounts done.
,I/SocialFeedProvider( 1269): +disConnect socialManager
,I/SocialFeedProvider( 1269): disconnect socialManager
,I/SocialFeedProvider( 1269): -disConnect socialManager
,D/Process (  906): killProcessQuiet, pid=3683
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3683:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3683
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(42fe5c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4136 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4136): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4136): MmsConfig.loadMmsSettings
,W/dalvikvm( 4136): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4136): VFY: unable to resolve instance field 36
,W/dalvikvm( 4136): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4136, uid=10111, userID:0
D/MmsCustomizationProvider( 3725): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/Settings( 4136): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 3725): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4136): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4136): MmsConfig.loadFromDatabase
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4136, uid=10111, userID:0
D/PMS     (  906): acquireWL(430087a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
E/Babel   ( 4136): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4136): MmsConfig.loadFromResources
E/Babel   ( 4136): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4136): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4136): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(430087a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4300cf28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4172 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{42634e80: PendingIntentRecord{42e26d10 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454578885370, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4257cfa0: PendingIntentRecord{42daaef0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59798, Int=0
,I/ImageRamCache( 4172): create image Cache, size: 31457280.
I/ImageRamCache( 4172): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4172): create image Cache, size: 12582912.
,I/FeedSettings( 4172): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4172): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4172): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4172): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4172): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4172): loadGridSize() with Alternative
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 6 times.
,I/SocialManager[SocialBiLogHelper]( 4172): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4172): last commit ulog time 1454479133305
,I/SocialManager[SocialBiLogHelper]( 4172): do commit ulog
,D/PMS     (  906): releaseWL(4300cf28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3696
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3696:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/PMS     (  906): acquireWL(42feb990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
I/ActivityManager(  906): Recipient 3696
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/PMS     (  906): releaseWL(42feb990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42fc6d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4190 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42fc6d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/ImageRamCache( 4190): create image Cache, size: 31457280.
I/ImageRamCache( 4190): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4190): create image Cache, size: 12582912.
,I/FeedSettings( 4190): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4190): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4190): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4190): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4190): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4190): loadGridSize() with Alternative
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3823
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/SocialManagerService( 1343): getDataSources
,I/ActivityManager(  906): Killing 3823:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/SocialManagerService( 1343): plugin added: com.facebook.auth.login
I/SocialManagerService( 1343): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1343): plugin added: com.htc.linkedin
I/SocialManagerService( 1343): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1343): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1343): plugin added: com.htc.drive.activator
I/SocialManagerService( 1343): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1343): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1343): plugin added: com.google
,I/SocialManagerService( 1343): device total memory: 1873M
,I/SocialManagerService( 1343): groupAccounts
I/ActivityManager(  906): Recipient 3823
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1380): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
E/SocialManagerService( 1343): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1343): error when get process name! process name is null!
E/SocialManagerService( 1343): skip binding the plugin without process namecom.htc.drive.activator
,I/SocialManagerService( 1343): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1343): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1343): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1343): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1343): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1343): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1343): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1343): add com.google to pending queue!
I/SocialManagerService( 1343): consume pending plugin session
,I/SocialManagerService( 1343): add com.facebook.auth.login to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.facebook.auth.login
,I/SocialManagerService( 1343): com.facebook.auth.login connecting, adding msg, has message?true
,I/SocialManagerService( 1343): add com.htc.linkedin to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.htc.linkedin
,I/SocialManagerService( 1343): com.htc.linkedin connecting, adding msg, has message?true
I/SocialManagerService( 1343): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.twitter.android.auth.login
,I/SocialManagerService( 1343): com.twitter.android.auth.login connecting, adding msg, has message?true
I/SocialManagerService( 1343): add com.htc.venuesrecommend to process map!
,V/SocialManagerService( 1343): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1343): com.htc.venuesrecommend connecting, adding msg, has message?true
W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
I/SocialManagerService( 1343): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1343): add com.htc.socialnetwork.rss.octopus to process map!
,V/SocialManagerService( 1343): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
,I/SocialManagerService( 1343): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
I/ActivityManager(  906): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=4210 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
D/PMS     (  906): acquireWL(42eef6e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42eef6e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SocialManagerService( 1343): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1343): com.htc.opensense.htcnews connecting, adding msg, has message?true
,D/LocationSocialPlugin( 4172): onBind
,I/SocialManagerService( 1343): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1343): com.htc.venuesrecommend connected, removed msg, has message?false
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2179/10029),
,I/SocialManagerService( 1343): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
D/PMS     (  906): acquireWL(42ea6068): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/StreamPluginService( 4172): getDataSources start
D/LocationIdentityProvider( 4172): is_approved false
,D/LocationSocialPlugin( 4172): account null
,D/SocialManagerService( 1343): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
,I/SocialManagerService( 1343): remove account type: com.htc.socialnetwork.rss.octopus from process map!
V/SocialManagerService( 1343): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
,D/LocationSocialPlugin( 4172): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
I/SocialManagerService( 1343): consume pending plugin session
,I/SocialManagerService( 1343): skip to add com.google, plugin per process full!
I/SocialManagerService( 1343): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1343): handling plugin: com.htc.venuesrecommend set result in bg
,I/SocialManagerService( 1343): remove account type: com.htc.venuesrecommend from process map!
V/SocialManagerService( 1343): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1343): consume pending plugin session
,I/SocialManagerService( 1343): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1343): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/SocialManagerService( 1343): com.htc.opensense.htcnews connected, removed msg, has message?false
,D/SocialManagerService( 1343): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1343): remove account type: com.htc.opensense.htcnews from process map!
,I/SocialManagerService( 1343): remove process: com.htc.sense.news from process map!
,V/SocialManagerService( 1343): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1343): consume pending plugin session
I/SocialManagerService( 1343): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1343): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,D/LinkedIn( 4210): contentprovider oncreate getReadableDatabase
,I/SocialManagerService( 1343): com.facebook.auth.login connected, removed msg, has message?false
,D/LinkedIn( 4210): service onBind
,I/SocialManagerService( 1343): com.htc.linkedin connected, removed msg, has message?false
,I/SocialManagerService( 1343): com.twitter.android.auth.login connected, removed msg, has message?false
D/g       ( 4210): get htcisdemo: false
,D/FacebookSocialPluginService( 4210): get htcisdemo: false
,D/Facebook_Session( 4210): MSG_QUERY_ACCOUNT
D/Facebook_Session( 4210): queryAccount
,D/Facebook_Session( 4210): queryAccount enter lock
,D/Facebook_Session( 4210): Facebook Session created
,D/Facebook_Session( 4210): queryAccount
,D/SocialManagerService( 1343): handling plugin: com.htc.linkedin set result in bg
,I/SocialManagerService( 1343): remove account type: com.htc.linkedin from process map!
V/SocialManagerService( 1343): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1343): consume pending plugin session
,I/SocialManagerService( 1343): add com.google to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.google
,I/SocialManagerService( 1343): com.google connecting, adding msg, has message?true
,I/SocialManagerService( 1343): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/Facebook_Session( 4210): Query Facebook account complete
,D/Facebook_Session( 4210): queryAccount enter lock
,D/GooglePlusSocialPluginService( 4210): Bind
,D/Facebook_Session( 4210): Query Facebook account complete
I/SocialManagerService( 1343): com.google connected, removed msg, has message?false
,D/SocialManagerService( 1343): handling plugin: com.twitter.android.auth.login set result in bg
,I/SocialManagerService( 1343): remove account type: com.twitter.android.auth.login from process map!
V/SocialManagerService( 1343): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1343): consume pending plugin session
,I/SocialManagerService( 1343): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1343): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
,I/SocialManagerService( 1343): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
,I/GooglePlusSocialPluginService( 4210): getDataSources start
,D/SocialManagerService( 1343): handling plugin: com.facebook.auth.login set result in bg
,I/SocialManagerService( 1343): remove account type: com.facebook.auth.login from process map!
,V/SocialManagerService( 1343): on plugin completed! plugin session type com.facebook.auth.login
,I/SocialManagerService( 1343): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
,D/SocialManagerService( 1343): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
,I/SocialManagerService( 1343): remove account type: com.htc.sense.socialnetwork.instagram from process map!
,I/GooglePlusSocialPluginService( 4210): getDataSources end
,V/SocialManagerService( 1343): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
,D/SocialManagerService( 1343): handling plugin: com.google set result in bg
I/SocialManagerService( 1343): remove account type: com.google from process map!
,I/SocialManagerService( 1343): remove process: com.htc.sense.socialplugins from process map!
,D/GooglePlusSocialPluginService( 4210): Unbind
V/SocialManagerService( 1343): on plugin completed! plugin session type com.google
,I/SocialManagerService( 1343): onSessionCompleted
,D/Process (  906): killProcessQuiet, pid=3418
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3418:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/SocialManager[SocialBiLogHelper]( 4172): social manager disconnect
D/PMS     (  906): releaseWL(42ea6068): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3418
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3447
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3447:com.htc.task/u0a71 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42bed370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42bed370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42874e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42874e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42481710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(42481710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(430326f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(430326f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=3972
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Recipient 3447
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Killing 3972:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Recipient 3972
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(4303c560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4241 uid=10041 gids={50041}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(4303c560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=3882
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3882:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3882
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4254 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(430469f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4254 10071 null
,D/PMS     (  906): acquireWL(43047088): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4254 10071 null
,D/PMS     (  906): acquireWL(43047ab0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,D/PMS     (  906): releaseWL(430469f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4254): java.lang.NullPointerException
,W/System.err( 4254): java.lang.NullPointerException
W/System.err( 4254): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4254): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4254): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4254): stopSelfResult true
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
D/PMS     (  906): releaseWL(43047088): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(43047ab0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,I/ActivityManager(  906): Killing 3840:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3840
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/LocationInitializer( 2179): Restart initialization of location
,E/MDM     ( 1221): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1380): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1380): Proximity feature is not enabled.
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1221): No location to return for getLastLocation()
W/FusedLocationProvider( 1221): location=null
D/PMS     (  906): acquireWL(42e5d3f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42e5d3f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42e47c08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4254 10071 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/PMS     (  906): acquireWL(42e3d4a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4254 10071 null
D/PMS     (  906): acquireWL(42c8eb88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4254 10071 null
E/TodoTaskNotifyService( 4254): java.lang.NullPointerException
W/System.err( 4254): java.lang.NullPointerException
W/System.err( 4254): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4254): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4254): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): releaseWL(42e47c08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): acquireWL(42e3d4a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4254 10071 null
D/PMS     (  906): releaseWL(42c8eb88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/WSP     ( 1343): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,W/NotifyReceiver( 4254): stopSelfResult false
E/TodoTaskNotifyService( 4254): java.lang.NullPointerException
,W/System.err( 4254): java.lang.NullPointerException
W/System.err( 4254): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4254): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4254): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/NotifyReceiver( 4254): mStartingService is null
D/WeatherUtility( 1343): Weather sync is On
D/PMS     (  906): releaseWL(42e3d4a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Recipient 3840
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/NotifyReceiver( 4254): stopSelfResult true
,I/WSP     ( 1343): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Feb 04 11:41:26 CET 2016
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/PMS     (  906): acquireWL(42ecb338): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1343 10055 null
,D/PMS     (  906): acquireWL(42f1e928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,D/GCM     ( 1380): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(42f1e928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1343): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1343): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(42f10e98): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f10e98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42fbfb20): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fbfb20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42ebb9a8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ebb9a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42ed9d00): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ed9d00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f16fb0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f16fb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4305ecf0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4305ecf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f10468): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f10468): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f6c790): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f6c790): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 217 ms] updated apps [took 217 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42ff0d60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3596 10160 null
,D/PMS     (  906): releaseWL(42ff0d60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  906): acquireWL(42f299a0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 4254): update TASK shortcut>
,V/AlarmManager(  906): sending alarm PendingIntent{42c4f078: PendingIntentRecord{42c4bcd8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454578887176, Int=0
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:73, mTXpacketCount:48, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/Icing   ( 2179): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42f299a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  906): mEventCount = 450
,I/GAV2    ( 4052): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(42fff698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fff698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  906): sending alarm PendingIntent{42cc8fe8: PendingIntentRecord{42cc9090 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454578888979, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42c36a78: PendingIntentRecord{42c2b480 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454578889015, Int=0
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/iu.UploadsManager( 2179): End new media; added: 0, uploading: 0, time: 67 ms
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4136): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 7 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2179, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2179, uid=10029, userID:0
,I/CheckinService( 2179): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,I/CalendarProvider2( 1523): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1523): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42fbad88): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3862 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3862): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3862, uid=10154, userID:0
,I/MusicLeanback( 3862): Conditions not met for autocaching.
,I/MusicLeanback( 3862): Stop autocaching.
D/PMS     (  906): releaseWL(42fbad88): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42f9d500): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42f9d4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,W/ContextImpl( 3862): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  906): releaseWL(42f9d500): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42f9d4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42e60b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42e60b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d68f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42d68f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4243a890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4308 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4243a890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 4308): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  906): killProcessQuiet, pid=3918
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3918:com.htc.sdm/u0a81 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3918
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4328 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4328): Loading default preferences
,W/Resources( 4328): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4328): Overriding preferences with custom values
,D/SyncApplication( 4328): Updating preferences succeeded
,E/SyncApplication( 4328): Application created.
D/VolumeInfo( 4328): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4328): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4328): Found 0 mount point(s)
,V/VolumeInfo( 4328): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4328): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4328): getNewCalendarAuthority()...
,D/VolumeInfo( 4328): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4328): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4328): enableAppOperation()+
,D/SyncApplication( 4328): enableAppOperation()-
,D/HTCUtilities( 4328): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4328, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4328, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4328): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4328): isNeorSinged() return false
,D/CDMountReceiver( 4328): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4328): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4328): enable CD Auto-mount: true
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4328): enable auto-mount
,D/HTCUtilities( 4328): enable auto-mount
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{4279f918 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42fd06c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 13 4 11
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/Process (  906): killProcessQuiet, pid=4018
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4349 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 4018:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42562f40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 10 2 16
,I/ActivityManager(  906): Recipient 4018
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3804): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3804): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3804): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3804): Cust_ConnectToPC   : spcsc>false
D/        ( 3804): Cust_ConnectToPC   : IPT>true
,D/        ( 3804): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3804): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3804): Index of the first 1 = -1
,W/Settings( 3804): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3804): hasRemovableStorageSlot: true
W/ContextImpl( 3804): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3804): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3804): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3804): [ACC]android_networking:tethering_guard_support=false
,D/Process (  906): killProcessQuiet, pid=4034
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4362 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 4034:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4034
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4362): onCreate
D/ProviderChangeReceiver( 4362): ---------------------------------------------------
,D/ProviderChangeReceiver( 4362): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4362): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4376 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3615
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3615:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3615
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AlertService( 4362): No fired or scheduled alerts
D/HtcAlertUtils( 4362): -- cancelReminderNotification --
D/HtcAlertUtils( 4362): broadcastExistReminder!
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4376): [4376/4376] onCreate()
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3725
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3725:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3725
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 8 times.
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42fe25b8 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  906): releaseWL(42ecb338): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42f90238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f90238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=46 rxSum=33} preTxRxSum={txSum=46 rxSum=33}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20332 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20333 delay=15s
D/PMS     (  906): acquireWL(43042600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42e70368: PendingIntentRecord{42c91968 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=72467, Int=0
D/PMS     (  906): releaseWL(43042600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  906): mEventCount = 600
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 9 times.
,D/Finsky  ( 4092): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/PMS     (  906): acquireWL(42fc5570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,W/dalvikvm( 4092): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  906): sending alarm PendingIntent{42df5dc0: PendingIntentRecord{42f96fa8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454578900825, Int=0
D/PMS     (  906): releaseWL(42fc5570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4092/10074)
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4092): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4092): [NET] getaddrinfo-,err=8
D/libc    ( 4092): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4092): [NET] getaddrinfo-, 1
D/libc    ( 4092): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a1af +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4092): [NET] getaddrinfo_proxy-, success
,I/global  ( 4092): call createSocket() return a new socket.
D/libc    ( 4092): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4092): [NET] getaddrinfo-, SUCCESS,
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4092): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4092): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4092): untagSocket(69) failed with errno -22
,D/Finsky  ( 4092): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4092): untagSocket(69) failed with errno -22
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=21 [56][12][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:141, mTXpacketCount:73, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/NetworkManagementSocketTagger( 4092): untagSocket(69) failed with errno -22
,D/Finsky  ( 4092): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
,D/Finsky  ( 4092): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4092/10074)
,D/Finsky  ( 4092): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(42e12b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42ccfd90: PendingIntentRecord{42e32318 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454578903228, Int=0
,D/PMS     (  906): acquireWL(42e45720): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4092 10074 null
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/Finsky  ( 4092): [434] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4092): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 1221): client connected with version: 8296000
D/PMS     (  906): releaseWL(42e12b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4092/10074)
,I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.vending.verifier.VerifyInstalledPackagesReceiver
,D/Finsky  ( 4092): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4092): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4092): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  906): Resuming delayed broadcast
,D/libc    ( 4092): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4092): [NET] getaddrinfo-,err=8
D/libc    ( 4092): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4092): [NET] getaddrinfo-, 1
,D/libc    ( 4092): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =222f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299,
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4092): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(42e45720): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 10 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [22][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/AutoSetting( 1343): service - has update message, not stop
,D/AutoSetting( 1343): service - mHandler: update timezone
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1523): service - mHandler: update timezone
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1523): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1523): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{427ce998 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 7 2 11
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 11 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42fcf7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fcf7b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42fdd4e0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42fdd4e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e30fb0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e30fb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=123 rxSum=107} preTxRxSum={txSum=46 rxSum=33}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20333 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  906): acquireWL(42e8d9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42ee0dd0: PendingIntentRecord{42c91968 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87473, Int=0
,D/PMS     (  906): releaseWL(42e8d9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20334 delay=15s
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 12 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:164, mTXpacketCount:141, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  906): acquireWL(430582e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=94406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1115): now=1454578920053 next=59947
D/PMS     (  906): releaseWL(430582e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1523): Don't start project servcice
,D/HtcModeClient( 1523): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1523): connectState: CONNECTION_READY = false
D/SilentMusic( 1523): call stop
D/HtcModeClient( 1523): close connection
W/HtcModeClient( 1523): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1523): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42f57700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42ff1e68: PendingIntentRecord{4304a0d0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454578917454, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4413 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{42f25118: PendingIntentRecord{42f1e5f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454578921267, Int=60000
,D/PMS     (  906): releaseWL(42f57700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078},
,D/SMSBackup( 4413): SMSBackupAgentService started
,D/SMSBackup( 4413): Checking restore status
,D/SMSBackup( 4413): Restore complete
,D/SMSBackup( 4413): cancelCheckAlarm
,D/SMSBackup( 4413): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/Finsky  ( 4092): [425] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4092): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=4172
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4172:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4172
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42f88a80 u0 com.htc.htclocationservice/.AutoSettingService}
,V/LightsService(  906): setLight #0: color=#3f
,V/LightsService(  906): setLight #0: color=#38
,V/LightsService(  906): setLight #0: color=#31
,V/LightsService(  906): setLight #0: color=#2e
,V/LightsService(  906): setLight #0: color=#27
,V/LightsService(  906): setLight #0: color=#21
,V/LightsService(  906): setLight #0: color=#1a
,V/LightsService(  906): setLight #0: color=#14
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=123 rxSum=107} preTxRxSum={txSum=123 rxSum=107}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20334 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20335 delay=15s
D/PMS     (  906): acquireWL(42f87848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42cdcfd8: PendingIntentRecord{42c91968 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102480, Int=0
D/PMS     (  906): releaseWL(42f87848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a7bc18
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a7bc18, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42998658
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42ecd508
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 339ms
D/PMS     (  906): nativeSetInteractive:false
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42fe8408)
,D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): Disable input method client, pid=1269
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,D/PMS     (  906): acquireWL(4302e5d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/NfcService( 1252): applyRouting -2
,W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): acquireWL(4302f430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4302e5d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/MtpService( 1932): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1932): [MTP][onReceive]-
,D/NfcService( 1252): applyRouting - 0
,D/AutoSetting( 1343): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1252): applyRouting -2
D/PMS     (  906): releaseWL(4302f430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): acquireWL(42ff8698): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMS     (  906): releaseWL(42ff8698): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3804): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3804): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3804): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3804): Cust_ConnectToPC   : spcsc>false
D/        ( 3804): Cust_ConnectToPC   : IPT>true
,D/        ( 3804): Cust_ConnectToPC   : Singel_USB>false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/HtcPowerSaver(  906): updateBatteryInfo
W/Settings( 3804): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3804): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3804): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/AutoSetting( 1343): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/SmartNS_NSReceiver( 3804): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/PSReceiver( 3804): onReceive:android.intent.action.USER_PRESENT
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 3804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20336 delay=15s
I/SmartNS_PSService( 3804): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3804): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3804):  defaultType:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:On
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
I/HtcPowerSaver(  906): << updateStatus
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
D/PowerUI ( 1115): closing low battery warning: level=100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1115): stop update clock
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:164, mTXpacketCount:164, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4349): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(4302a708): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4349 1000 null
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(4302b9e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4302b9e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43090670): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4302a708): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1744): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): onScreenOn: 1454578931262
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1744): onScreenOn: 1454578931262
D/PMS     (  906): releaseWL(43090670): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42998658
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42998658, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42ecd508
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4349): getMobilePolicyEnabled, result = true
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43095f20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1269): [onPause]
,I/FeedProviderManager( 1269): onPause
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
,I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424a0ea8
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20336 mDataStallAlarmIntent=PendingIntent{42e057e8: PendingIntentRecord{42c91968 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:Off
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6,
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43095f20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): acquireWL(430a2180): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): releaseWL(430a2180): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/SmartSyncUtils( 4349): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4349): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4349): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42ecd508
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42ecd508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42ecd508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42ecd508
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 56
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42ecda50 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42ecda50 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1343): service - mHandler: cancel location update
,D/AutoSetting( 1343): service -           changes count: 0
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  906): acquireWL(430b8de0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(430b8de0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430ba288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(430ba288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1744): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1744): onScreenOff
,D/AutoSetting( 1523): service - handleMessage() stop self
,D/AutoSetting( 1523): service - onDestroy() END
,D/AutoSetting( 1523): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4210
,I/ActivityManager(  906): Killing 4210:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4210
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  906): killProcessQuiet, pid=3897
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3897:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3897
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(430c2c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  906): sending alarm PendingIntent{42ee4be0: PendingIntentRecord{42cbfaf8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120413, Int=0
,D/PMS     (  906): releaseWL(430c2c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430c4a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(430cad70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(430cad70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(430c4a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430d08e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(430d08e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430d4840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(430dd6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430e5880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1454578946294 tag=VacuumService
,D/PMS     (  906): releaseWL(430d4840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(430dd6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430f0048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(430f0048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430f3f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/PMS     (  906): releaseWL(430e5880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(430f3f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430fb560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(430fb560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(430ff4b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(430ff4b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(431062e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4310f0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4310f0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43116a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(431062e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4311bbb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(4311bbb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 13071 seconds from now (1454578947123)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6ad3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=16 [12][2][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(43116a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4313d530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(4313d530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43143b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(43143b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4314b7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): releaseWL(4314b7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43150b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{423df3d8: PendingIntentRecord{42d971b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135905, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,D/PMS     (  906): releaseWL(43150b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1343): service - handleMessage() stop self
,D/AutoSetting( 1343): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4190
,D/AutoSetting( 1343): service - handleMessage() quit looper
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4190:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4190
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(431573c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42dabe58: PendingIntentRecord{42974708 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141815, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(431586c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(431573c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6c85 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(431586c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(4318f298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4318f298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43190af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154407, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43190af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43193428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
V/AlarmManager(  906): sending alarm PendingIntent{42e93438: PendingIntentRecord{42fa7388 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171994, Int=0
,D/PMS     (  906): releaseWL(43193428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(431955d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431955d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4319ae18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4319ae18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4319be90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4319be90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4319e0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4319e0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(4319fa00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4319fa00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(431a1c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431a1c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431a3688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=334406, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431a3688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(431a57a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431a57a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(431a6cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431a6cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(431ac060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431ac060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(431ae2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431ae2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431afbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=454406, Int=0
,D/PMS     (  906): releaseWL(431afbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(431b29b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(431b29b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(431b85a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=514406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431b85a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43126910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43126910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43046868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=574406, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43046868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43045a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43045a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1239): sku_id=99
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/PMS     (  906): acquireWL(43041548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43041548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43008a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=634406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43008a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4241
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4241:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4241
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42fff698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fff698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ffc240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=694407, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ffc240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ffbf40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ffbf40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ffafc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=754407, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ffafc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ff1ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ff1ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42feaa70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=814406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42feaa70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fe1e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fe1e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42fe1b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=874406, Int=0
,D/PMS     (  906): releaseWL(42fe1b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fdeaa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fdeaa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42fd7be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=934406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42fd7be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fd2f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{425f99f8: PendingIntentRecord{42d44c18 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780609, Int=0
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4478 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{42ee4a40: PendingIntentRecord{42e3f2a0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{428877f0: PendingIntentRecord{42de4978 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=946142, Int=0
,D/PMS     (  906): acquireWL(42f5bd60): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f5bd60): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4490 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  906): sending alarm PendingIntent{42b323e8: PendingIntentRecord{42833bb8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454579037040, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42eaa450: PendingIntentRecord{42cd1b48 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454579114659, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{42ed7c90: PendingIntentRecord{42faa530 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454579757470, Int=900000
,D/PMS     (  906): acquireWL(42db3208): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d2f848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1380 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1380/10029)
W/ContextImpl( 4349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): acquireWL(42827f00): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/ImageRamCache( 4478): create image Cache, size: 31457280.
I/ImageRamCache( 4478): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4478): create image Cache, size: 12582912.
,I/FeedSettings( 4478): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4478): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4478): GroupBudget 60 45 15
,D/PowerUsageService( 4349): call getInstance()
D/PMS     (  906): releaseWL(42db3208): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1380/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
,I/Prism.ExternalStringMa_( 4478): changeLocale(): en_GB
,D/PowerUsageList:PowerUsageHelper( 4349): MY_DEBUG = false
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
D/PMS     (  906): releaseWL(42fd2f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(42d2f848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.AllAppsOptionsMa_( 4478): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4478): loadGridSize() with Alternative
,I/EventLogService( 2179): Aggregate from 1454578877294 (log), 1454577314580 (data)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4490/10049)
W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/PMS     (  906): releaseWL(42827f00): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4478): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4478): [NET] getaddrinfo-,err=8
D/libc    ( 4478): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4478): [NET] getaddrinfo-, 1
,D/libc    ( 4478): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4bf9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =,
,D/libc    (  363): [NET] NOT IN CACHE
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=206
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4478): [NET] getaddrinfo_proxy-, success
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/Process (  906): killProcessQuiet, pid=4136
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4136:com.google.android.talk/u0a111 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (4478/10076)
,I/ActivityManager(  906): Recipient 4136
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (4478/10076)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024303
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024621
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024625
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024628
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029123
,D/Process (  906): killProcessQuiet, pid=4254
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4254:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4254
,D/PMS     (  906): acquireWL(43183070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43183070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43184968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994406, Int=0
,D/PMS     (  906): releaseWL(43184968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431877c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4349): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{42f587d8: PendingIntentRecord{43091d80 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454579831394, Int=0
,D/PMS     (  906): acquireWL(43188bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4349 1000 null
,D/PMS     (  906): releaseWL(431877c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4349): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4349): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4349): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4349): SettingOnTime = 1454652000000, randomSettingOnTime = 1454651719000
,D/SmartSyncScreenOnOffTimeReceiver( 4349): SettingOffTime = 1454637600000, randomSettingOffTime = 1454643840000
,D/SmartSyncScreenOnOffTimeReceiver( 4349): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4349): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4349): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(43188bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(431685c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431685c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43169ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43169ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4316c130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4316c130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4316db68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1114406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4316db68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4316fc90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4316fc90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431715b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1174406, Int=0
,D/PMS     (  906): releaseWL(431715b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43173dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43173dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(431756f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{428d64d8: PendingIntentRecord{424850a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1234406, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431756f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4515): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4515): ====startRecUseTime====
D/htc.customization.log.level( 4515):  is 
W/CustomizationLogLevel( 4515): Level value is invalid, use default level 2
D/CustomizationManager( 4515):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4515): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4515): Parsing tag category name = system
I/CustomizationCIDLoader( 4515): Parsing tag category name = application
I/CustomizationCIDLoader( 4515): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4515): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4515): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4515): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4515): Parsing tag category name = Settings
D/CustomizationManager( 4515):  Read CID file spent 0.149 (s)
D/CustomizationManager( 4515):  All configurations done spent 0.149 (s)
W/HtcNativeFlag( 4515): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4515): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4515): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4515): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4515, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{42a92698 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{42a96308 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  906): acquireWL(431b37b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(431b37b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 4478): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4478): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 1343): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1343): handle notify Blinkfeed plugin client changed
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/IcingCorporaProvider( 2821): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4530 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/IcingCorporaProvider( 2821): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4530): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4530): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4530): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4530): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4530): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4530): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4530): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4530): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4530): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4530): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4530): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4530): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4530): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4530): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4530): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4530): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4530): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4530): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4530): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4530): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4530): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4530): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4530): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4530): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4530): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4530): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4530): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4530): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4530): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4530): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4530): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4530): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4530): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4530): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4530): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4530): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4530): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4530): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4530): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4530): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4530): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4530): threadid=11: thread exiting with uncaught exception (group=0x41f80e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4530): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4530): Process: com.google.android.apps.docs, PID: 4530
E/AndroidRuntime( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4530): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4530): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4530): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4530): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4530): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4530): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4530): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4530): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4530): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4530): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4530): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4530): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4530): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4530): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4530): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4530): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4530): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4530): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4530): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4530): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4530): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4530): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4530): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4530): Opened ClientFlag.db in read-only mode
D/Process ( 4530): killProcess, pid=4530
D/Process ( 4530): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4549 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4530
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4530) has died.
W/ContextImpl( 4549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4562 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4549): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4549): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4549): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4549): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4549): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4549): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4549): threadid=10: thread exiting with uncaught exception (group=0x41f80e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4549): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4549): Process: com.android.keychain, PID: 4549
E/AndroidRuntime( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4549): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4549): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4549): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4549): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4549): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@42443cb0 +
I/Prism.WidgetManager( 1269): onLoadItems() +
I/Prism.ItemManager( 4478): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4478): loadItems() com.htc.launcher.pageview.WidgetManager@42419770 +
I/Prism.WidgetManager( 4478): onLoadItems() +
D/AppTag  ( 4562): getInstance(Context context)
D/AppTag  ( 4562): getInstance(Context context)
D/AppTag  ( 4562): onCreate()
D/Process ( 4549): killProcess, pid=4549
D/Process ( 4549): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454580095034.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4549
D/PMS     (  906): acquireWL(431b5188): PARTIAL_WAKE_LOCK  AsyncService 0x1 3596 10160 null
I/ActivityManager(  906): Process com.android.keychain (pid 4549) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  906): releaseWL(431b5188): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  906): killProcessQuiet, pid=3862
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3862:com.google.android.music:main/u0a154 (adj 15): empty #17
W/dalvikvm( 4092): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2179): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2179): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2179): Removing dialog suppression flag for package com.test.thalitest

```
